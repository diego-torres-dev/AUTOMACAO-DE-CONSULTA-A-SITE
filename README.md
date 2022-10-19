# Automação de Consulta de Processos

## Contexto
Este notebook apresenta uma automação para um sistema fictício de consulta de status de processos jurídicos. 

Esse sistema possui duas páginas: a principal permite selecionar uma cidade a partir de uma lista de opções e a outra nos permite preencher um formulário com os dados de um processo qualquer.

Desejamos realizar consultas para diversos processos e descobrir a situação de cada um deles, dado que um processo pode ter sido encaminhado ou não.

Para realizar diversas consultas e descobrir o status de cada processo, vamos partir do arquivo `Processos.xlsx` — uma planilha do Excel com dados de processos que desejamos consultar.

Ao término da automação, criamos uma nova planilha — `Processos Atualizados.xlsx` —, a qual apresenta a situação de cada processo.


## Bibliotecas

Esta é a lista de bibliotecas usadas neste projeto:

- os
- time
- selenium
- pandas