## Utilizando o projeto no ionic em novo computador
- 1 - Baixe ou clone este projeto
- 2 - Navegue até dentro da pasta pelo terminal (CMD)
- 3 - Certifique-se de tenha instalado o NodeJS mais atualizado do site oficial: https://nodejs.org/en/download/
- 4 - Faça o download das dependencias através do comando: npm install *cerca de 160MB*. (ele captura as dependencias do projeto que utilizam as bibliotecas. Estas mesmas não acompanham no projeto por se tratar de arquivos grandes)
- 5 - Para rodar o aplicativo, navegue dentro da pasta do projeto através do console, e execute o seguinte comando: ionic serve

## Obs.: Constantemente armazena cache
Caso queira fazer alterações no Angular, TypeScript e Html, recomenda-se limpar o cache, ou simplesmente reiniciar o servidor

## Gerar APK
Caso faça modificações e queira gerar APK  para Android, certifique-se de que tenha instalado o Android Studio: https://developer.android.com/studio/install.html?hl=pt-br
Certifique-se de que todas as atualizações estejam instaladas adtravés do SDK Manager: Abra o Android Studio -> Configure -> SDK Manager ->  Abas: Appareance & Behavior -> System Settings -> Android SDK. Dentro selecione a aba SDK Tools
Todas as checkbox com "-" foram assinaladas para "Check": 
- Android SKD Build-Tools
- Android Emulator
- Android SKD Platform-Tools
- Android  SDK Tools
- Google Play APK Expansion Library
- Instant Apps Development SDK
- Intel x86 Emulator Accelerator
- Support Repository.

- Faça a instalação de todas as atualizações

- Após atualizar as SDKs, adicione o caminho da pasta nos PATH de seu computador, localizado em: Configurações do Windows -> Sistema -> Sobre -> Em Configurações Relacionadas: Informações do Sistema -> Configurações avançadas do sistema -> Aba: Avançado -> Botão: Variaveis do Ambiente -> Em: Variaveis do Sistema adicione uma nova variavel clicando onde se localiza PATH e EDITAR -> Na nova janela clique em Novo e adicione o caminho até a PASTA onde se localiza os SDK por exemplo: "C:\Users\LUCASDOMINGOSLEAOGOM\AppData\Local\Android\Sdk"

Para gerar o APK, utilize o seguinte comando: ionic cordova build android.

## Guias Uteis para problemas
- Gerar APK - Problemas com o SDK e Lisença: https://stackoverflow.com/questions/40383323/cant-accept-license-agreement-android-sdk-platform-24/40383457#40383457
 - Converter tabelas Excel para JSON: http://www.convertcsv.com/json-to-csv.htm
