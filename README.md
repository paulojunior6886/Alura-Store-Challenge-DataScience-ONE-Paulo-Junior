# 📊 Projeto de Análise de Vendas – Desafio Alura Data Science

Este projeto é parte do desafio de Data Science da Alura. O objetivo principal é analisar os dados de vendas de quatro lojas diferentes para ajudar o Senhor João a decidir **qual loja vender** com base em múltiplos critérios de desempenho.

---

## 📌 Objetivo

Fornecer uma análise detalhada das lojas a partir de dados reais, considerando:

- Faturamento total de cada loja
- Categorias mais e menos vendidas
- Média das avaliações dos clientes
- Produtos mais e menos vendidos
- Custo médio do frete
- Análise geográfica das vendas
- Visualizações dos dados para insights mais claros

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Folium** (para mapas interativos opcionais)

---

## 🗃️ Dados

Os dados foram extraídos diretamente do repositório oficial da Alura:

- [`loja_1.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- [`loja_2.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- [`loja_3.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- [`loja_4.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

---

## 📈 Principais Análises Realizadas

### 1. 💰 Faturamento Total

Foi somado o valor total de vendas (`Preço`) de cada loja.  
Exemplo:
- Loja 1: R$ 1.534.509,12

### 2. 🛍️ Vendas por Categoria

As categorias com maior e menor volume de vendas foram identificadas, por exemplo:
- Mais vendida (Loja 1): **Móveis**
- Menos vendida (Loja 1): **Utilidades Domésticas**

### 3. 🌟 Média das Avaliações dos Clientes

Foi calculada a média das avaliações para cada loja, revelando a satisfação dos consumidores.

### 4. 🏆 Produtos Mais e Menos Vendidos

Identificamos os produtos com maior e menor número de vendas em cada loja.

### 5. 🚚 Custo Médio de Frete

A média de custo de frete foi calculada por loja, auxiliando na análise de despesas logísticas.

### 6. 🌍 Análise Geográfica

Utilizando latitude e longitude, foi visualizada a distribuição geográfica das vendas com:
- Gráfico de dispersão
- Mapa de calor

---

## 📊 Visualizações Criadas

- Gráficos de **barras** (vendas por produto, avaliação por loja)
  ![image](https://github.com/user-attachments/assets/d99fbe23-fdc1-4ba6-a46e-90b17bc66092)

- Gráfico **pizza** (distribuição de vendas por categoria)
  ![image](https://github.com/user-attachments/assets/9d66a68e-7b46-4c2f-9d32-c6955a9156f0)

- **Gráfico de dispersão** (análise geográfica)
  ![image](https://github.com/user-attachments/assets/fc4739ab-eeee-4ca3-9842-1e251b2e4fcf)


- **Mapa de calor** (concentração de vendas por região)
  ![image](https://github.com/user-attachments/assets/792d08fd-1b65-4956-8099-635bdb63e983)

---

## 📌 Conclusão e Recomendação

Após analisar todos os dados, considerando o **faturamento**, **avaliações dos clientes**, **custo médio de frete** e **desempenho por categoria**, conclui-se que:

🔎 **Loja 03** é a melhor opção para ser vendida, pois:
- Apresenta **menor faturamento**
- Possui **relativas avaliações de clientes**
- Tem **alto custo logístico**
- Não se destaca em categorias estratégicas de produto

> Essa recomendação foi baseada em dados objetivos e visualizações criadas ao longo da análise.

---

## 🛠️ Como Executar o Projeto

1. Clone o repositório ou abra o notebook no Google Colab.
2. Instale as bibliotecas necessárias (caso não estejam disponíveis):
```bash
pip install pandas matplotlib seaborn folium

✍️ Autor
Desenvolvido por Paulo Junior.
Projeto proposto pela One Next Education - Oracle + Alura.
