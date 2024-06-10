# Como configurar/instalar o `Telegram Desktop` no  `Linux Ubuntu` 

## Resumo

Neste documento estão contidos os principais comandos e configurações para configurar/instalar o `Telegram Desktop` no  `Linux Ubuntu` .

## Abstract

This document contains the main commands and settings to configure/install `Telegram Desktop` on  `Linux Ubuntu` .

## Revisão(ões)/Versão(ões)

|Revisão número|Data da revisão|Descrição da revisão|Autor da revisão|
|:-:|:-:|:-|:-|
|0|18/10/2023|<ul><li>Revisão inicial/criação do documento.</li></ul>|Eden Denis F. da S. L. Santos|
|1|16/11/2023|<ul><li>Incluída a Seção Descrição.</li></ul>|Eden Denis F. da S. L. Santos|

## Controle de configuração/instalação nos Sistemas Operacionais (SO) vs. Computador

|Numero|Computador          |Sistema Operacional (SO) |Tipo de sistema |Status da configuração/instalação|
|:----:|:------------------:|:-----------------------:|:--------------:|:-------------------------------:|
|1     |Dell Precision 7520 |Kali   Linux             |Debian          |Pendente                         |
|2     |Dell Precision 7520 |Linux Ubuntu             |Ubuntu          |N/A                              |
|3     |Dell Precision 7520 |Linux Xubuntu            |Ubuntu          |Pendente                         |
|4     |Dell Precision 7520 |Windows 10               |Windows         |Pendente                         |
|5     |Asus                |Kali   Linux             |Debian          |N/A                              |
|6     |Asus                |Linux Ubuntu             |Ubuntu          |Pendente                         |
|7     |Asus                |Linux Xubuntu            |Ubuntu          |Pendente                         |
|8     |Asus                |Windows 10               |Windows         |Pendente                         |


## Descrição [2]

### `Telegram Desktop`

O Telegram Desktop é um aplicativo de mensagens instantâneas seguro e de código aberto disponível em várias plataformas, incluindo Linux, que oferece recursos avançados de comunicação. Conhecido por seu foco na privacidade e segurança, o Telegram oferece criptografia de ponta a ponta para as conversas, garantindo que as mensagens e arquivos compartilhados permaneçam confidenciais. Além disso, ele suporta chats em grupo, canais de divulgação, chamadas de voz e vídeo, bem como a capacidade de compartilhar arquivos de grande porte. Sua interface de usuário intuitiva e personalizável, juntamente com a capacidade de acessar o Telegram em várias plataformas, o torna uma escolha popular para comunicação pessoal e profissional, além de ser amplamente utilizado para grupos de comunicação, notícias e compartilhamento de informações.

## 1. Configurar/Instalar o `Telegram Desktop` no `Linux Ubuntu` [1]

Para configurar/instalar o `Telegram Desktop` no `Linux Ubuntu`, você pode seguir estas etapas:

1. Abra o terminal. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Certifique-se de que seu sistema esteja atualizado.

    2.1 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update -y`

    2.2 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.3 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update -y`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`


3. Você pode instalar o Telegram Desktop usando o aplicativo "Snap". Certifique-se de que você tenha o Snap instalado. Se ainda não o tiver, você pode instalá-lo com este comando: `sudo apt install snapd -y`

4. Após instalar o Snap, você pode instalar o Telegram Desktop com este comando: `sudo snap install telegram-desktop`

5. Depois de instalado, você pode iniciar o Telegram Desktop digitando o seguinte comando no Terminal: 
`telegram-desktop`

- Isso abrirá o Telegram Desktop, e você poderá escanear o código QR usando o aplicativo Telegram no seu telefone, assim como no Telegram Web.

Lembrando que a disponibilidade de aplicativos e as instruções podem ter mudado após a minha última atualização em setembro de 2021. Certifique-se de verificar se há novas opções ou métodos disponíveis caso não encontre o aplicativo mencionado


## 2. Código completo para configurar/instalar

Para instalar o `Telegram Desktop` no `Linux Ubuntu` sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o terminal. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Digite o seguinte comando e pressione `Enter`:

    ```
    sudo apt update -y
    sudo apt list --upgradable
    sudo apt full-upgrade -y
    sudo apt install snapd -y
    sudo snap install telegram-desktop
    telegram-desktop
    ```

## Referências

[1] OPENAI. ***Instalar telegram no ubuntu:*** https://chat.openai.com/c/54b1d9ab-291f-4f89-aa5a-dba1497f15e7 (texto adaptado). ChatGPT. Acessado em: 18/10/2023 13:49.

[2] OPENAI. ***Vs code: editor popular:*** https://chat.openai.com/c/b640a25d-f8e3-4922-8a3b-ed74a2657e42 (texto adaptado). ChatGPT. Acessado em: 14/11/2023 09:33.
