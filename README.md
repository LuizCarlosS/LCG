# LCG

### Implementação de Gerador Linear Congruente de Números Pseudoaleatórios.
#### INTRODUÇÃO:

Para implementação de geradores de números pseudoaleatórios (PRNG, sigla em inglês) um gerador congruente linear (LCG, sigla 
em inglês) é frequentemente usado.
Um LCG é definido pela relação de recorrência:

                                         Xn+1 = aXn + b (mod m)

onde Xn é o n-ésimo número da sequência gerada e a, b, m são inteiros constantes que especificam o gerador.


#### OBJETIVOS:

O programa GeradorPseudoaleatorio.c tem como objetivo implementar o algoritmo LCG mod 2ˆ64, elaborar teste comparativo de 
velocidade entre a função rand( ), nativa do GCC, e o código implementado para as seguintes quantidades de gerações: 100.000, 
1.000.000, 10.000.000 e 100.000.000, sendo todas as gerações definidas no intervalo de 0 a 9.

Será realizado também para o experimento o teste do Chi-quadrado aplicado para as duas distribuições encontradas.
