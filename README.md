![Lumi Play · Downloads oficiais](assets/lumi-play.svg)

O Lumi Play reproduz suas playlists de canais, filmes e séries.

## Escolha o seu aparelho

| Plataforma | Download |
| :--- | :--- |
| <img src="assets/windows.svg" width="24" alt=""> **Windows 10 e 11 · 64 bits** | [Baixar ZIP para Windows](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-build.1-windows-x64-portable.zip) |
| <img src="assets/android.svg" width="24" alt=""> **Android** | [Baixar APK para Android](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-build.1-android.apk) |
| <img src="assets/iphone.svg" width="24" alt=""> **iPhone** | [Baixar build de teste para o iOS Simulator](https://github.com/vnshot/lumi-play-downloads/releases/download/v0.1.0-build.1/LumiPlay-0.1.0-build.1-ios-simulator.zip) · Requer um Mac com Xcode |
| <img src="assets/mac.svg" width="24" alt=""> **Mac** | Aplicativo nativo para macOS em planejamento. No Mac, já é possível testar a build do iPhone no Simulator. |

## Windows

1. Baixe o ZIP portátil pela tabela acima.
2. Clique com o botão direito no ZIP, escolha **Extrair tudo** e abra a pasta extraída.
3. Execute `lumi_play.exe` dentro dessa pasta. Mantenha as DLLs e os demais arquivos ao lado do executável.

Para atualizar, feche o app e extraia o novo ZIP em uma pasta diferente. Suas playlists e preferências ficam no perfil do Windows.

## Android

1. No aparelho, baixe o APK pela tabela acima.
2. Abra o arquivo em **Downloads**.
3. Se o Android pedir, toque em **Configurações** e autorize **Permitir desta fonte** para o navegador ou gerenciador de arquivos que abriu o APK.
4. Volte à instalação, toque em **Instalar** e depois em **Abrir**.

Para atualizar, instale o APK mais recente sobre o app existente, quando a assinatura for compatível. [Guia do Android para instalar um APK](https://support.google.com/pixelphone/answer/7391672?hl=pt-BR)

## iPhone no iOS Simulator

A build atual é de teste para o Simulator. A instalação em um **iPhone físico** exige uma versão assinada para o aparelho, que ainda não está disponível nesta release.

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
