# SoundChatGPT

Este projeto utiliza JavaScript no ambiente do Google Colab para realizar a gravação de áudio por um determinado período de tempo. A transcrição do áudio é realizada por um modelo de reconhecimento de fala, e em seguida, a transcrição é usada como entrada para o modelo ChatGPT para gerar uma resposta em linguagem natural. O resultado final é convertido em áudio e reproduzido.
Requisitos e Configuração

    O código é projetado para ser executado no ambiente do Google Colab.
    É necessário um navegador compatível com a API navigator.mediaDevices.getUserMedia para gravação de áudio.
    Certifique-se de instalar as bibliotecas necessárias usando os comandos !pip install.

Como Usar

    Gravação de Áudio:
        O trecho JavaScript permite a gravação de áudio por um período especificado. Execute a função record para iniciar a gravação.

    Transcrição de Áudio:
        A transcrição do áudio gravado é realizada usando o modelo de reconhecimento de fala do Whisper.

    Resposta em ChatGPT:
        O texto transcrito é usado como entrada para o modelo ChatGPT, que gera uma resposta em linguagem natural.

    Conversão para Áudio e Reprodução:
        A resposta gerada pelo ChatGPT é convertida em áudio usando a biblioteca gTTS (Google Text-to-Speech) e, em seguida, reproduzida.
