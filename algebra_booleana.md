## Introdução à Álgebra Booleana
A Álgebra Booleana, desenvolvida por George Boole em 1854, é uma estrutura matemática que lógica binária (verdadeiro/falso, 1/0, ligado/desligado). É fundamental para o projeto de circuitos digitais e programação de computadores.

Operações Básicas (Portas Lógicas)
# 1. Porta NOT (Inversor)
Símbolo: Triângulo com círculo na saída

Tabela verdade:

| A |	NOT A |
|------|------|
| 0	| 1 |
| 1 |	0 |

Expressão: Y = Ā ou Y = A'

# 2. Porta AND (E)
Símbolo: Forma de D com entrada múltipla

Tabela verdade (2 entradas):

| A	| B	| A AND B |
|------|------|------|
| 0	| 0	| 0 |
| 0	| 1	| 0 |
| 1	| 0 |	0 |
| 1	| 1	| 1 |

Expressão: Y = A ∧ B ou Y = A·B

# 3. Porta OR (OU)
Símbolo: Forma de cápsula com entrada múltipla

Tabela verdade (2 entradas):

| A	| B |	A OR B |
|------|------|------|
| 0	| 0	| 0 |
| 0	| 1 |	1 |
| 1 |	0 |	1 |
| 1 |	1 |	1 |

Expressão: Y = A ∨ B ou Y = A+B

# 4. Porta NAND (NOT AND)
Combinação de AND + NOT

Tabela verdade:

| A	| B |	A NAND B |
|------|------|------|
| 0	| 0 |	1 |
| 0	| 1 |	1 |
| 1	| 0 |	1 |
| 1	| 1 |	0 |

Expressão: Y = A∧B' ou Y = (A·B)'

# 5. Porta NOR (NOT OR)
Combinação de OR + NOT

Tabela verdade:

| A |	B	| A NOR B |
|------|------|------|
| 0	| 0	| 1 |
| 0	| 1	| 0 |
| 1	| 0	| 0 |
| 1	| 1 |	0 |

Expressão: Y = A∨B' ou Y = (A+B)'

# 6. Porta XOR (OU Exclusivo)
Saída 1 quando as entradas são diferentes

Tabela verdade:

| A	| B	| A XOR B |
|------|------|------|
| 0	| 0	| 0 |
| 0	| 1	| 1 |
| 1	| 0	| 1 |
| 1	| 1	| 0 |

Expressão: Y = A⊕B

# 7. Porta XNOR (Equivalência)
Inverso de XOR (saída 1 quando entradas iguais)

Tabela verdade:

| A	| B	| A XNOR B |
|------|------|------|
| 0 |	0	| 1 |
| 0	| 1 |	0 |
| 1	| 0 |	0 |
| 1	| 1	| 1 |

Expressão: Y = A⊙B

Postulados da Álgebra Booleana
Identidade:

A + 0 = A

A · 1 = A

Elemento nulo:

A + 1 = 1

A · 0 = 0

Idempotência:

A + A = A

A · A = A

Complemento:

A + Ā = 1

A · Ā = 0

Comutatividade:

A + B = B + A

A · B = B · A

Associatividade:

(A + B) + C = A + (B + C)

(A · B) · C = A · (B · C)

Distributividade:

A + (B · C) = (A + B) · (A + C)

A · (B + C) = (A · B) + (A · C)

Leis de De Morgan:

(A + B)' = A' · B'

(A · B)' = A' + B'

## Aplicações Práticas
1. Circuitos digitais: Todas as operações em computadores são baseadas em combinações de portas lógicas

2. Memórias: Células de memória usam combinações de portas lógicas

3. Processadores: Unidades lógicas aritméticas (ALUs) implementam operações matemáticas usando álgebra booleana

4. Sistemas de controle: Automação industrial, sistemas embarcados

5. Programação: Condições lógicas em linguagens de programação

## Simplificação de Expressões Booleanas
### Técnicas para simplificar circuitos:

- Mapas de Karnaugh: Método gráfico para simplificação

- Álgebra booleana: Aplicação dos postulados e teoremas

- Quine-McCluskey: Algoritmo sistemático para simplificação

## Universalidade das Portas NAND e NOR
### Qualquer função booleana pode ser implementada usando apenas:

- Portas NAND, ou

- Portas NOR

Isso é útil na fabricação de circuitos integrados, pois simplifica o processo de produção.
