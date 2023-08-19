# RNP - E-Commerce Data Case - Python Dev Jr

Este repositório abjetiva a resolução do case técnico apresentado por PSM Company e RNP.
O case, consiste na extração de dados armazenados em um PostgreSQL, realizar as operações solicitadas, descritas em 'RNP-TESTE.txt", e, disponibilizar os resultados obtidos em tabelas no formato Delta junto do(s) algoritmos desenvolvidos.

## Ferramentas Utilizadas
    - Databricks Community
    - Python/PySpark
    - pgAdmin 4
    - Lucid Chart

### Diagrama ER
![Diagrama ER](https://github.com/dev-torugo/ecommerce-data-case/blob/main/Respostas/RNP%20-%20Q1%20-%20Diagrama%20de%20ER.jpeg)

### Execução e Verificação

O arquivo [RNP - E-COMMERCE DATA CASE.ipynb](https://github.com/dev-torugo/ecommerce-data-case/blob/main/Respostas/RNP%20-%20E-COMMERCE%20DATA%20CASE.ipynb) contendo as operações solicitadas, está disposto na pasta Respostas e poderá ser utilizado para execução/verificação.

Para executá-lo no ambiente Databricks Community, basta importar o arquivo para o Workspace criado no Databricks.

### Pedras encontradas no caminho
    - Para resolução da questão 4, fez-se necessário a criação de uma query de merge para cada uma das tabelas presentes no banco de dados.
    - Também na questão 4, houve a necessidade da trasnformação dos arquivos Parquet em Delta Datalake. Tal movimento foi necessário para que a rotina de UPDATE, INSERT e DELETE desempenhasse seu papel de maneira satisfatória. Caso haja impossibilidade de transformação dos arquivos parquet, sugiro que a rotina seja implementada utilizando PySpark Dataframes.

### Sugestões
    - Acredito que, ao fornecer um gabarito para as perguntas propostas na questão 5 cria-se uma base de verificação da resposta encontrada pelo candidato. De maneira, à auxiliá-lo a encontrar o caminho correto para resolução da atividade proposta.

### Aos interessados
Caso deseje perguntar, sugerir ou recomendar algo, não hesite em entrar em contato via e-mail, este, disponibilizado na apresentação do perfil.
