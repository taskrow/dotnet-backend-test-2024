# Banco de dados

A partir do banco de dados criado na parte 2, pediremos a seguir algumas queries SQL. Se achar conveniente pode responder essas questões utilizando queries EF ou Linq2SQL.

## 3.1 - Listagem de solicitações

Lista de meses com o número de solicitações abertas, os 2 grupos que mais solicitaram (diretamente)

Colunas de saída:
- Ano
- Mês
- Número de solicitações
- Grupo solicitante 1
- Grupo solicitante 2

## 3.2 - Tipos de solicitações mais frequentes

Recebendo os parâmetros ano e mês, liste os 5 tipos de solicitação mais frequentes, com o número de solicitações e o grupo solicitante que mais solicitou cada tipo.

Colunas de saída:
- Tipo de solicitação
- Número de solicitações
- Grupo solicitante

## 3.3 - Limites de solicitações

Recebendo os parâmetros ano e mês, liste a partir dos limites para esse mês o percentual do limite consumido. Lembrando que quando um grupo não tem limite para um tipo de solicitação, aplica-se o limite de algum grupo superior.

Colunas de saída:
- Grupo solicitante
- Tipo de solicitação
- Limite
- Solicitações
- Percentual consumido (0 a 100%)