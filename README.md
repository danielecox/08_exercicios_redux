Professor Rodrigo Bossini
https://www.rodrigobossini.com.br
Produção: outubro de 2021
ReactJS
Redux
1 Exercícios
Escreva uma função chamada transacao. Ela deve.
- Receber o objeto store como parâmetro.
- Definir um vetor com quatro nomes de pessoas
- Definir um objeto JSON em que as chaves são os valores 0, 1 e 2 e os valores
associados são as seguintes funções. Todas elas recebem um nome por parâmetro.
As ações que criam envolvem esses nomes.
- Associada ao valor 0, há uma função que cria uma ação de criação de contrato e
faz “dispatch”.
- Associada ao valor 1, há uma função que cria uma ação de cancelamento de
contrato e faz “dispatch”.
- Associada ao valor 2, há uma função que sorteia um valor real entre 10 e 30. A
seguir, cria uma ação de solicitação de cashback com esse valor e faz “dispatch”.
A função chamada transacao, depois de definir o mapa de funções, sorteia um valor
entre 0 e 2 e chama a função associada a esse valor, passando como parâmetro o
nome de uma pessoa cujo índice também deve ser sorteado.
No script principal, use setInterval para chamar a função transacao a cada cinco
segundos.
Professor Rodrigo Bossini
https://www.rodrigobossini.com.br
Produção: outubro de 2021
Referências
React – A JavaScript library for building user interfaces. 2021. Disponível em
<https://reactjs.org/>. Acesso em agosto de 2021.
Redux - A predictable state container for JavaScript apps. | Redux. 2021.
Disponível em <https://redux.js.org>. Acesso em outubro de 2021.
