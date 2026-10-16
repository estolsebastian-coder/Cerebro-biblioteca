---
type: libro
title: "_-_Acustica"
author: "kica"
categoria: "ACOND. ACÚSTICO"
paginas: 12
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ACOND. ACÚSTICO/libros/_-_Acustica.pdf"
convertido: 2026-10-16
---

# _-_Acustica

> Texto extraído de `ACOND. ACÚSTICO\libros\_-_Acustica.pdf` (12 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

\4. ROTEIRO DE CÁLCULO PARA ACÚSTICA

DIAGNÓSTICO, PROJETO E AVALIAÇÃO DE DESEMPENHO

a. Caracterizar as condições de exposição: ruído urbano móvel (tráfego viário,

aéreo, etc) e fixo (casas noturnas, indústrias, etc);

b. Identificar o nível de ruído externo: para tráfego viário considerar número de

veículos, distância da fonte, velocidade e inclinação da pista, percentagem de

veículos pesados;

c. Determinar o nível de ruído em dB(A) que atinge o objeto de estudo com as

barreiras existentes;

d. Identificar o nível de ruído interno aceitável nos diversos ambientes (NBR -

10152);

e. Projeto: implantação, distribuição interno, localização dos recintos a serem

estudados, etc;

f. Calcular o tempo de reverberação da sala/ajustar para o tempo ótimo (NB –

101);

g. Calcular o nível de ruído interno, considerando a absorção da sala/inserir filtro

A de ponderação dB(A) e verificar se é compatível com a norma;

h. Garantir o desempenho entre ambientes;

i. Detalhamento.

A. Dados da via: caracterizar as condições de exposição: ruído urbano móvel

(tráfego viário, aéreo, etc.) e fixo (casas noturnas, indústrias, etc.)

B. Identificar o nível de ruído externo: para tráfego viário considerar número de

veículos, distância da fonte, velocidade e inclinação da pista, percentagem

de veículos pesados.

1

<!-- p. 2 -->

Resultados estatísticos de medições na cidade de São Paulo
Espectro típico do ruído de tráfego a 7m da fonte / velocidade 60Km/h
Curvas de referência em dB(A)
125 250 500 1K 2K 4K dB(A)
Via expressa 15.000 veículos/h 83 82 80 78 77 72 87
Via expressa 4.000 veículos/h 77 76 74 72 71 66 81
Via expressa 2.000 veículos/h 75 74 72 70 69 64 79
Via coletora 1.000 veículos/h 71 70 68 66 65 60 75
Via coletora 500 veículos/h 68 67 65 63 62 57 72
Via local 250 veículos/h 65 64 62 60 59 54 69
Via local 100 veículos/h 61 60 58 56 55 50 65
Via local 50 veículos/h 58 57 55 53 52 47 62

Dados da via

distância fonte/receptor d = _______ m
número de veículos/hora Q = ______ veículos

valores de correção pelas tabelas para:
• % de veículos pesados c = _______
• velocidade cv = _______
• inclinação da via em % ci = _______

L = 52 + 10 log (Q/d) + cv + c% + ci dB(A) – Eq. JOSSE p.82

Tabela de Correções
cv correção devido à velocidade dos veículos
velocidade 33 47 53 60 67 78 80 87 93
cv -4 -2 -1 0 +1 +2 +3 +4 +5
cv correção devido à % de veículos pesados
% veículos 7 20 35 47 60 73 87 100
c% 0 +1 +2 +3 +4 +5 +6 +7
cv correção devido à inclinação da via em %
inclinação 0% 2% 4% 6%
ci 0 +1 +2 +3

Curva de referência
125 250 500 1K 2K 4K f (Hz)
84 76 74 72 68 60 dB (A)

2

<!-- p. 3 -->

C. Determinar o nível de ruído em dB(A) que atinge o objeto de estudo com

as barreiras existentes

AMORTECIMENTO POR BARREIRA

fonte: JOSSE, R. La acústica en la construcción, Ed. Gustavo Gili, Barcelona, 1975.

a. Se não houver nenhuma barreira, continuar com o valor calculado pela

equação de Josse; se houver, subtrair o valor do amortecimento (lido no
gráfico acima) do valor calculado pela equação de Josse, em dB (A)1;

b. Construir uma nova curva por freqüência da seguinte maneira:

c. Retomar a curva de referência em dB(A), somar os níveis 2 a 2 pela regra
seguinte, e calcular o nível de ruído externo2;

1 Nota: o livro do Egan apresenta um outro gráfico para cálculo do amortecimento por barreira por
faixa de freqüência, em d(B).
2
Nota: não faz sentido apresentar os valores finais em dB(A) por faixa de freqüência. O dB(A)
sempre é apresentado com um único número para ser comparado com as normas.

3

<!-- p. 4 -->

Soma em dB ou dB(A)

Diferença entre Somar ao maior
os níveis
0 a 1 +3
2 a 3 +2
4 a 8 +1
≥ 9 0

Curva de referência

125 250 500 1K 2K 4K f (Hz)
84 76 74 72 68 60 dB (A)

Somando os níveis dois a dois:
69 74 77 8060

68

72

74

76
85
84

nível de ruído externo da curva de referência = 85 dB(A)

d. Subtrair, do nível de ruído externo da curva de referência, o L calculado pela

equação de Josse = 78 dB(A). Neste exemplo, (85 – 78) a diferença foi igual

7 dB(A).

e. Subtrair essa diferença em dB(A) da curva de referência e construir uma nova

curva por faixa de freqüência, que representa o ruído externo que atinge o
objeto de estudo (Le).3

Curva de ruído de referência

125 250 500 1K 2K 4K f (Hz)
84 76 74 72 68 60 dB (A)
\-7 -7 -7 -7 -7 -7 dB (A)
77 69 67 65 61 53 Le dB(A)

4

<!-- p. 5 -->

Só para conferir o resultado, somar a curva Le 2 a 2 pela regra da soma em d(B) e

ver se coincide com o L calculado pela equação de Josse = 78 dB(A)

D. Identificar o nível de ruído interno aceitável nos diversos ambientes pela

norma NBR – 10152

3 Se o valor calculado pela eq. de Josse for maior do que o nível de ruído externo da curva de referência, deve-se
SOMAR, e não SUBTRAIR a diferença. De qualquer forma, essas duas curvas são sempre paralelas.

5

<!-- p. 6 -->

E. Projeto4

a. Estudo de Implantação;

b. Efeito de vento, temperatura e solo;

c. Distribuição interna em função da geração e da tolerância ao ruído;

d. Compatibilização com a ventilação;

e. Localização dos recintos a serem estudados;

f. Escolha dos revestimentos internos e do mobiliário para calcular o tempo de
reverberação, e ajustar para o tótimo, antes de calcular o nível de ruído interno

já considerando a absorção da sala, para ver se contempla a norma.

4 Desenho: Nelson Solano Vianna.

6

<!-- p. 7 -->

F. Calcular o tempo de reverberação da sala segundo a Norma NB – 101

(Anexo 3). Ajustar para o tempo ótimo nas salas que necessitam de melhor

desempenho acústico (teatros, igrejas, salas de aula, etc).

G. Calcular o nível de ruído interno Li em dB, considerando a absorção da

sala; inserir o filtro dB(A) e verificar se contempla a Norma NBR 10152

Filtro A de Ponderação (para transformar dB em dB(A))

F (Hz) (A)
31.5 -39
63 -26
125 -16
250 -9
500 -3
1000 0
2000 +1
4000 +1
8000 -1

Retomar a curva do ruído externo Le em dB

77 69 67 65 61 53 Le dB(A)
\+16 +9 +3 0 -1 -1 filtro dB
93 78 70 65 60 52 Le dB

Calcular o Li para cada faixa de freqüência pela equação:

Li = Le – R + 10log (S/A) dB

Le já foi calculado;

R é o isolamento da fachada;
• só da alvenaria se a fachada for cega
• só do vidro se a janela estiver fechada e diferença para o R da alvenaria for

maior do que 9dB
• calcular separado para alvenaria e vidro se essa diferença for menor do que

9dB (ex: para um vidro acústico)
• R = 5dB se a janela estiver aberta

S é a área do material por onde entra o ruído;
• área da fachada, se esta for cega
• área da janela, se esta estiver fechada

7

<!-- p. 8 -->

• área efetiva de ventilação, se a janela estiver aberta
A equivale à ∑ (α x S) para todas as superfícies internas, considerando mobiliário e
ocupação5. α é o coeficiente de absorção do material.

Absorção do material 125 250 500 1K 2K 4K
área do material 1
área do material 2
área do material n
∑ (α x S)
Obs.: para objetos e pessoas, multiplicar a absorção α pelo número de unidades.

Calcular Li por faixa de freqüência.

Li em dB filtro dB(A) Li dB(A) norma
Li125 =
Li250 =
Li500 =
Li1K =
Li2k =
Li4k =

Para se comparar o desempenho interno das alterações nos materiais de absorção,

usar a equação NR (noise reduction):

NR = 10 log (a2/a1) , onde:

NR é a redução do nível interno quando se modificam as superfícies de absorção

a1 é a absorção do ambiente

a2 é a absorção do ambiente após as modificações

Para calcular a isolação entre dois ambientes, conhecendo a redução da parede

divisória, utilizar a formula:

NR = R + 10 log (a2 / S) ( onde a2 é a Absorção do ambiente receptor e S é a

área da parede divisória)

5 Valores de α -para diferentes materiais NB 101.

8

<!-- p. 9 -->

H. Garantir isolamento compatível de uma sala para outra: verificar o limite da

norma e procurar um sistema que atinja esse resultado
• pela lei das massas para material homogêneo ou
• pelos catálogos dos fabricantes para os componentes industrializados

LEI DAS MASSAS6

6 Fonte: JOSSE, R. La acústica en la construcción, Ed. Gustavo Gili, Barcelona, 1975.

9

<!-- p. 10 -->

10

<!-- p. 11 -->

Ver também os valores de isolamento da tabela 1 NB101 em anexo

11

<!-- p. 12 -->

H. Detalhamentos

12
