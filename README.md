# 📊 Projeto de Análise de Dados em E-commerce

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados de um e-commerce utilizando SQL e Python. A análise foi desenvolvida com foco na identificação de padrões de vendas, comportamento dos clientes, faturamento e tendências ao longo do tempo.

Durante o projeto, foram aplicadas técnicas de manipulação, consulta e visualização de dados para gerar insights relevantes para o negócio.

---

# 🚀 Tecnologias Utilizadas

- Python
- SQL
- SQLite
- Pandas
- Matplotlib
- Jupyter Notebook

---

# 🎯 Objetivos da Análise

- Analisar o faturamento da plataforma
- Identificar os estados com maior volume de vendas
- Calcular ticket médio
- Identificar categorias mais relevantes
- Analisar a evolução do faturamento ao longo do tempo
- Explorar padrões de comportamento dos consumidores

---

# 📈 Principais Análises Realizadas

## Faturamento Total
Análise do volume financeiro movimentado pela plataforma.

## Estados com Mais Vendas
Identificação das regiões com maior quantidade de pedidos.

## Ticket Médio por Estado
Análise do valor médio gasto por compra em diferentes estados.

## Categorias com Maior Faturamento
Identificação das categorias mais relevantes para a receita do e-commerce.

## Evolução do Faturamento Mensal
Análise temporal do crescimento e comportamento das vendas ao longo do tempo.

## Distribuição dos Preços dos Produtos
Análise da concentração de produtos em diferentes faixas de preço.

---

# 📊 Visualizações do Projeto

## Evolução do Faturamento Mensal

![Faturamento Mensal](images/faturamento_mensal.png)

---

## Participação das Categorias no Faturamento 

![Categorias](images/categorias_faturamento_pizza.png)

---

## Ticket Médio por Estado

![Ticket Médio](images/ticket_medio_estado.png)

---

## Distribuição dos Preços dos Produtos

![Histograma](images/histograma_precos.png)

## Categorias com alto faturamento mas avaliação baixa

![Notas das Categorias](images/categorias_nota.png)

## Pedidos por dia da semana e hora do dia

![Tempo dos pedidos](images/pedidos_tempo.png)

## Frete vs distância (quem paga mais?)

![Frete por estado](images/frete_estado.png)

---

# 💡 Insights Obtidos

- O faturamento da plataforma apresentou crescimento ao longo do período analisado.
- Algumas categorias concentram grande parte da receita total do e-commerce.
- Estados com maior volume de pedidos não necessariamente possuem maior ticket médio.
- A maior parte dos produtos está concentrada em faixas de preço mais acessíveis.
- O comportamento das vendas apresenta oscilações ao longo do tempo, indicando possíveis sazonalidades.

---

# 🗂️ Estrutura do Projeto

```plaintext
ecommerce-analysis/
│
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   └── ecommerce.db
│
├── images/
│
├── notebooks/
│   └── analysis.ipynb
│
├── .gitattributes
│
└── README.md
```

---

# 📂 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos no Kaggle, através do dataset brasileiro de e-commerce Olist.

Dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

O conjunto de dados contém informações sobre pedidos, clientes, produtos, pagamentos e avaliações de um e-commerce brasileiro.

---

# ⚙️ Como Executar o Projeto

## 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

---

## 2. Instalar as dependências

```bash
pip install -r requirements.txt
```

---

## 3. Abrir o Jupyter Notebook

```bash
jupyter notebook
```

---

## 4. Executar o arquivo

Abra:

```plaintext
analysis.ipynb
```

---

# ✅ Conclusão

O projeto permitiu aplicar técnicas de análise de dados utilizando SQL e Python em um cenário real de e-commerce. As análises desenvolvidas possibilitaram identificar padrões importantes de vendas, faturamento e comportamento dos clientes, além de contribuir para o desenvolvimento de habilidades práticas em análise de dados.