# Alura_store

## 🛒 Análise de Desempenho de Lojas - Alura Store
Este projeto tem como objetivo analisar os dados de vendas de quatro lojas do e-commerce fictício Alura Store, com o propósito de identificar qual loja tem o menor desempenho e, com base nisso, recomendar ao Sr. João (dono da rede) qual loja ele deve vender para obter capital e investir em um novo negócio.

## 📌 Objetivo
Realizar uma análise exploratória de dados utilizando métricas estratégicas para avaliar o desempenho de cada loja e apresentar:

## 📊 Faturamento total

⭐ Média de avaliação dos clientes

🚚 Custo médio do frete

🛍️ Categoria de produto mais popular

🔼 Produto mais vendido

🔽 Produto menos vendido

Com base nessas informações, gerar gráficos comparativos e um relatório com a recomendação final da loja a ser vendida.

## 🗂️ Estrutura dos Dados
Os dados estão divididos em quatro arquivos CSV — um para cada loja:

loja_1.csv

loja_2.csv

loja_3.csv

loja_4.csv

Cada arquivo contém as seguintes colunas:

Produto: nome do produto vendido

Categoria do Produto: categoria do item

Preço: valor do item

Frete: custo de envio

Data da Compra: data da venda

Vendedor: nome do vendedor

Local da compra: localização

Avaliação da compra: nota dada pelo cliente (1 a 5)

Tipo de pagamento: forma de pagamento

Quantidade de parcelas: número de parcelas

lat, lon: coordenadas geográficas

## 🛠️ Tecnologias Utilizadas
Python 3.10+

Pandas – manipulação de dados

Matplotlib – criação de gráficos

(Opcional) Jupyter Notebook ou Google Colab – para execução interativa

## 📈 Métricas Analisadas
Durante a análise, foram geradas as seguintes métricas por loja:

Faturamento Total – soma dos valores de venda (Preço)

Média de Avaliação – média da coluna Avaliação da compra

Custo Médio de Frete – média da coluna Frete

Categoria mais popular – categoria com maior número de vendas

Produto mais vendido – produto com maior contagem de vendas

Produto menos vendido – produto com menor contagem de vendas

## 📊 Gráficos Criados
Três gráficos foram gerados para visualização comparativa entre as lojas:

Gráfico de Barras – Faturamento total por loja

Gráfico de Pizza – Participação percentual da média de avaliação

Gráfico de Barras Horizontais – Custo médio do frete por loja

## 🚀 Como Executar o Projeto
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/alura-store-analise.git
cd alura-store-analise
Instale as dependências (opcional com virtualenv):

bash
Copiar
Editar
pip install pandas matplotlib
Execute o script analise_lojas.py ou abra o notebook analise_lojas.ipynb.

## 🔍 Resultados da Análise (Resumo)
A Loja 4 apresentou o menor faturamento e uma média de avaliação inferior às demais.

Apesar de ter o frete mais barato, a Loja 4 não compensou em vendas ou avaliação.

Todas as lojas têm "móveis" como categoria mais vendida, o que mostra padrão de consumo.

Produtos com menor rotatividade (como guitarra na Loja 4) indicam menor apelo comercial.

## ✅ Recomendação Final
Recomendamos que o Sr. João venda a Loja 4, pois ela demonstrou o menor desempenho geral entre as quatro unidades, sendo a menos lucrativa e com menor avaliação média dos clientes.

## 📄 Licença
Este projeto é livre para uso educacional. Sinta-se à vontade para modificar e reutilizar.

## 🤝 Agradecimentos
Projeto proposto como desafio de Análise de Dados pela Alura.

