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
-----------------------------------------------------------------------------------

English:

In a selection process challenge, we were proposed a routing exercise.
The content of the routes was not important, but making the routes of the site.

Since they gave me that freedom, I decided to work with numbers, I created a route for some types of numbers, from 1 to 1,000,000.
Each route leads to a JSON object with a list of numbers.

The types are:

- Pairs (numbers/even)
- Odd (numbers/odd)
- Cousins (numbers/prime)
- Multiples of 5 (numbers/multipleOfFive)
- From the Fibonacci sequence (numbers/fibonacci)
- Perfect (numbers/perfect)
- With integer square root (numbers/intSquareRoot)
- Triangular (numbers/triangular)

In parentheses are the routes that lead to each of the types.

The Javascript runtime used was Deno, so to generate the JSON file with the numbers, it is necessary to install it, and run the file "api.js" with "deno run api.js" on the terminal.

And to start the server, you need to run the "router.js" file.
