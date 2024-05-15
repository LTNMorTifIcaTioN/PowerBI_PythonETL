Dashboard de RH em Power BI com pipeline de dados e ETL em Python via Jupyter Notebook

Pré-requisitos
Python 3.x

Bibliotecas: numpy, pandas, openpyxl, plotly.express

Instalação
Clone o repositório.
Instale o Jupyter Notebook e o Power BI em seu computador.

Uso
Execute o script Analise_Exploratoria_POC.ipynb
Os dados serão lidos de uma planilha online e processados.
Os resultados serão exibidos em gráficos interativos.

Estrutura do Projeto
Analise_Exploratoria_POC.ipynb: Script principal para processamento dos dados (pipeline e ELT).
Base_de_dados_tratada.csv: Arquivo CSV com os dados tratados.
Base_de_Dados_Ficticia_Despadronizada.xlsx: Arquivo excel com dados originais.
POC_DataInov.pbix: projeto de ETL em Power Query M
Portifolio_RH.pbix: Visualização final dos dados no Power BI

Resultados
Análise Exploratória
Visualização da distribuição de idade e peso.
Cálculo do IMC (Índice de Massa Corporal).
Geolocalização
Mapeamento das cidades para estados.
Criação da coluna “Endereco_CEP” com endereço completo.
Informações Adicionais
Ano de nascimento a partir da idade.
Correção da coluna “Data_Nascimento”.
Classificação do IMC.
Classificação social com base no salário.

Visualização de Dados
Dashboard Interativo
O projeto inclui um dashboard interativo chamado Portifolio_RH.pbix, que permite uma análise visual dos dados processados. Este dashboard foi criado utilizando o Power BI e oferece insights detalhados através de gráficos e métricas.

Funcionalidades do Dashboard
Plotagem Dinâmica: Os usuários podem interagir com os dados, selecionando diferentes parâmetros para visualizar as métricas específicas.
Filtros e Segmentação: Filtros permitem que os usuários visualizem dados segmentados, como por departamento, faixa etária ou nível educacional.
Análise Temporal: Visualização da evolução dos dados ao longo do tempo, permitindo identificar tendências e padrões.
Modelagem dos Fatos e Dimensões em Star Schema.
Uso de Linguagem M, Dax e Parâmetros.

Como Acessar
Para acessar o dashboard:
Abra o arquivo Portifolio_RH.pbix com o Power BI Desktop.
Explore as diferentes abas e filtros para analisar os dados.
