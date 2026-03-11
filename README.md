# 📊 Análise de Dados: Salários em Data Science

Este projeto foi desenvolvido para explorar, limpar e visualizar dados sobre o mercado de trabalho em Ciência de Dados. O foco principal foi transformar dados brutos em insights compreensíveis, utilizando técnicas de tratamento de dados e visualizações estatísticas.

## 🛠️ Tecnologias e Bibliotecas
* **Python**: Linguagem base.
* **Pandas**: Manipulação de DataFrames e limpeza de dados.
* **NumPy**: Tratamento de valores nulos (`NaN`).
* **Matplotlib & Seaborn**: Gráficos estáticos e análise de distribuição.
* **Plotly Express**: Gráficos interativos e dinâmicos.

---

## 📖 O que foi feito no projeto?

### 1. Limpeza e Tradução (ETL)
Os dados originais estavam em inglês e continham siglas técnicas. O projeto realizou:
* **Renomeação de colunas**: De `work_year` para `ano`, `salary_in_usd` para `usd`, etc.
* **Mapeamento de categorias**: Tradução de níveis de experiência (Ex: `SE` → `Senior`) e tipos de contrato (Ex: `FT` → `Tempo Integral`).
* **Tratamento de Nulos**: Demonstração de técnicas como preenchimento por média, mediana, `ffill`, `bfill` e remoção de dados ausentes.

### 2. Análise Exploratória (EDA)
Foram geradas visualizações para responder perguntas de negócio:
* **Distribuição Salarial**: Qual a frequência de faixas salariais em dólar?
* **Senioridade vs. Salário**: Qual a média salarial para cada nível de experiência?
* **Modalidade de Trabalho**: Qual a proporção de vagas remotas, híbridas e presenciais?



### 3. Visualizações Estatísticas
O código utiliza **Boxplots** para identificar a dispersão dos salários e a presença de *outliers* (valores muito acima ou abaixo da média) em cada categoria de senioridade, além de **Histogramas** para entender a densidade dos dados.

---

## 📈 Resultados e Insights
* O projeto identifica as tendências salariais globais.
* Demonstra como o nível de senioridade impacta diretamente na remuneração em USD.
* Proporciona um dataset limpo (`dados-imersao-final.csv`) pronto para análises futuras ou dashboards.
Modalidade de Trabalho: Gráfico de rosca (donut chart) mostrando a proporção entre trabalho Presencial, Híbrido e Remoto.
