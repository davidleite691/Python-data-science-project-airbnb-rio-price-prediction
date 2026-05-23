# 🏠 Airbnb Rio - Previsão Inteligente de Preços de Imóveis

Projeto de Ciência de Dados desenvolvido para prever o valor ideal da diária de imóveis anunciados no Airbnb na cidade do Rio de Janeiro.

O objetivo é fornecer uma ferramenta acessível para proprietários e locatários, permitindo estimar preços justos com base nas características do imóvel e nas condições do mercado.

## 🚀 Demonstração

A aplicação foi disponibilizada através do Streamlit, permitindo que qualquer usuário informe as características de um imóvel e obtenha uma previsão de preço em tempo real.

🔗 Para acessar a aplicação através do Streamlit:
pip install -r requirements.txt
execute: streamlit run c:\caminho\Deploy_projeto_airbnb.py.


# 📌 Problema de Negócio

No Airbnb, anfitriões precisam definir o valor da diária de seus imóveis considerando diversos fatores, como:

- Localização
- Quantidade de quartos
- Capacidade de hóspedes
- Comodidades disponíveis
- Regras de hospedagem
- Época do ano

Definir um preço inadequado pode resultar em baixa ocupação ou perda de receita.

Este projeto busca resolver esse problema utilizando Machine Learning para estimar automaticamente o valor ideal da diária.

---

# 🎯 Objetivos

## Para proprietários

Permitir que anfitriões descubram quanto cobrar por seu imóvel com base nas características informadas.

## Para hóspedes

Auxiliar na identificação de imóveis com preços atrativos ao comparar o valor anunciado com o preço estimado pelo modelo.

---

# 📊 Base de Dados

Os dados utilizados foram obtidos através do Kaggle:

📂 Dataset:
https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

Notebook de referência:
https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb

### Informações sobre os dados

- Dados referentes ao Airbnb Rio de Janeiro
- Período: Abril/2018 até Maio/2020
- Exceção: Junho/2018 não possui base disponível
- Valores em Real (R$)
- Informações sobre imóveis, localização, acomodações e preços

---

# 🔬 Metodologia

O projeto seguiu as principais etapas do ciclo de vida de um projeto de Ciência de Dados:

## 1. Entendimento do Problema

Definição do objetivo de negócio e compreensão das necessidades dos usuários da plataforma.

## 2. Entendimento dos Dados

Análise das variáveis disponíveis e identificação de possíveis fatores que influenciam o preço dos imóveis.

## 3. Coleta dos Dados

Importação e consolidação dos datasets mensais disponibilizados.

## 4. Limpeza e Tratamento

- Remoção de valores inconsistentes
- Tratamento de valores ausentes
- Padronização de variáveis
- Conversão de tipos de dados

## 5. Análise Exploratória (EDA)

Investigação dos dados para identificar:

- Distribuições
- Correlações
- Outliers
- Influência de variáveis sobre o preço

## 6. Engenharia de Atributos

Criação e transformação de variáveis para melhorar o desempenho dos modelos.

## 7. Modelagem

Treinamento e comparação de algoritmos de Machine Learning para regressão.

Exemplos:

- Linear Regression
- Random Forest Regressor
- Extra Trees Regressor
- XGBoost (se utilizado)

## 8. Avaliação dos Resultados

Comparação dos modelos através de métricas como:

- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

## 9. Deploy

Construção de uma aplicação web utilizando Streamlit para disponibilizar o modelo aos usuários finais.

---

# 💡 Hipóteses Iniciais

Durante a fase exploratória foram levantadas algumas hipóteses:

### Sazonalidade

Meses de férias e alta temporada, especialmente dezembro, tendem a apresentar diárias mais elevadas.

### Localização

A região do imóvel possui forte influência no valor da diária devido a fatores como:

- Segurança
- Proximidade de praias
- Pontos turísticos
- Infraestrutura

### Comodidades

Itens como:

- Ar-condicionado
- Piscina
- Wi-Fi
- Estacionamento

podem aumentar significativamente o valor cobrado.

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Streamlit
- Joblib

---

# 📈 Resultados

O modelo desenvolvido foi capaz de identificar padrões relevantes nos preços dos imóveis e fornecer previsões consistentes com base nas características informadas pelos usuários.

Além disso, a aplicação web permite realizar previsões de forma simples e intuitiva sem necessidade de conhecimento técnico.

---

# ▶️ Como Executar o Projeto
Execute o código do arquivo Solução Airbnb  Rio.ipynb para gerar o arquivo modelo.joblib (Arquivo que contém o modelo treinado) (como o 
github não permite upload de arquivos acima de 100 Mb então não consegui fazer o upload desse arquivo). Depois execute o deploy

---

# 👨‍💻 Autor

Desenvolvido por **David Luís Leite de Oliveira**.

📧 davidluisleite22@gmail.com  
🔗 www.linkedin.com/in/david-luís-leite

---

# 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de aprendizado em Ciência de Dados e Machine Learning.
