![Lumi Play · Downloads oficiais](assets/lumi-play.svg)

O Lumi Play reproduz suas playlists de canais, filmes e séries.

## Escolha o seu aparelho

| Plataforma | Download |
| :--- | :--- |
| <img src="assets/windows.svg" width="24" alt=""> **Windows 10 e 11 · 64 bits** | [Baixar ZIP para Windows](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-build.1-windows-x64-portable.zip) |
| <img src="assets/android.svg" width="24" alt=""> **Android celular** | [Baixar APK para celular](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.2.4-build.6/LumiPlay-0.2.4-build.6-android.apk) |
| <img src="assets/android.svg" width="24" alt=""> **Android TV e TV Box** | [Baixar APK para Android TV](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.2.4-build.6/LumiPlay-0.2.4-build.6-android.apk) |
| <img src="assets/iphone.svg" width="24" alt=""> **iPhone físico** | [Baixar IPA para iPhone](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-iphone.ipa) · Instalação pelo Windows com assinatura local |
| <img src="assets/iphone.svg" width="24" alt=""> **iOS Simulator** | [Baixar build de teste para o iOS Simulator](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-build.1-ios-simulator.zip) · Requer um Mac com Xcode |
| <img src="assets/mac.svg" width="24" alt=""> **Mac** | Aplicativo nativo para macOS em planejamento. No Mac, já é possível testar a build do iPhone no Simulator. |

## Windows

1. Baixe o ZIP portátil pela tabela acima.
2. Clique com o botão direito no ZIP, escolha **Extrair tudo** e abra a pasta extraída.
3. Execute `lumi_play.exe` dentro dessa pasta. Mantenha as DLLs e os demais arquivos ao lado do executável.

Para atualizar, feche o app e extraia o novo ZIP em uma pasta diferente. Suas playlists e preferências ficam no perfil do Windows.

## Android

O APK listado para celular e Android TV ? o mesmo pacote universal. Na TV, instale a op??o **Android TV e TV Box**; a navega??o usa o controle remoto. [Verificar SHA-256](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.2.4-build.6/LumiPlay-0.2.4-build.6-android.apk.sha256).

1. No aparelho, baixe o APK pela tabela acima.
2. Abra o arquivo em **Downloads**.
3. Se o Android pedir, toque em **Configurações** e autorize **Permitir desta fonte** para o navegador ou gerenciador de arquivos que abriu o APK.
4. Volte à instalação, toque em **Instalar** e depois em **Abrir**.

Para atualizar, instale o APK mais recente sobre o app existente, quando a assinatura for compatível. [Guia do Android para instalar um APK](https://support.google.com/pixelphone/answer/7391672?hl=pt-BR)

## iPhone físico pelo Windows

A build requer iOS 15.0 ou superior. Você pode baixar o IPA no iPhone. A instalação usa o PC Windows para assinar o app com a sua conta Apple.

1. Baixe o [IPA do Lumi Play](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-iphone.ipa) e salve em **Arquivos** no iPhone.
2. No Windows, configure o AltServer e instale o **AltStore Classic** no iPhone conectado por USB. [Guia do AltStore para Windows](https://faq.altstore.io/altstore-classic/how-to-install-altstore-windows)
3. Com o iPhone conectado e o AltServer aberto no PC, abra o AltStore no iPhone. Vá a **My Apps**, toque em **+** e selecione o IPA.
4. Abra o **Lumi Play** na tela inicial. Se o iOS pedir, siga a seção **Developer Mode** no guia do AltStore.
5. Com uma conta Apple gratuita, renove a instalação a cada sete dias em **AltStore → My Apps → Refresh All**. [Guia de renovação](https://faq.altstore.io/altstore-classic/your-altstore)

[Verificar SHA-256 do IPA](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-iphone.ipa.sha256)

## iPhone no iOS Simulator

Use o ZIP do Simulator para testar em um iPhone virtual no Mac.

1. Em um Mac com Apple Silicon, instale o **Xcode** e baixe um runtime do iOS Simulator.
2. Baixe o ZIP de iOS pela tabela acima e extraia até obter `Runner.app`.
3. Abra um iPhone virtual em **Xcode → Open Developer Tool → Simulator**.
4. Arraste `Runner.app` para a janela do iPhone virtual. Quando a instalação terminar, abra **Lumi Play** na tela inicial do Simulator. [Guia do Simulator da Apple](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/iOS_Simulator_Guide/InteractingwiththeiOSSimulator/InteractingwiththeiOSSimulator.html)

## Como usar o Lumi Play

1. Abra **Playlists → Adicionar**.
2. Dê um nome à lista e selecione o formato fornecido pelo seu serviço. Use **M3U-URL** para colar um endereço, **M3U-arquivo** para escolher um arquivo ou **Xtream** para informar servidor, usuário e senha.
3. Toque ou clique em **Salvar**. No Windows, dê dois cliques na playlist para carregá-la. No Android e no iPhone virtual, toque uma vez. Aguarde o catálogo carregar.
4. Abra **Canais**, **Filmes** ou **Séries** e escolha o que quer reproduzir.
5. Para arquivos compatíveis, use **Baixar offline**. Acompanhe o progresso em **Offline** e selecione **Reproduzir offline** quando o download terminar.

[Ver versões anteriores e hashes SHA-256](https://github.com/vnshot/lumi-play-downloads/releases) · [Relatar um problema](https://github.com/vnshot/lumi-play-downloads/issues/new)
