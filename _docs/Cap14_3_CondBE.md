---
title: Capítulo 14.3 - Condensado de Bose-Einstein
description: Condensado de Bose-Einstein.
---



### 14.3 - Condensado de Bose-Einstein

Heitor Ribeiro
October 2021

Condensado De Bose-Einstein

Viu-se no capítulo 12 que, para qualquer estatística, a densidade de estados de energia $ε$ para
um sistema de partıculas de massa $m$ seria

{% raw %}
  $$D_m(ε) = \frac{ m^{3/2} }{ \sqrt{2}\pi^2\hbar^3 } V ε^{1/2}$$ 
 {% endraw %}

{% raw %}
  $$D_m(ε) = A V ε^{1/2}$$ 
 {% endraw %}(14.1)

onde $V$ e o volume do sistema e $A = m^{3/2}/\sqrt{2}\pi^2\hbar^3$

Para um gas em condições normais, geralmente a diferença entre as distribuições de
Maxwell-Boltzmann e Bose-Einsteiné pequena. Isso ocorre porque nestes casos a densidade de
partículas $\rho$é pequena ou porque o volume $V = N/\rho$é grande, de modo que há um número elevado de estados quânticos por partícula, ou seja, uma alta densidade de estados $D_m (ε)$.
No caso do Helio lıquido, entretanto, a temperatura Té baixa e o comprimento de onda
térmico de de Broglie, $\lambda_{th} ∝ T^{-1/2}$, dada na eq.(12.75) do Capítulo 12, não e pequeno o suficiente para que usemos a estatística clássica.

A ideia ousada de que o Hélio líquido pode ser tratado como um gás ideal que obedece a
distribuição de Bose-Einstein foi proposta em 1928 por F. London na tentativa de compreender o
comportamento do hélio a baixas temperaturas.
Na teoria de London, conhecida como modelo de dois fluídos, considera-se o Hélio
II (Helio com $T < T_c$) formado por dois componentes: um fluido normal, com propriedades
semelhantes a do Hélio I (Hélio com $T > T_c$), e um superfluido de propriedades muito diferentes.

A densidade $\rho_{II}$ do Hélio II seria, então,

$\rho_{II} = \rho_{s} + \rho_{n}$,

onde $\rho_{s}$é a densidade do superfluido e $\rho_{n}$é a densidade do fluido normal. Quando a temperaturaé reduzida a partir do ponto $\lambada$, a fração da fase super-fluida aumenta e a fração do fluido normal diminui, até restar somente a fase super-fluida no zero absoluto $(T = 0)$.

Na fase super-fluida, todos os  ́atomos de Hélio se encontram no estado de menor energia,
o estado fundamental.
Nãoé ́obvio que o Hélio líquido comporte-se como um gás ideal, já queé de se esperar
que exista interção entre átomos. No entanto, os  ́atomos de Hélio interagem somente por forças
de Van der Walls, que são de pouca intensidade. Além disso, a baixa densidade do Hélio líquido
($0,145g/cm^3$ nas vizinhanças do ponto $\lambda$) sugere que a distância entre átomos seja relativamente grande. Assim, o modelo do gáas ideal para o Hélio léquido deve constituir-se de uma aproximação razoável.

No capítulo 12 concluiu-se ainda que, para uma distribuiçao de Bose-Einstein, o número
de partículas com energia $ε$ é dado por

N =
X
ε
nBE(ε) = X
ε
1
e
βε+α − 1
. (14.3)
Como se fez com f ́ermions, poderia-se em princípio substituir a distribui çao discreta por
uma distribui çao contínua, uma vez que, em geral, os níveis de energia s ̃ao numerosos e est ̃ao muito
pr ́oximos. Ocorre, por ́em, que quando substitui-se a distribui çao discreta por uma distribui çao
contínua, o estado fundamental desaparece. Isso pode ser visto, por exemplo, na equa çao (14.3),
onde Dn(ε) ∝ ε
1/2
e, portanto, Dn(ε) = 0 para ε = 0.
Este fato n ̃ao  ́e importante para um g ́as constituído por f ́ermions, j ́a que cada estado
espacial n ̃ao pode ser ocupado por mais de duas partículas e, portanto, n ̃ao h ́a problemas em
ignorar duas partículas em por exemplo 1022. Quando o g ́as  ́e constituído por b ́osons, por ́em, n ̃ao
existe nenhuma restri çao quanto ao n ́umero de partículas que podem ocupar o mesmo estado.
Particularmente, no H ́elio líquido, os estado de mais baixa energia, principalmente o estado
fundamental, s ̃ao importantes.
O n ́umero de ocupa çoes N0 do estado fundamental ε0 pode ser calculado a partir da
equa çao (14.3), assumindo-se uma condi çao de contorno de ondas progressivas para partículas no
interior de uma caixa grande de comprimento L, onde ε0 = 0, isto  ́e,

