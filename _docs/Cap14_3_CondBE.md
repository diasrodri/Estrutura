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
 {% endraw %}              (14.1)

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

{% raw %}
  $$\rho_{II} = \rho_{s} + \rho_{n}$$ 
 {% endraw %}(14.2)

onde $\rho_{s}$é a densidade do superfluido e $\rho_{n}$é a densidade do fluido normal. Quando a temperaturaé reduzida a partir do ponto $\lambda$, a fração da fase super-fluida aumenta e a fração do fluido normal diminui, até restar somente a fase super-fluida no zero absoluto $(T = 0)$.

Na fase super-fluida, todos os átomos de Hélio se encontram no estado de menor energia,
o estado fundamental.
Não é óbvio que o Hélio líquido comporte-se como um gás ideal, já queé de se esperar
que exista interção entre átomos. No entanto, os átomos de Hélio interagem somente por forças
de Van der Walls, que são de pouca intensidade. Além disso, a baixa densidade do Hélio líquido
($0,145g/cm^3$ nas vizinhanças do ponto $\lambda$) sugere que a distância entre átomos seja relativamente grande. Assim, o modelo do gáas ideal para o Hélio léquido deve constituir-se de uma aproximação razoável.

No capítulo 12 concluiu-se ainda que, para uma distribuiçao de Bose-Einstein, o número
de partículas com energia $ε$ é dado por

{% raw %}
  $$N = \sum_{ε}n_{BE}(ε) = \sum_{ ε } \frac{ 1 }{ \exp{\beta ε +\alpha } - 1}$$ 
 {% endraw %}(14.3)

Como se fez com férmions, poderia-se em princípio substituir a distribuição discreta por
uma distribuição contínua, uma vez que, em geral, os níveis de energia são numerosos e estão muito próximos. Ocorre, porém, que quando substitui-se a distribuição discreta por uma distribuiçãao contínua, o estado fundamental desaparece. Isso pode ser visto, por exemplo, na equação (14.3), onde $D_n(ε) ∝ ε^{1/2}$ e, portanto, $D_n(ε) = 0$ para $ε = 0$.

Este fato não é importante para um gás constituído por férmions, já que cada estado
espacial não pode ser ocupado por mais de duas partículas e, portanto, não há problemas em
ignorar duas partículas em por exemplo 1022. Quando o gás é constituído por bósons, porém, não
existe nenhuma restri çao quanto ao número de partículas que podem ocupar o mesmo estado.
Particularmente, no Hélio líquido, os estado de mais baixa energia, principalmente o estado
fundamental, são importantes.

O número de ocupa çoes $N_0$ do estado fundamental $ε_0$ pode ser calculado a partir da
equaçãoo (14.3), assumindo-se uma condiçãoo de contorno de ondas progressivas para partículas no
interior de uma caixa grande de comprimento $L$, onde $ε_0 = 0$, isto é,

{% raw %}
  $$N_0 = (\exp{\alpha } - 1)^{-1}$$ 
 {% endraw %}(14.4)

Evidentemente, pode-se assumir $α > 0$ tal que $N_0$ é finito e positivo para bósons. E bom lembrar que, no caso de férmions a baixas temperaturas, $α < 0$, pois este é proporcional ao negativo da energia de Fermi $(α = -\beta ε_F )$. Entretanto, nesses casos, $N_0 = (\exp{\alpha } - 1)^{-1}$. Se $α$ é muito pequeno, em particular $α = 1/N$, da expansão em série 
$\exp{α} = 1 + α + α^2 + ··· ≈ 1 + 1/N$, a equação (14.4) torna-se

{% raw %}
  $$N_0 ≈ (1 + 1/N - 1)^{-1}=N$$ 
 {% endraw %}(14.5)

O número de partículas N para qualquer valor de α, dado na equa çao (14.3), pode ser
reescrito então como

{% raw %}
  $$N = N_0 + \sum_{ε\ne 0} \frac{ 1 }{ \exp{\beta ε +\alpha } - 1}$$ 
 {% endraw %}(14.6)

Como a ocupação do estado fundamental está preservada na equação (14.6), a distribuição
discreta pode agora ser substituída por uma distribuição contínua, obtida a partir da função densidade de estados, dada na equação (14.1),

{% raw %}
  $$N = N_0 + \int_{0}^{\inf} n_{BE} D_m(ε) dε = N_0 +AV \int_{0}^{\inf} (\exp{\beta ε+\alpha}-1)^{-1} ε^{1/2} dε$$ 
 {% endraw %}

ou, adotando-se a troca de variável $z = βε$,

{% raw %}
  $$N = N_0 +AV(k_B T)^{3/2} G(\alpha)$$ 
 {% endraw %} (14.7)

onde

{% raw %}
  $$G(\alpha) = \int_{0}^{\inf} dz z^{1/2}(\exp{z+\alpha}-1)^{-1} $$ 
 {% endraw %} (14.8)

Para valores muito grandes de $α$, pode-se adotar somente os dois primeiros termos da
expansão da função $(e^{z+α}-1)^{−1}$ e mostrar que

{% raw %}
  $$G(\alpha) \sim \frac{\sqrt{\pi}}{2}\exp{-\alpha} $$ 
 {% endraw %} (14.9)

Para $α = 0$, pode-se calcular a integral na equação (14.8) e mostrar que

{% raw %}
  $$G(0) =\frac{\sqrt{\pi}}{2} 2,612 $$ 
 {% endraw %} (14.10)

Quando $α$ é da ordem de $1/N$, isto é, pequeno o suficiente para que $G(α) ≈ G(0)=\frac{\sqrt{\pi}}{2} 2,612$, a equação (14.7) resulta em

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

No modelo de dois fluidos de London, os $N_0$ átomos que foram acrescentados na equação
(14.6) se condensaram no estado fundamental. São estes átomos que constituem o superfluido. Os
$N - N_0$ átomos restantes constituem o fluido normal.

A concordância do valor teórico da temperatura crítica $T_c = 3,1K$ com o valor experimental da temperatura do ponto lambda, $T_c = 2,17K$, pode ser considerada razoável, particularmente se for levado em considera çao que os cálculos teóricos se baseiam na hipótese de que o Hélio líquido se comporta como um gás ideal.

O processo de acumulaçao de átomos no estado fundamental a uma temperatura $T = 0$
é denominada condensação de Bose-Einstein. O fenômeno foi previsto por Einstein em 1924,
mas levou mais de 70 anos para ser observado em átomos de rubídio, como se verá na próxima
seção.

2 Exercícios

1 - O que é a condensa çao de Bose-Einstein? Por que átomos de $3^He$ podem formar
condensados de Bose-Einstein, apesar de terem spins semi–inteiros?

2 - O hidrogênio spin polarizado tem sido condensado a uma densidade de $ρ = 5×10^{24} atomos/m^3$. Calcule a temperatura crítica $T_c$ para essa densidade assumindo-se que esse sistema comporta-se como um gás ideal. Resp.: 47mK

3 - Obtenha a energia total e a capacidade térmica para um gás ideal de Bósons, considerando que este esteja à uma temperatura abaixo da temperatura crítica $T_c$ para a condensação de Bose-Einstein.
