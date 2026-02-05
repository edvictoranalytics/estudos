# Arquitetura de dados | Comece por aqui
#### Data Databricks Arquiteturas Data Warehouse

Muito se fala sobre dados, mas você sabe realmente como funciona a jornada do dado | do bruto ao insight?

Quando falamos em arquitetura de dados, estamos falando justamente do caminho que o dado percorre desde a sua origem até virar informação útil para tomada de decisão.

Se você, assim como eu, está aprendendo cada vez mais aqui na DIO, vamos construir esse aprendizado juntos.

# A jornada do dado passa pelas seguintes etapas:

Fontes: de onde os dados nascem (sistemas, APIs, planilhas, sensores etc.).
Ingestão (Ingestion): como esses dados são coletados e levados para o ambiente de dados.
Armazenamento: onde os dados ficam guardados (data lake, data warehouse, banco de dados).
Transformação: limpeza, padronização e enriquecimento dos dados.
Modelagem: criação de relações, métricas e estruturas que facilitam a análise.
Consumo: uso dos dados em relatórios, dashboards e produtos analíticos.
Governança: regras de segurança, qualidade, acesso e conformidade (presente em toda a jornada).
Todo esse processo pode ser englobado pelos conceitos de ETL (Extract, Transform, Load) ou ELT (Extract, Load, Transform). A escolha entre um ou outro depende de diversos fatores, como volume de dados, complexidade do ambiente e tipo de banco utilizado.

# Dentro dessa arquitetura, lidamos com diferentes tipos de dados:

Dados estruturados: organizados em linhas e colunas, comuns em bancos relacionais (SQL).
Dados semiestruturados: possuem organização flexível por meio de tags ou chaves, como JSON e XML.
Dados não estruturados: não seguem um modelo definido, como textos livres, imagens, áudios e vídeos.
Entender essa jornada é o primeiro passo para compreender como os dados se transformam em insights de negócio. Então, vamos pro a mão na massa!