N0 = (e
α − 1)−1
. (14.4)
Evidentemente, pode-se assumir α > 0 tal que N0  ́e finito e positivo para b ́osons. E bom  ́
lembrar que, no caso de f ́ermions a baixas temperaturas, α < 0, pois este  ́e proporcional ao negativo
da energia de Fermi (α = −βεF ). Entretanto, nesses casos, N0 = (e

α + 1)−1 > 0. Se α  ́e muito

pequeno, em particular α = 1/N, da expans ̃ao em s ́erie e

α = 1 + α + α

2/2! + · · · ≈ 1 + 1/N, a

equa çao (14.4) torna-se

2

N0 ≈ (1 + 1
N
− 1)−1 = N. (14.5)
O n ́umero de partículas N para qualquer valor de α, dado na equa çao (14.3), pode ser
reescrito ent ̃ao como

N = N0 +
X
ε̸=0
1
e
βε+α − 1
. (14.6)

Como a ocupa çao do estado fundamental est ́a preservada na equa çao (14.6), a distribui çao

discreta pode agora ser substituída por uma distribui çao contínua, obtida a partir da fun çao den-
sidade de estados, dada na equa çao (14.1),

N = N0 +
Z ∞
0
nBE(ε)Dm(ε)dε = N0 + AV Z ∞
0
dε ε1/2
(e
βε+α − 1)−1

, (1)

ou, adotando-se a troca de vari ́avel z = βε,

N = N0 + AV G(kbT)

3/2G(α), (14.7)

onde

G(α) = Z ∞
0
dz z1/2
(e
z+α − 1)−1
. (14.8)
Para valores muito grandes de α, pode-se adotar somente os dois primeiros termos da
expans ̃ao da fun çao (e
z+α − 1)−1

e mostrar que

G(α) ≈
√
π
2
e
−α
. (14.9)

Para α = 0, pode-se calcular a integral na equa çao (14.8) e mostrar que

G(α) ≈
√
π
2
2, 612. (14.10)
Quando α  ́e da ordem de 1/N, isto  ́e, pequeno o suficiente para que G(α) ≈ G(0), a
equa çao (14.7) resulta em

N0 = N − AV (kBT)
3/2
√
π
2
2, 612. (14.11)

3

Figure 1: Comportamento da fra çao N0/N em fun çao da temperatura T

ou

N0
N
= 1 −

T
Tc
3/2
, (14.12)

onde

Tc =
1
kB

2N
V A√
π2, 6122/3
=
2πħ
2
kBm

ρ
2, 6122/3
. (14.13)

Com A = m3/2/
√
2π
2ħ
3
e ρ = N/V sendo a densidade de partículas. A figura abaixo
mostra a fra çao N0/N de superfluidos N0 na mistura N em fun çao da temperatura T para T ≤ Tc,
de acordo com a equa çao (14.12).
No modelo de dois fluidos de London, os N0  ́atomos que foram acrescentados na equa çao
(14.6) se condensaram no estado fundamental. S ̃ao estes  ́atomos que constituem o superfluido. Os
N − N0  ́atomos restantes constituem o fluido normal.

A concordˆancia do valor te ́orico da temperatura crítica Tc = 3, 1K com o valor experimen-
tal da temperatura do ponto lambda, Tc = 2, 17K, pode ser considerada razo ́avel, particularmente

se for levado em considera çao que os c ́alculos te ́oricos se baseiam na hip ́otese de que o H ́elio líquido
se comporta como um g ́as ideal.

4

O processo de acumula çao de  ́atomos no estado fundamental a uma temperatura T = 0
 ́e denominada condensa çao de Bose-Einstein. O fenˆomeno foi previsto por Einstein em 1924,
mas levou mais de 70 anos para ser observado em  ́atomos de rubídio, como se ver ́a na pr ́oxima
se çao.

2 Exercícios

1 - O que  ́e a condensa çao de Bose-Einstein? Por que  ́atomos de 3He podem formar
condensados de Bose-Einstein, apesar de terem spins semi–inteiros?
2 - O hidrogˆenio spin polarizado tem sido condensado a uma densidade de ρ = 5 ×
1024 atomos/m  ́
3
. Calcule a temperatura crítica Tc para essa densidade assumindo-se que esse

sistema comporta-se como um g ́as ideal. Resp.: 47mK

3 - Obtenha a energia total e a capacidade t ́ermica para um g ́as ideal de B ́osons, con-
siderando que este esteja `a uma temperatura abaixo da temperatura crítica Tc para a condensa çao

de Bose-Einstein.
