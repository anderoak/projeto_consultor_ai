# projeto_consultor_ai

# Consultor AI de Documentos PDF

Este projeto contém um notebook que demonstra como combinar a API Gemini com embeddings para criar um chatbot capaz de responder perguntas sobre o conteúdo de documentos e buscar informações relevantes em uma base de documentos PDF.

Copyright © 2024 [Anderson Carvalho] - GNU GENERAL PUBLIC LICENSE

# Instruções para Utilização

- Adicione a sua chave de API do Google AI no Secrets, na barra lateral esquerda do Colab, definindo com o nome: GEMINI_API_KEY.
- Crie uma pasta chamada PDF no ambiente Colab. Você pode fazer isso clicando no ícone arquivos na lateral esquerda do Colab, depois clicando com o botão direito no espaço em branco e selecionando "Nova pasta".
- Depois faça o upload dos seus arquivos PDF e arraste-os para dentro da pasta PDF que criou. Leve em conta que a API do Gemini pode limitar de quantidade de dados carregados dos PDF se você está usando a versão gratuita da API, então use apenas um ou dois arquivos pequenos (deixei 2 arquivos que usei para testar aqui no repositório, na pasta "PDFs para teste").
- Garanta que os arquivos na pasta sejam realmente PDFs. Atente que esse projeto assume que os PDFs contêm texto extraível, portanto não irá funcionar com PDFs que são apenas imagens digitalizadas, pois exigiria técnicas de OCR (Optical Character Recognition) para extrair o texto.
- Execute o código célula por célula.
- Interaja com o chatbot fazendo perguntas sobre o conteúdo dos PDFs.
- Digite "sair" para encerrar o chat.

Observação: Este é um exemplo básico genérico, mas que talvez possa se aprimorado adicionando mais funcionalidades, como especialização por área e uma interface web.
