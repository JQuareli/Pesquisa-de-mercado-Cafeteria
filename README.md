# Pesquisa-de-mercado-Cafeteria

Este projeto foi desenvolvido para realizar uma pesquisa de mercado detalhada sobre restaurantes na cidade de Los Angeles. Iniciando com a limpeza e otimização dos dados brutos, o objetivo é gerar gráficos e visualizações claras para extrair conclusões e recomendações a respeito da localização e tamanho da cafeteria. Estas conclusões serão apresentadas a investidores locais com o objetivo de angariar apoio financeiro para uma pequena cafeteria que se destaca com garçons robôs.

## Índice

- [Metodologia](#metodologia)
- [Bibliotecas Utilizadas](#bibliotecas-utilizadas)
- [Conclusões](#conclusões)
- [Como Utilizar](#como-utilizar-este-repositório)
- [Possíveis Melhorias](#possíveis-melhorias)

## Metodologia

### Carregamento e Preparação dos Dados

1. **Carregamento dos Dados**:
    - Dados sobre restaurantes em Los Angeles: `rest_data_us_upd.csv`

2. **Preparação dos Dados**:
    - Neste ponto os dados foram limpos e organizados utilizando a biblioteca Pandas do Python para garantir a precisão das análises subsequentes. Além disso, foi necessário criar colunas específicas para os dados do endereço, e nome da rede, que continham caracteres que atrapalhavam os agrupamentos por rede.

### Relatórios e Cálculo de Métricas

1. **Proporções de Restaurantes**:
    - Foram analisados os dados a respeito do tipo de restaurante (Bakery, Bar, Cafe, Fast Food, Pizza, Restaurant) e avaliadas as proporções de cada um na região. Esta análise foi feita nos dados como um todo e também após agrupar os restaurantes entre os pertencentes a redes e os não pertencentes.

2. **Números de Assentos**:
    - Também foram avaliados os números de assentos de cada tipo de restaurante e também entre os pertencentes ou não a redes, para identificar qual a maior tendência do mercado atual.

3. **Quantidade de Restaurantes**:
    - Nesta parte do projeto, foram avaliados dois números em relação a quantidade: o número de restaurantes pertencentes a cada rede de restaurantes, a fim de identificar aqueles que o mercado já está saturado, ou os que não possuem muitas lojas; e o número de restaurantes por rua, tentando identificar o melhor lugar para se localizar.

Por fim, ainda foram tiradas conclusões a respeito do local, tipo do restaurante (rede ou não rede) e em relação ao número de assentos.

## Bibliotecas Utilizadas

As seguintes bibliotecas Python foram utilizadas para a análise de dados e visualização:

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Plotly-Express](https://plotly.com/python/plotly-express/)

## Conclusões
O projeto ainda não foi concluído, e a conclusão final será atualizada na íntegra assim que o projeto for finalizado por completo.

## Como utilizar este repositório

Para utilizar, basta clonar o repositório e instalar o arquivo requirements.txt em um ambiente Python. Os scripts são bem documentados e podem ser facilmente adaptados para outras análises de dados. Ao final do projeto, foi montado uma apresentação dos dados em formato PDF, que pode ser acessada clicado no link do projeto, ou acessando por [aqui](https://link-da-apresentação).

## Possíveis melhorias

