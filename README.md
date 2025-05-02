このWEBアプリは俺専用のAIです。
シングルページで大丈夫です。
フロントはvue, 裏側はphp(UIなし。APIだけのサーバー)
dbは俺の話したことを全部記憶してくれる（古い記憶は要点をまとめて自動で圧縮する）
インターフェースは電話とチャットのみで電話する前は
電話中は close のicon を配置して欲しい。
仕組みは会話の仕組みは/apichat/tabiguideのapi/chatService.phpを参考にして。フロント側は/tabiguide_guest/pages/ChatPage.vue , tabiguide_guest/store/hat.js を参考にして。
ChatPage.vueのインターフェースの右上にmaterial icon のcall を配置して。通話は/tabiguide_guest/pages/CallPage.vueを参考にして 
