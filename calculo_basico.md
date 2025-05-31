# Cálculo Básico: Derivadas e Integrais
## Derivadas
Conceito Fundamental
A derivada representa a taxa de variação instantânea de uma função em relação à sua variável independente. Geometricamente, é a inclinação da reta tangente à curva da função em um ponto.

### Notações:
- f'(x) (notação de Lagrange)

- dy/dx (notação de Leibniz)

- Df(x) (notação de Euler)

### Regras Básicas de Derivação:
1. Derivada de uma constante:

- d/dx [c] = 0

2. Regra da potência:

- d/dx [xⁿ] = n·xⁿ⁻¹

3. Derivada da exponencial:

- d/dx [eˣ] = eˣ

- d/dx [aˣ] = aˣ·ln(a)

4. Derivada do logaritmo:

- d/dx [ln(x)] = 1/x

- d/dx [logₐ(x)] = 1/(x·ln(a))

5. Regras operacionais:

- Soma: (f + g)' = f' + g'

- Produto: (f·g)' = f'·g + f·g'

- Quociente: (f/g)' = (f'·g - f·g')/g²

- Cadeia: (f(g(x)))' = f'(g(x))·g'(x)

### Derivadas de Funções Trigonométricas:
- d/dx [sen(x)] = cos(x)

- d/dx [cos(x)] = -sen(x)

- d/dx [tan(x)] = sec²(x)

- d/dx [cot(x)] = -csc²(x)

- d/dx [sec(x)] = sec(x)·tan(x)

- d/dx [csc(x)] = -csc(x)·cot(x)

## Integrais
### Conceito Fundamental
A integral representa a área sob a curva de uma função (integral definida) ou a antiderivada de uma função (integral indefinida).

### Notações:
- ∫f(x)dx (integral indefinida)

- ∫[a,b] f(x)dx (integral definida de a até b)

### Integrais Imediatas:
1. Integral da potência (n ≠ -1):

- ∫xⁿ dx = xⁿ⁺¹/(n+1) + C

2. Integral do inverso:

- ∫(1/x) dx = ln|x| + C

3. Integral da exponencial:

- ∫eˣ dx = eˣ + C

- ∫aˣ dx = aˣ/ln(a) + C

4. Integrais trigonométricas:

- ∫sen(x) dx = -cos(x) + C

- ∫cos(x) dx = sen(x) + C

- ∫sec²(x) dx = tan(x) + C

- ∫csc²(x) dx = -cot(x) + C

### Técnicas de Integração:
1. Substituição simples:

- ∫f(g(x))·g'(x)dx = ∫f(u)du, onde u = g(x)

2. Integração por partes:

- ∫u dv = uv - ∫v du

3. Frações parciais:

- Para integrar funções racionais P(x)/Q(x)

4. Substituição trigonométrica:

- Para integrandos com √(a²-x²), √(a²+x²) ou √(x²-a²)

### Teorema Fundamental do Cálculo:
Se F é uma antiderivada de f no intervalo [a,b], então:
∫[a,b] f(x)dx = F(b) - F(a)

## Aplicações
### Derivadas:
- Velocidade (derivada da posição)

- Aceleração (derivada da velocidade)

- Taxas relacionadas

- Máximos e mínimos de funções

- Análise de gráficos (concavidade, pontos de inflexão)

### Integrais:
- Cálculo de áreas

- Cálculo de volumes de revolução

- Trabalho em física

- Valor médio de funções

- Cálculo de probabilidades

## Exemplos Práticos
### Derivada:
Calcular a derivada de f(x) = 3x⁴ - 2x² + 5x - 7
f'(x) = 12x³ - 4x + 5

### Integral:
Calcular ∫(4x³ - 3x² + 6)dx
= x⁴ - x³ + 6x + C

### Integral Definida:
Calcular ∫[0,1] (2x + 3)dx
= [x² + 3x] de 0 a 1 = (1 + 3) - (0 + 0) = 4

Este é um resumo básico do cálculo diferencial e integral.
