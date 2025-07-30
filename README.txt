- IA Generativa DALL-E da OpenAI - Geração de imagens

Neste projeto, será criado uma IA generativa DALL-E da OpenAi para gerar imagens.
Será criado:

1. IA Generativa DALL-E da OpenAI
2. SDK Python da OpenAI o Custom Vision

- Como usar: Passo a passo

1. Acesse o Portal do Azure AI Foundry
   [https://ai.azure.com]

2. Escolhendo um modelo para iniciar um projeto
   Na página inicial, na seção Explorar modelos e recursos , procure o "dall-e-3"
   Selecione o modelo e marque "Usar o modelo"
   Preencha: Recurso do Azure AI Foundry, Assinatura, Grupo de recursos, região
   Clique em "Criar" 
   
3. Testando o modelo no playground
   Selecione "Playgrounds" e depois "Imagens playground
   Verifique se a implantação do modelo DALL-E está selecionada. Na caixa próxima à parte inferior da página, insira um prompt como "Create an image of an robot eating spaghettie" selecione "Gerar" 
   Revise a imagem resultante no playground
   Insira um prompt de acompanhamento, como "Show the robot in a restaurante revise a imagem resultante.
   Selecione o botão </> Visualizar Código e certifique-se de estar na aba de autenticação de ID de Entrada. Copie o Ponto de extremidade OpenAI, Versao da API OpenAI, Nome da implantação

4. Criando aplicativo cliente
   Abra o Portal do Azure
   Abra o Cloud Shell e selecione PowerShell -> versão clássica
   Digite: "rm -r mslearn-ai-vision -f
            git clone https://github.com/MicrosoftLearning/mslearn-ai-vision"
   Clone o repositório: "cd mslearn-ai-vision/Labfiles/dalle-client/python"
   Instale as bibliotecas: "python -m venv labenv
                            ./labenv/bin/Activate.ps1
                            pip install -r requirements.txt azure-identity openai requests"
   Digite: "code .env"para abrir o editor e acrescente o ponto de extremidade, modelo e versão de API. Essas informacõeses estão no Foundry. Salve
  
5. Escrevendo o código para conectar ao modelo:
   Digite: "code dalle-client.py" para abrir o código
   Complemente o código e o execute
   Baixe os arquivos gerados.

- Tecnologias Usadas

 1. Microsoft Azure - (https://azure.microsoft.com/)
 2. Azure AI Foundry - (https://ai.azure.com/)
 3. ARM Templates - (https://learn.microsoft.com/azure/azure-resource-manager/templates/overview)
 4. Markdown para documentação

- Autor
  Dannuza Martins Cardoso Silva
 
 


