# H&M Fashion Parquet Performance

Os varejistas de moda estão cada vez mais recorrendo à inteligência artificial (IA) para obter ajuda na busca de oferecer aos clientes o que eles desejam. O varejo orientado por IA permite que as marcas atendam às demandas modernas dos clientes, personalizando a experiência de compra.

À medida que mais empresas de varejo levam seus negócios das lojas tradicionais de varejo para o comércio eletrônico, elas podem obter mais informações sobre as preferências de seus clientes para atender à demanda.

O Grupo H&M é uma empresa multinacional sueca de moda presente em 74 países, com mais de 5000 lojas e tem investido fortemente em inteligência artificial para acompanhar os ciclos da moda.

Este notebook tem como objetivo analisar uma base de dados que apresenta registros de vendas de roupas. Os dados são referentes a comercialização de peças da H&M.

O dataset está disponível no link (www.kaggle.com/datasets/tbierhance/hm-fashion-recommendation-parquet)

O notebook está subdividido nas seguintes etapas:

1) Aquisição dos dados
- Nessa etapa os arquivos .parquet são importados utilizando o método read_parquet() da biblioteca Pandas.
- É realizado a verificação dos dataframes e um tratamento em relação ao arquivo customers.parquet que apresenta uma inconsistência.

2) Análise exploratória
- Na análise exploratório foi realizada a integração dos dataframes e verificado a existência de valores nulos.
- Como melhoria, devem ser inseridos alguns gráficos para verificar o comportamento de algumas variáveis. 
- Além de verificar algumas métricas estatísticas para realizar algum tratamento, caso seja necessário.

3) Descoberta de Insights
- Nessa etapa, algumas perguntas foram levantadas sobre os dados e as respostas obtidas foram utilizadas para a construção de dashboard no Power BI.

4) Apresentação de Insights em um dashboard do Power BI (https://app.powerbi.com/view?r=eyJrIjoiNmNlZGFhN2YtNzA5Zi00NmEwLTk4MDAtMThkYWU0YWI5YjE1IiwidCI6ImQ0MmJlNTIzLTg5ZDQtNGUwMi1hNjJiLWE0MzFhZGZmOTMyMSJ9&pageName=ReportSection)
