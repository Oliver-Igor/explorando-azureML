# Processo de Criação e Implantação de Modelo no Azure Machine Learning
Este readme fornece um guia passo a passo sobre como criar e implantar um modelo de previsão usando o Azure Machine Learning.

## Pré-requisitos
- Conta no Azure
- Azure Machine Learning Studio configurado

  

### Passo 1: Configuração do Ambiente
Certifique-se de que você está conectado ao seu ambiente do Azure Machine Learning Studio.

### Passo 2: Preparação do Conjunto de Dados
Utilize dados históricos de aluguel de bicicletas e siga as instruções para criar um conjunto de dados tabular no Azure Machine Learning Studio.

### Passo 3: Configuração do Trabalho de ML Automatizado
No Azure Machine Learning Studio, vá para a página Automated ML (em Authoring) e crie um novo trabalho de ML automatizado conforme as configurações fornecidas no texto original.

### Passo 4: Avaliação do Melhor Modelo
Aguarde a conclusão do trabalho automatizado. Na guia Visão geral do trabalho, observe o melhor resumo do modelo e verifique as métricas na guia Métricas.

### Passo 5: Implantação do Modelo
Na guia Modelo do melhor modelo treinado, selecione Implantar e configure o serviço web conforme as instruções originais.

### Passo 6: Teste do Serviço Implante
No Azure Machine Learning, acesse Endpoints e abra o ponto final em tempo real de previsão de alugueres. Na guia Teste, substitua o modelo JSON pelos dados de entrada fornecidos em [endpoints.json](https://github.com/Oliver-Igor/explorando-azureML/blob/main/endpoints.json) e clique em Testar.

### Passo 7: Limpeza
Exclua o ponto de extremidade de previsão de aluguel no Azure Machine Learning Studio para evitar custos desnecessários. Se necessário, exclua o grupo de recursos no portal Azure.

### Para o passo a passo detalhado das configurações seguir as recomendações dos seguintes links:
- [Explore Azure AI Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html#try-out-text-moderation-in-the-content-safety-studio)
- [Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)
