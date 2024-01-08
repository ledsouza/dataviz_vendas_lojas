# Estudos de Visualização de Dados

Desenvolver habilidades avançadas em visualização de dados, capacitando-me a aprender, associar adequadamente, experimentar técnicas de foco, personalizar e diferenciar diversos tipos de visualizações, incorporando boas práticas.

| :books: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Estudos de Visualização de Dados**
| :label: Tecnologias | python, pandas, matplotlib, seaborn, pyplot, numpy

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://vitrinedev.s3.amazonaws.com/dataviz_graficos.png#vitrinedev)

## Detalhes do projeto

### Dados

Há um total de cinco datasets nesse projeto:
- [Relatório de vendas](https://raw.githubusercontent.com/alura-cursos/dataviz-graficos/master/dados/relatorio_vendas.csv)
- [Amostras de volumes do amaciante](https://raw.githubusercontent.com/alura-cursos/dataviz-graficos/master/dados/volume_amaciante.csv)
- [Amostras das medidas da embalagem de sabão em pó](https://raw.githubusercontent.com/alura-cursos/dataviz-graficos/master/dados/medidas_sabao_em_po.csv)
- Relatório de notas de uma turma fictícia
- Relatório de idades de uma cidade fictícia

### Desenvolvimento

São utilizados recursos de visualização de dados como gráficos, anotações, destaques de dados entre outros, para responder aos questionamentos de uma rede de lojas de departamentos que opera em todo Brasil.

Esse tipo de exploração dos dados será importante para gerar insights para a rede e também para apresentar como os estados ou sua clientela estão se comportando nas vendas de seus produtos.

Em relação ao relatório de vendas, existem os seguintes dados:
- data_pedido: data em que o cliente realizou o pedido do produto.
- data_envio: data em que o produto foi enviado ao cliente.
- modo_envio: modo de envio do produto especificado pelo cliente.
- nome_cliente: nome do cliente.
- segmento_cliente: o segmento a que pertence o cliente, podendo ser B2B ou B2C.
- cidade: cidade de destino do pedido.
- estado: estado de destino do pedido.
- regiao: região de destino do pedido.
- departamento: departamento do produto encomendado.
- tipo_produto: categoria do produto encomendado.
- preco_base: preço base de uma unidade do produto
- preco_unit_sem_desc: preço unitário de venda do produto sem desconto
- desconto: desconto fornecido na compra.
- preco_unit_venda: preço unitário de venda do produto com desconto
- quantidade: quantidade do produto requisitada.
- vendas: valor da venda das unidades requisitadas do produto.
- lucro: valor do lucro/prejuízo da empresa considerando o preço base do produto.

A segunda parte do projeto é focada na criação de diferentes visualizações que apresentam a distribuição dos dados. É utilizado outros recursos de visualização de dados como anotações com setas, elipses e linhas horizontais e verticais para responder aos questionamentos de uma fábrica de produtos de higiene e limpeza.

Será trabalhado com os dados de amostras de seus produtos fabricados, com os volumes e as dimensões de seus produtos documentados, para teste de acordo com os critérios de qualidade. Serão analisados e descritas algumas métricas (média, mediana e moda) das amostras utilizando gráficos para facilitar a compreensão desses valores.

#### Base de Dados 1 - Amostra dos volumes do amaciante
Esta base de dados possui 1000 amostras selecionadas do volume de uma dada marca de amaciante, contabilizando se o volume deste produto está próximo do valor de 1L (1000 ml).

- Volume: volume medido das amostras com valores em mililitros (ml).

#### Base de Dados 2 - Amostras das dimensões de uma embalagem de sabão em pó
Esta base de dados possui as medidas de altura, comprimento e largura de uma caixa de sabão em pó em um total de 1000 amostras medidas. Existem no total 5 grandes amostras, cada uma com 200 registros.

- comprimento: comprimento medido das amostras com valores em centímetros (cm).
- altura: altura medida das amostras com valores em centímetros (cm).
- largura: largura medida das amostras com valores em centímetros (cm).
- amostra: identificador da amostra medida (A a E).

### Extra

Como atividade extra, foram desenvolvidas visualizações simples, utilizando o plotly, dos relatórios de notas e idades fictícios.
