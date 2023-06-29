# Dashboard_Python
Projeto de criação de um dashboard na linguagem python com ajuda da Data Viking.<br>
Esse projeto consistiu em três etapas:<br>
1ª - Ingestão dos dados:<br>
- Importação dos dados e leitura dos dados;<br>
- Cálculo para saber a quantidade de espaço que ocupa todos os arquivos;<br>
- Consolidação dos dados;<br>
- Exportação dos dados em CSV, DB e Parquet.<br>
*Observação: com a extensão Parquet o arquivo ocupa aproximadamente 84mb, já nas extensões CSV e DB ocupa aproximadamente 1gb e 3gb respectivamente.<br>
<br>
2ª - Modelagem dos dados:<br>
- Análise exploratória dos dados;<br>
- Criação de gráficos para melhor análise;<br>
- Webscraping no site do Detran para adicionar os valores de cada infração;<br>
- União entre a base consolidada e a tabela criada com os dados do webscraping.<br>
<br>
3ª - Construção do Dashboard:<br>
- Instalação e criação de um ambiente virtual no cmd com o virtualenv para evitar problemas com versões de pacotes;<br>
- Usamos a biblioteca Dash que possibilita a criação de um dashboard em python.

