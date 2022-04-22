# LÓGICA DE PROGRAMAÇÃO

#### Porque um Software é criado ?

> - para criar soluções para um problema diário.
> 
> - automação e otimização de processos.

#### O que são algoritimos

> - "Um algoritmo é simplesmente uma série de instruções a serem seguidas para resolver um problema"
> 
> - "Algoritmos são conjuntos de passos finitos e organizados que, quando executados resolvem um determinado problema"

#### Quando os algoritmos devem ser criados ?

> "Sempre que queremos montar uma sequência de passos necessários para solucionar um problema"

# PSEUDOCÓDIGO

**Problema 1 -** *valor por hora trabalhada do funcionário.*

> - **input** : palavra usada para receber dados do usuário
> 
> - **print** : exibit algo na tela
> 
> - **if** : condição que controla se algo deve ou não ser feito
> 
> - **else** : cláusula a ser executada caso nenhua condicional **if** seja executada
> 
> - **loop de x a y** : laço de repetição que irá iterar de **x a y** 
> 
> - **loop x em y** : laço de repetição que irá iterar **x em uma coleção y** 
> 
> - **while x** : laço de repetição que acontecerá enquanto uma condição for verdadeira

                   

                  ***input*** *salario_mensal*

                        ***input***  *horas_trabalhadas_por_mes*

                ***Variavel*** = *valor_hora = salario_mensal / horas_trabalhadas_por_mes*

                    ***print***  *valor_hora* 

# EXERCICIO EM PORTUGOL

> ***algoritmo*** "TRIANGULOS"
> 
>  ***var***
>    L1, L2, L3: real
>    EQ, ES : logico
> ***inicio***
>     Escreva ("Digite o valor do primeiro lado: ")
>     Leia (L1)
>     Escreva ("Digite o valor do segundo lado: ")
>     Leia (L2)
>     Escreva ("Digite o valor do terceiro lado: ")
>     Leia (L3)
>     EQ<- (L1 = L2) E (L2 = L3)
>     EscrevaL ("O triangulo é equilátero", EQ)
>     ES<- (L1 <> L2) e (L2 <> L3) e (L1 <> L3)
>     EscrevaL ("O triangulo é escaleno", ES)
> 
> ***finalgoritmo***
