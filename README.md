📊 Análise de Dados: Salários em Data Science
Este projeto foi desenvolvido durante uma aula prática de Python para análise de dados. O objetivo principal foi realizar o Processamento de Dados (ETL) e a Análise Exploratória de um dataset contendo informações salariais do setor de tecnologia ao redor do mundo.

🛠️ Tecnologias Utilizadas
Python: Linguagem principal.

Pandas: Manipulação e tratamento de dados.

NumPy: Operações matemáticas e tratamento de valores nulos.

Matplotlib & Seaborn: Criação de gráficos estáticos e boxplots.

Plotly Express: Visualizações interativas (Gráficos de barra e pizza).

📖 Etapas do Projeto
1. Limpeza e Tradução de Dados
O dataset original possuía nomes de colunas e categorias em inglês. Foram realizadas as seguintes transformações:

Renomeação de Colunas: Tradução de termos como work_year para ano, experience_level para senioridade, etc.

Mapeamento de Categorias: Conversão de siglas (Ex: 'SE' ➔ 'Senior', 'FT' ➔ 'Tempo Integral', 'M' ➔ 'Médio').

Tipagem: Conversão de tipos de dados para garantir cálculos precisos.

2. Tratamento de Valores Ausentes (NaN)
Foram exploradas diferentes técnicas para lidar com dados faltantes, tais como:

Preenchimento com a Média e Mediana.

Métodos de propagação (ffill e bfill).

Substituição por valores genéricos ("Não informado").

Remoção de linhas nulas para a análise final.

3. Análise Exploratória (EDA)
Geramos diversos insights visuais para entender o mercado:

Distribuição Salarial: Histograma para verificar a frequência de salários em USD.

Salário por Senioridade: Gráficos de barras ordenados pela média salarial.

Outliers: Uso de Boxplots para identificar a dispersão dos salários e valores discrepantes entre os níveis de experiência.

Modalidade de Trabalho: Gráfico de rosca (donut chart) mostrando a proporção entre trabalho Presencial, Híbrido e Remoto.
