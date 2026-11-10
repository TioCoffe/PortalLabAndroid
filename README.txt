PORTAL LAB FAN GAME — PROJETO ANDROID

Este projeto prepara o jogo HTML/CSS/JavaScript como aplicação Android em ecrã inteiro,
na horizontal, usando WebView. Os controlos táteis já existentes no jogo são mantidos.

COMO GERAR O APK:
1. Instala o Android Studio num computador.
2. Abre a pasta PortalLabAndroid no Android Studio (Open).
3. Aguarda pela sincronização do Gradle e instala o Android SDK Platform 35 se for pedido.
4. Escolhe Build > Build Bundle(s) / APK(s) > Build APK(s).
5. O APK de teste ficará em app/build/outputs/apk/debug/app-debug.apk.

NOTA IMPORTANTE:
O jogo carrega a biblioteca Three.js a partir do CDN público (cdnjs), conforme o HTML original.
Por isso, é necessária ligação à Internet para iniciar o jogo. O APK inclui os ficheiros do jogo,
mas não inclui uma cópia local da biblioteca Three.js.

É um projeto de fã não oficial. Portal e respetivas marcas pertencem aos seus titulares.
