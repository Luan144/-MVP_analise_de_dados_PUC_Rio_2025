
# MVP_analise_de_dados_PUC_Rio_2025

### Trabalho de conclusão da sprint Análise de Dados e Boas Práticas da especialização em Ciência de Dados e Analytics da Puc-Rio.

#### O objetivo desse trabalho é entender o impacto de alguns fatores como engenharia e seleção de variáveis e ajuste de hiperparâmetros impactam no desempenho final de um modelo preditivo.

#### O conjunto de dados utilizado está disponível neste link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Catálogo de Dados

- **CustomerID**: ID único de cada cliente.  
  - `str`; apenas valores únicos

- **Gender**: Gênero biológico.  
  - `str`; Binário: `Male`, `Female`

- **SeniorCitizen**: Idoso.  
  - `int`; Binário: `0`, `1`

- **Partner**: Possui parceiro.  
  - `str`; Binário: `No`, `Yes`

- **Dependants**: Possui dependentes.  
  - `str`; Binária: `No`, `Yes`

- **tenure**: Duração da relação com o serviço, em meses.  
  - `int`; Numérica: de `0` a `72`

- **PhoneService**: Possui serviço de telefonia.  
  - `str`; Binária: `No`, `Yes`

- **MultipleLines**: Possui múltiplas linhas de telefonia.  
  - `str`; Categórica: `No`, `Yes`, `No phone service`

- **InternetService**: Possui serviço de internet.  
  - `str`; Binária: `No`, `Yes`

- **OnlineSecurity**: Possui serviço de segurança online.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **OnlineBackup**: Possui serviço de backup online.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **DeviceProtection**: Possui serviço de proteção de dispositivo.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **TechSupport**: Possui serviço de suporte técnico.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **StreamingTV**: Possui serviço de TV por streaming.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **StreamingMovies**: Possui serviço de filmes por streaming.  
  - `str`; Categórica: `No`, `Yes`, `No internet service`

- **Contract**: Tipo de contrato.  
  - `str`; Categórica: `Month-to-month`, `One year`, `Two year`

- **PaperlessBilling**: Optou por modalidade de cobrança eletrônica.  
  - `str`; Binária: `No`, `Yes`

- **PaymentMethod**: Método de pagamento utilizado.  
  - `str`; Categórica: `Mailed check`, `Electronic check`, `Bank transfer (automatic)`, `Credit card (automatic)`

- **MonthlyCharges**: Cobranças mensais.  
  - `float`; Numérica: de `18,25` a `118,75`

- **TotalCharges**: Cobranças totais.  
  - `float`; Numérica: de `18,80` a `8684,80`

- **Churn**: Cancelou o contrato.  
  - **Variável Alvo**; Binária: `No`, `Yes`
