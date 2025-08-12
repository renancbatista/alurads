📊 Análise de Desempenho das Lojas AluraStore

Este repositório contém uma análise de dados sobre o desempenho de diferentes lojas da AluraStore, com o objetivo de apoiar a decisão de qual loja deve ser vendida.

O projeto inclui:
✅ Preparação e limpeza de dados
✅ Criação de visualizações interativas e estáticas
✅ Relatório final com insights e recomendações

📂 Conteúdo do Repositório
📓 AluraStore.ipynb
Contém todo o código-fonte da análise, incluindo:

📥 Carregamento e combinação dos dados de vendas das 4 lojas

📊 Gráficos de coluna, pizza e linha para visualizar faturamento, categorias e avaliações ao longo do tempo

🗺️ Gráfico de dispersão para análise geográfica das vendas

📈 Análise de desempenho por local de compra (faturamento, avaliação e frete médio)

🏷️ Ranking dos produtos mais e menos vendidos por categoria

📝 Relatório final com a conclusão e a recomendação sobre qual loja vender

🖼️ Imagens geradas:

faturamento_por_local_coluna.png → 📊 Faturamento total por local

distribuicao_categorias_pizza.png → 🥧 Distribuição das categorias de produtos

avaliacao_media_linha.png → 📈 Evolução da avaliação média ao longo do tempo

vendas_geograficas_dispersao.png → 🌎 Distribuição geográfica das vendas

⚙️ Como Executar a Análise

1️⃣ Clone o repositório

git clone https://github.com/seu-usuario/AluraStore-Analysis.git

2️⃣ Instale as dependências
Certifique-se de ter o Python instalado. As bibliotecas necessárias são:

pip install pandas matplotlib


3️⃣ Abra o Jupyter Notebook

jupyter notebook

4️⃣ Execute as células
No notebook, rode todas as células sequencialmente. Ele irá carregar os dados, realizar a análise, gerar os gráficos e exibir o relatório final.

📈 Principais Conclusões
📌 Faturamento:
São Paulo (SP) lidera, seguido de Rio de Janeiro (RJ) e Minas Gerais (MG).

📌 Categorias mais vendidas:
Móveis, eletrônicos e eletrodomésticos.

📌 Avaliação dos clientes:
Variável por estado, com alguns apresentando médias mais altas que outros.

📌 Distribuição geográfica:
Maior concentração de vendas nas regiões Sudeste e Sul.

📌 Recomendação final:
💡 Vender a loja de Roraima (RR) devido ao baixo faturamento e alto custo de frete, redirecionando esforços para mercados mais lucrativos.

📜 Para mais detalhes sobre metodologia, análises e resultados, consulte o notebook AluraStore.ipynb
