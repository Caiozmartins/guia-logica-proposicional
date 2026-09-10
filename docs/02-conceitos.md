\# Conceitos Fundamentais de Lógica Proposicional



\## Proposição



Uma proposição é uma frase declarativa que possui um valor lógico: verdadeiro ou falso.



Exemplos:



\- O Brasil está na América do Sul.

\- 10 é maior que 3.



\## Conectivos lógicos



Os conectivos servem para unir ou modificar proposições.



\### Negação



Símbolo:



`¬p`



A negação inverte o valor lógico da proposição.



Exemplo:



\- p: Está chovendo.

\- ¬p: Não está chovendo.



\### Conjunção



Símbolo:



`p ∧ q`



A conjunção é verdadeira somente quando as duas proposições são verdadeiras.



| p | q | p ∧ q |

|---|---|---|

| V | V | V |

| V | F | F |

| F | V | F |

| F | F | F |



\### Disjunção



Símbolo:



`p ∨ q`



A disjunção é falsa somente quando as duas proposições são falsas.



| p | q | p ∨ q |

|---|---|---|

| V | V | V |

| V | F | V |

| F | V | V |

| F | F | F |



\### Condicional



Símbolo:



`p → q`



A condicional é falsa somente quando o antecedente é verdadeiro e o consequente é falso.



| p | q | p → q |

|---|---|---|

| V | V | V |

| V | F | F |

| F | V | V |

| F | F | V |



\### Bicondicional



Símbolo:



`p ↔ q`



A bicondicional é verdadeira quando as duas proposições possuem o mesmo valor lógico.



| p | q | p ↔ q |

|---|---|---|

| V | V | V |

| V | F | F |

| F | V | F |

| F | F | V |



\## Tabela-verdade



A tabela-verdade permite analisar todas as combinações possíveis de valores lógicos de uma expressão.



Para duas proposições existem 4 combinações possíveis.



Para três proposições existem 8 combinações possíveis.



De modo geral, a quantidade de linhas pode ser calculada por:



`2^n`



onde `n` representa a quantidade de proposições.

