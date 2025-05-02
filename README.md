このWEBアプリは俺専用のAIです。
シングルページで大丈夫です。
フロントはvue, 裏側はphp(UIなし。APIだけのサーバー)
dbは俺の話したことを全部記憶してくれる（古い記憶は要点をまとめて自動で圧縮する）
インターフェースは電話とチャットのみで電話する前は
電話中は close のicon を配置して欲しい。
仕組みは会話の仕組みは konishi0221/tabiguide/api/chat/chatService.phpを参考にして。フロント側はkinishi0221/tabiguide_guest/pages/ChatPage.vue , tabiguide_guest/store/hat.js を参考にして。
ChatPage.vueのインターフェースの右上にmaterial icon のcall を配置して。通話はフロント側はkinishi0221/tabiguide_guest/pages/CallPage.vueを参考にして 
aiはgpt-4oフロントのホスティングはcloud run で行く。
