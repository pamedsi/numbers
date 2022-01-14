# numbers

Portuguese:

Em um desafio de processo seletivo, nos foi proposto um exercício de roteamento.
O conteúdo das rotas não era importante, e sim fazer as rotas do site.

Já que deram essa liberdade, eu decidi trabalhar com números, criei uma rota para alguns tipos de números, de 1 a 1.000.000.
Cada rota leva a um objeto JSON com uma lista dos números.

Os tipos são:

- Pares (numbers/even)
- Ímpares (numbers/odd)
- Primos (numbers/prime)
- Múltiplos de 5 (numbers/multipleOfFive)
- Da sequência de Fibonacci (numbers/fibonacci)
- Perfeitos (numbers/perfect)
- Com raíz quadrada inteira (numbers/intSquareRoot)
- Triangulares (numbers/triangular)

Entre parênteses estão as rotas que levam a cada um dos tipos.

O ambiente de desenvolvimento Javascript utilizado foi o Deno, então para gerar o arquivo JSON com os números,
é necessário instalá-lo, e executar o arquivo "api.js"

E para iniciar o servidor, é necessário executar o arquivo "router.js".
