# Microsoft Speech Studio

O serviço de **Fala** de **IA do Azure** transcreve fala em texto e texto em fala audível.


## Criar um recurso de Fala de IA do Azure

Você pode usar o serviço de Fala criando um recurso de **Fal**a ou um recurso **de serviços de IA do Azure**.

Criaremos um recurso de Fala de IA.

1.Em outra guia do navegador, abra o Azure AI Speech Studio, entrando com sua conta da Microsoft.

2. Selecione **Configurações** e **Criar um recurso**. Configure-o com as seguintes configurações:
* **Nome do novo recurso**: insira um nome exclusivo.
* **Assinatura**: sua assinatura do Azure.
* **Região**: selecione uma região com suporte.
* **Nível de preços**: FO gratuito (se disponível, caso contrário, selecione Standard S0).
* **Grupo de recursos**: selecione ou crie um grupo de recursos com um nome exclusivo.

3. Selecione **Criar recurso**. Aguarde até que o recurso tenha sido criado e selecione **Usar recurso**. A página Introdução à Fala é exibida.

## Explorar a conversão de voz em texto no Speech Studio

1. Selecione [ https://aka.ms/mslearn-speech-files ](https://aka.ms/mslearn-speech-files) para baixar **speech.zip**. Abra a pasta.

2. Na página Introdução à Fala, em Fala para texto, localize Conversão de fala em texto em tempo real. Selecione **Experimentar conversão de voz em texto em tempo real.**

<img width="608" alt="image" src="https://github.com/jacquelinepalumbo/Speech_Studio/assets/119548193/03dd7552-525f-4f74-86a4-ad7072186a32">


3. Em _Escolher arquivos de áudio_, selecione **Procurar arquivos** e navegue até a pasta onde você salvou o arquivo. Selecione **WhatAICanDo.m4a** e, em seguida, **Abrir**.

<img width="510" alt="image" src="https://github.com/jacquelinepalumbo/Speech_Studio/assets/119548193/6d751913-c9d0-48b6-bfeb-3e65dac92edc">


4. O serviço de Fala transcreve e exibe o texto em tempo real. Se você tiver áudio no computador, poderá ouvir a gravação enquanto o texto está sendo transcrito.

5. Revise a saída, que deve ter reconhecido e transcrito com sucesso o áudio em texto.



Neste exercício, você criou um recurso de Fala de IA no Speech Studio. Em seguida, você usou o serviço de conversão de fala em tempo real para texto para transcrever uma gravação de áudio. Você pôde ver a transcrição de texto sendo gerada à medida que o arquivo de áudio era reproduzido.
