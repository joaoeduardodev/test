Problema:

Você trabalha em uma empresa de cartões de crédito no setor de tecnologia da informação. Ao emitir os cartões, é gerado um código sequencial impresso em cada cartão para identificação e distribuição. No entanto, durante o processo de fabricação e impressão, alguns cartões foram perdidos. Como desenvolvedor, sua tarefa é criar um programa que receba um array de cartões e retorne quais cartões estão faltando no processo de distribuição.

Implemente a função findMissingCards() com os seguintes requisitos:

A função findMissingCards() deve receber um parâmetro $cards, que é um array contendo os códigos sequenciais dos cartões emitidos.
Os códigos sequenciais dos cartões estão em ordem crescente, sem repetições.
Alguns cartões podem estar faltando no array $cards.
A função deve retornar um array contendo os códigos sequenciais dos cartões que estão faltando no processo de distribuição.
Exemplo de Uso:
```php
$cards = [1001, 1002, 1004, 1005, 1007];
$result = findMissingCards($cards);
print_r($result); // Saída esperada: [1003, 1006]

$cards = [2001, 2003, 2004, 2005, 2007, 2008];
$result = findMissingCards($cards);
print_r($result); // Saída esperada: [2002, 2006]
```



Certifique-se de implementar a função findMissingCards() completa. Inclua a definição da função e o código necessário para testá-la com os exemplos de uso fornecidos.
