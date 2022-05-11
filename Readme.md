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

> algoritmo "AlunoMédia"
> 
> var
> 
>     N1 , N2 , MEDIA :  Real
> 
> inicio
> 
>     Escreva ("Primeira nota: ")
> 
>     Leia (N1)
> 
>     Escreva ("Segunda nota: ")
> 
>     Leia (N2)
> 
>     MEDIA <- (N1 + N2)  /  2
> 
>     EscrevaL ("A média foi :  " , MEDIA : 4:2 )
> 
>     Se ( MEDIA >= 5 ) entao
> 
>             EscrevaL ("O ALUNO ESTÁ APROVADO")
> 
>     Senao
> 
>             Se  ( MEDIA >= 5 ) entao
> 
>                     EscrevaL ("O ALUNO ESTÁ DE RECUPERAÇÃO")
> 
>             Senao
> 
>                     EscrevaL ("O ALUNO FOI REPROVADO")
> 
>         
> 
>             Fimse
> 
>        Fimse
> 
> fimalgoritmo



# GIT E GITHUB

*"Git é um sistema de versionamento de arquivos, e GitHub é uma plataforma digital aonde esses arquivos podem ser compartilhados com outros devs."*

## PROMPT de Comando

> **1 - Windows / 2 - Linux** 
> 
> mostrar em lista as pastas e diretórios -  **dir : ls**      
> 
> entrar no diretório principal do computador - **cd / : cd /**   
> 
> **cd** + arquivo / - entrar pasta expecifica 
> 
> voltar para pasta anterior - **cd ..**
> 
> limpar as informações na tela - **cls / clear ou Ctrl + L**
> 
> **Tab** - autocompleta palavras conhecidas pelo sistema 
> 
> criar pasta no dentro diretório atual - **mkdir + nome**
> 
> print texto na tela - **echo**
> 
> criar arquivo de texto - **echo + texto > nome + formato**
> 
> apaga pastas e arquivos dentro do diretório - **del + arquivo / pasta** (apenas no Windows)
> 
> apagar todo o diretório - **rmdir + pasta / arquivo + /S /Q** 
> 
> apagar no **Linux** - **rm -rf + pasta / arquivo /**
> 
> voltar aos comandos já utilizados - **seta para cima**

# COMANDOS PARA CRIAR REPOSITÓRIO NO GIT E GITHUB

> - **branch -** é uma ramificação da linha principal
> 
> - **commit -** são uma forma de salvar o estado atual do arquivo
> 
> - **merge** - mesclar duas ou mais **Branch** em uma nova
> 
> - **remote -** arquivos armazenados no sistema remoto 
> 
> - **push -** pega os arquivos e manda para o repositório remoto
> 
> - **pull -** puxar os arquivos do GitHub para o repositório local
>   
>   - **git init -** inicia o repositório na pasta, cria também a pasta oculta **.git**
>   
>   - **git add + arquivo / pasta -** manda os arquivos para **"staging"** 
>   
>   - **git status -** mostra detalhes do repositório
>   
>   - **git commit -m + "texto" -**  criar o commit para mandar para o GitHub
>   
>   - **git branch -m "main" -** trocar o nome da branch **master** para **main** 
>   
>   - **git remote add origin "link.git.https" -** adicionar um **"link"** entre o repositório local e o remoto
>   
>   - **Shift + insert -** cola o arquivo copiado no **Git Bash** ( **Ctrl V** não funciona )
>   
>   - **git push -u origin main -** leva os arquivos para o repositório do GitHub 
