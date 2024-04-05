# Python-AI-Artificial-Intelligence-and-Predictions
Python AI: Artificial Intelligence and Predictions

Este projeto é uma aplicação de Inteligência Artificial (IA) para prever o score de crédito dos clientes de um banco. O objetivo é analisar os dados dos clientes e criar um modelo que possa ler as informações do cliente e prever automaticamente o score de crédito dele: Ruim, Ok, Bom.

Estrutura do Projeto
O projeto é dividido em várias partes, cada uma com um propósito específico:

Importação e Visualização dos Dados: A primeira parte do projeto envolve a importação dos dados dos clientes de um arquivo CSV e a visualização inicial dos dados para entender a estrutura e os tipos de dados presentes.
Pré-processamento dos Dados: Nesta etapa, os dados são pré-processados para garantir que estejam no formato adequado para o treinamento do modelo. Isso inclui a codificação de variáveis categóricas e a verificação de valores ausentes ou inconsistências nos dados.
Divisão dos Dados: Os dados são divididos em conjuntos de treinamento e teste. O conjunto de treinamento é usado para treinar o modelo, enquanto o conjunto de teste é usado para avaliar o desempenho do modelo.
Treinamento do Modelo: Aqui, dois modelos de aprendizado de máquina são treinados nos dados de treinamento: uma Árvore de Decisão RandomForest e um K-Nearest Neighbors (KNN).
Avaliação do Modelo: Após o treinamento, os modelos são avaliados no conjunto de teste para determinar sua precisão. A acurácia do modelo é calculada comparando as previsões do modelo com os valores reais.
Conclusão: A última parte do projeto resume os resultados obtidos e discute as implicações desses resultados para a previsão do score de crédito dos clientes.
Como Executar
Para executar este projeto, siga os passos abaixo:

Clone o repositório para sua máquina local.
Instale as dependências necessárias usando o comando pip install -r requirements.txt.
Execute o arquivo principal do projeto (geralmente main.py ou similar) usando um interpretador Python.
Dependências
Este projeto depende das seguintes bibliotecas Python:

pandas: para manipulação e análise de dados.
sklearn: para treinamento e avaliação de modelos de aprendizado de máquina.
matplotlib e seaborn: para visualização de dados.
Dados
Os dados utilizados neste projeto são fictícios e representam informações sobre clientes de um banco, incluindo idade, profissão, salário anual, número de contas, entre outros. O objetivo é prever o score de crédito de cada cliente com base nessas informações.

Contribuição
Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.
