# Explorando IA Generativa em um Pipeline de ETL com Python

## Descrição do desafio

Construir um pipeline ETL (Extração, Transformação e Carregamento), demonstrando a relação entre dados, Inteligência Artificial (IA) e APIs. 

**Extração:** Começa com uma planilha simples, de onde extrairemos os IDs dos usuários. Depois, usaremos esses IDs para acessar a API da 'Santander Dev Week 2023' e obter dados mais detalhados, um processo que evidencia a versatilidade na coleta de informações em Ciência de Dados. 

**Transformação:** Adentrar o universo da IA com o GPT-4 da OpenAI, transformando esses dados em mensagens personalizadas de marketing. Ver como a IA pode ser empregada de maneira inovadora e prática! 

**Carregamento:** Finalizaremos o processo enviando essas mensagens de volta para a API da 'Santander Dev Week 2023'. Este passo ilustra como dados transformados são reintegrados em sistemas, completando o ciclo de um pipeline ETL.

## O que foi feito

### Etapa 1 - Preparação
- Criação dos usuários na API [Santander Dev Week 2023](https://sdw-2023-prd.up.railway.app/swagger-ui/index.html) IDs ```5148``` ```5149``` ```5150```
- Criação de um arquivo CSV que irá servir de base para a etapa de extração

### Etapa 2 - Extração
- Estrair os IDs do arquivo CSV
- Obter os dados de cada ID usando a API da Santander Dev Week 2023

### Etapa 3 - Transformação
- Instalação da biblioteca da OpenIA 
- Obtendo a API Key da OpenIA
- Implementar a integração com o ChatGPT usando o modelo GPT-3.5 Turbo

### Etapa 4 - Carregar
- Atualização dos usuários na API da Santander Dev Week 2023 com os dados transformados

### Google Colab
https://colab.research.google.com/drive/1TRhUzIyoqPW-JjVWsLqSjYCUAFdgKZAP#scrollTo=dCz3pmVXD2d8&uniqifier=3

## Conhecimento e habilidades
 ![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white)
 ![ChatGPT](https://img.shields.io/badge/chatGPT-000?style=for-the-badge&logo=openai)


## Para mais informações
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=E94D5F)](mailto:maikonepereira@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=30A3DC)](https://www.linkedin.com/in/maikonpereira/)
