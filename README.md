# dioMachineLearningChalenge

# Modelo de Previsão de Vendas de Bicicletas no Azure

Este repositório contém um projeto de Machine Learning Automatizado no Azure focado na previsão de vendas de bicicletas. Utilizando um conjunto de dados fictício, o projeto visa desenvolver um modelo que preveja as vendas de bicicletas, disponibilizando este modelo por meio de endpoints configurados.

## Experiência de Desenvolvimento

Após me inscrever na plataforma Azure, criei um recurso de Machine Learning e configurei meu espaço de trabalho. Compilei todos os dados necessários para a automatização das tarefas seguindo o guia disponibilizado pela própria plataforma Azure. Conforme a documentação, implementei o algoritmo que forneceu as saídas esperadas para a previsão de vendas. Realizei a validação das métricas e gerei os gráficos necessários, como o gráfico residual e o de previsão real. Por fim, testei o modelo utilizando o endpoint com dados fictícios, conforme documentado no arquivo `.json` anexado, obtendo respostas satisfatórias.

## Fonte de Dados

Os dados utilizados são fictícios, criados para simular vendas de bicicletas ao longo do tempo, incluindo variáveis como data, temperatura, precipitação, feriados, entre outros. Os dados estão disponíveis na documentação oficial "Explore Automated Machine Learning in Azure Machine Learning".

## Modelo de Previsão

Utilizei técnicas de regressão e séries temporais no Azure Machine Learning para construir o modelo de previsão de vendas de bicicletas. O processo de treinamento do modelo foi automatizado, com seleção e ajuste de algoritmos e hiperparâmetros para otimizar o desempenho.

## Pontos de Extremidade Configurados

Os endpoints foram configurados no Azure após o treinamento do modelo, permitindo o acesso via API para previsões em tempo real.

## Como Utilizar

- **Preparação dos Dados:** Garanta que os dados de entrada estejam corretamente formatados.
- **Acesso aos Pontos de Extremidade:** Utilize as URLs fornecidas para enviar solicitações de previsão.
- **Processamento dos Resultados:** Processe as previsões recebidas conforme necessário.

## Recursos Adicionais

- **Documentação do Azure Machine Learning:** Consulte a [documentação oficial](https://docs.microsoft.com/azure/machine-learning/) para mais detalhes sobre o uso da plataforma.
- **Exemplos de Código:** Inclusos neste repositório para demonstrar como interagir com os endpoints.
- **Contribuições:** São bem-vindas para melhorar o projeto.

## Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

Este projeto foi desenvolvido como parte da certificação AI-900 da Digital Innovation One (DIO) em parceria com a Microsoft.
