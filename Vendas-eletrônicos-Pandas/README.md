# Tarefas Ciência de Dados Pandas
Estudo de um dataset de produtos eletrônicos vendidos nos EUA utilizando ferramentas como pandas e matplotlib.


## O que foi feito neste estudo:

Usou-se Python Pandas e Python Matplotlib para analisar e responder perguntas de business sobre 12 meses de dados sobre as vendas. O dataset
contem centenas de milhares de compras deprodutos eletrônicos divididos por mês, produto, custo, endereço de compra, etc.

Começo limpando os dados. Onde exercito as seguintes tarefas:
- Excluir valores NaN do DataFrame;
- Remover linhas com base numa condição;
- Alternar os tipos de colunas (to_numeric, to_datetime).

Com nosos dados limpos. Respondi 5 questões de business relacionadas aos nossos dados:
- Qual foi o mês com maior lucro? E quanto que foi?
- Qual cidade teve o maior número de vendas?
- Quanto tempo devemos ter de propaganda para maximizar as chances do consumidor comprar os produtos?
- Quais pares de produtos mais costumam ser vendidos juntos?
- Qual produto vendeu mais e por que será?

Para responder estas perguntas utilizei diferentes métodos de pandas e matplotlib, como:
- Concatenar diversos arquivos .cvs juntos para criar um novo DataFrame (pd.concat);
- Addicionar novas colunas;
- Analisar colunas do DataFrame como strings a fim de fazer novas colunas (.str)
- Usar o método .apply() junto com a função lambda e outras;
- Usar o método groupby a fim de realizar análises agregadas;
- Plotar gráficos de barra e de linha para vizualizar nossos resultados;
- Configurar as legendas dos gráficos.
