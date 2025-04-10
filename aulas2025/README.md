# Avaliação
 
* 2 provas de 30 pontos e uma prova de 27 pontos (87 pts) - Prova I 14/4/25, Prova II 26/5/25, Prova III 3/7/25
* Trabalhos (10 pontos - serão cobrados na prova - Trabalho em Grupo mas a arguição é individual)
    * Simulador Tomasulo em Python 3 pontos - 24/4/25 - [Especificação Video](https://www.youtube.com/watch?v=wXvhKRUkJq4&list=PLcvOyD_LMr6nZYSK4Dfr7b55qBRUgxJXV&index=7) e [Colab](https://colab.research.google.com/drive/1YHrcZgxybtBlIu6SW-BQZRux1MpRfN6T?usp=sharing). Enviar email para agendar a apresentação do Grupo.
    * Simulador Cache 4 Way 5 pontos - 19/5/25
    * Simulador Dataflow 2 pontos - 30/6/25
* Lista : [Software Pipeline](https://docs.google.com/document/d/1AhvrvgKKYBrJtgPooiA9RNMaadFP4_JSf-UkPeNDDy0/edit?usp=sharing), [Superescalar/VLIW](https://docs.google.com/document/d/1akJ7_g7bifrVumRnE0-qTSy5bnroo33RFNoGtkFpQr4/edit?usp=sharing) e PTX (1 ponto cada) - Individual e escrita a mão.
# Referências
* [apostilas]()
* [Computer Organization and Design MIPS (or RiscV) Edition: The Hardware/Software Interface 5th Edition](https://www.amazon.com/Computer-Organization-Design-MIPS-Architecture/dp/0124077269)

# Cronograma de Aulas

## Aula 1 10/3/25 - Multiplas Unidades Funcionais [videos](https://www.youtube.com/playlist?list=PLcvOyD_LMr6lE-dC0VJ2V-TjCt3Bea1Tl)
* [slides Multiplas unidades, Unrolling, Soft Pipelining e Escalonamentos](https://docs.google.com/presentation/d/14wxD1nXVCHVqidB4S4sbar_OGkiAhkooeNXDyEL-RZ8/edit?usp=sharing)
* Exemplos da [aula com colab](https://colab.research.google.com/drive/1zhO5TzSEAy0P_EKT5oNtp_BR0lg-ZZhO?usp=sharing)
* [Exercicio 1](https://docs.google.com/document/d/1Ib10ajsfOkAV2flKp2jx3ZnB1YXGRCnuYECg1935kz0/edit?usp=sharing)

## Aula 2 13/3/25 - Loop Unroolling e Escalonamento Estático [video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6m9kKfCRkj-9wzfwVZfUL8G) 
* [exemplos: unroll](https://docs.google.com/document/d/1VbJ5KoNpPBL990Hxp9_J4r0wJ1ThuCHeWmGWwinRLhQ/edit?usp=sharing)
* [colab com "emulação" em python](https://colab.research.google.com/drive/1VXYg4UgnspfATiabb-CAkvkoII4IO0Nn?usp=sharing)

## Aula 3 17/3/25 - Software Pipelining (assíncrona) [Clique Aqui para Assistir a aula e fazer os dois exercicios, aqui tem os vidoes da aula presencial com as dicas para a lista](https://www.youtube.com/playlist?list=PLcvOyD_LMr6k9xqFEfsVTfc1lOYyww07u)
* Slides Software Pipelining [Weac 2023](https://docs.google.com/presentation/d/176eY8fTNS0xd_VzsCKBBNn9xbN_dEvwVTR5h3ibtDns/edit?usp=sharing)
* Artigo [weac 2023 - Ensino de Software Pipelining e Escalonamento em GPUs com Python](http://www2.sbc.org.br/ceacpad/ijcae/v12_n2_dec_2023/IJCAE_v12_n2_dez_2023_paper_3_vf.pdf)
* [Colab indice do Artigo Weac 2023](https://colab.research.google.com/drive/1zpyc25cTdNnPoqY07MVJd6Cpcpm7_L9e?usp=sharing)
* [Software Pipelining com 2 exemplos](https://colab.research.google.com/drive/1oeHtya06AMZBuPofLHvckZfkf8Q1DMX1?usp=sharing) 
* [Exercicios para treino](https://docs.google.com/document/d/1iMePpBllLPABsJtC3P1knk6QhF9Mo2XuHR_l24cL4lw/edit?usp=sharing)
* [Exemplos resolvidos](https://docs.google.com/document/d/1J-BHI6DYczwqqI01_H-GWNVTFY-30ll7dSgDrcagcH0/edit?usp=sharing)

## Aula 4 20/3/25 - Tomasulo (síncrona) [gravação da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6nZYSK4Dfr7b55qBRUgxJXV)
*  Escalonamento dinamico  ---- [simulador 1 com 10 exemplos](https://arthurmteodoro.github.io/tomasulo-simulator/index) ----- [simulador 2](https://naheel.xyz/tomasulo-sim/)  
* Folha de exercicios da [aula revisão escalonamento dinamico e multiplas unidades](https://docs.google.com/document/d/1S4xz6zUmKN1bZ77NH3JbNzx_O8Y4sMX9dPjFn9ZOfwY/edit?usp=sharing) mais outros [exercicios para treino da aula 20 marco](https://docs.google.com/document/d/1XX8jwdupN82-9vPxbYTiQcUnzMKQrkeWdalP_eUpi6A/edit?usp=sharing) mais sugestões de [exercicio para treino](https://docs.google.com/document/d/1W19ofIvCMIcWTam78DMwOXRO555nKc80cljbKpRJyCk/edit?usp=sharing)
* [exemplos com resposta para as tecncias anteriores, pode usar o mesmo exemplo no trabalho do Tomasulo, resolvendo com escalonamento dinamico](https://docs.google.com/document/d/11Kep0l6_UFheh5b5t3N8kaGj2hApEXlM3LkGB5kCNxM/edit?usp=sharing)
* [consultar o livro Quantitative Approach para teoria do Tomasulo](https://acs.pub.ro/~cpop/SMPA/Computer%20Architecture%20A%20Quantitative%20Approach%20(5th%20edition).pdf)

## Aula 5 24/3/25 - Predição de Desvios (síncrona)
* [playlist video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6n5ck1Wte2asogGWCSok3gP)
* Entregar a lista de exercícios de Software Pipeline (1 ponto)
* [Colab de Predição de Desvios](https://colab.research.google.com/drive/1H2an9LBEouzM9V81U9PHCeX1GZwTItLU?usp=sharing)

## Aula 6 27/3/25 - Predição de Desvios (síncrona)
* [Simulador de Preditor Dinâmica para fazer a correção](https://colab.research.google.com/drive/19ffbZEbwlhMq95FpKd1S1TaN4IZcE-Yx?usp=sharing)
* [2 exercícios para treino - Ainda não atualizado]()
  
## Aula 7 31/3/25 - Superscalar, VLIW  (assíncrona)
* [Aula com as dicas para fazer o exercício 2](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kFiUbMsrqcF0BR_-L5Hp8S)
* [exercicio para entregar em papel, escrito a mão](https://docs.google.com/document/d/1LkOcmb5JF6cJj34Zog1XTgs2I4KWLS1foS_CLlfQQIU/edit?usp=sharing) - Entregar até 7 de Abril no escaninho da secreatria do DPI.
## Aula 8 03/4/25 - Assembler PTX da GPU e escalonamento estático (assíncrona)
* [playlist de vídeo](https://www.youtube.com/playlist?list=PLcvOyD_LMr6keaqk5T7drV1ZGEgskxh4X)
* [lista de exercício de gpu](https://docs.google.com/document/d/1JzC20YiTkD8YZ9OdaNK9XbN9_fSrqfMTHjQRjk7B0gY/edit?usp=sharing)
* [Versão com html](https://colab.research.google.com/drive/1fX8K21hhJmUPXzzq52dTpDeCij8Sn5ys?usp=sharing)
* [Versao com coresII](https://colab.research.google.com/drive/1_hiw_MjPfFuVj_IDFSJ_BE9PZufjku9d?usp=sharing)


## Aula 9 07/4/25  - Revisão 
* [Gravações dos vídeos da revisão com Exemplos de questoes de Prova](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kWR7OxKKXbG8oE-xUCxpw4)
* [Prova 2024](https://docs.google.com/document/d/1Q4jr7J6BSF0E9BpHFA8H5aLt1y2GEU8ImUqdaximUD4/edit?usp=sharing)
* [Prova 2023](https://docs.google.com/document/d/1HKhF6WCDqGJV9DjXn4wobdmdpJ93QTWRy9bvmrsTdMk/edit?usp=sharing)
* [Resumo da Prova - anotações](https://docs.google.com/document/d/1NmfZrIL31t1U1210UR1GrP7WysAOxULVDxHoVG5CrmM/edit?usp=sharing)

* Prazo final para lista VLIW/GPU, devolver na aula.
## Aula 10 10/4/25 - Revisão
## Aula 11 14/4/25 - Prova I (semana santa/tiradentes)
* Prazo Final para lista de GPU
## Aula 12 24/4/25 - Introdução as Caches e seus tipos
## Aula 13 28/4/25 - Implementação Caches  (trabalho)
## Aula 14 5/5/25  - Implementação Caches e Politicas de Substituição  
## Aula 15 8/5/25  - Tempo, Níveis, Compartilhamento
## Aula 16 12/5/25 - Memória Virtual e Paginação
## Aula 17 15/5/25 - Paginação em 2 níveis ou mais
## Aula 18 19/5/25 - TLB e Revisão  (santa rita)
## Aula 19 26/5/25 - Prova II
## Aula 20 29/5/25 - Dataflow 
## Aula 21 2/6/25  - Maquina Vetorial
## Aula 22 5/6/25  - Multiprocessadores e Extensões Vetoriais
## Aula 23 9/6/25  - Arquiteturas SIMD
## Aula 24 12/6/25 - Arquiteturas Sistólicas
## Aula 25 16/6/25 - Arquitetura GPU memórias  (corpus)
## Aula 26 23/6/25 - Arquitetura GPU multiprocessadores
## Aula 27 26/6/25 - Arquitetura GPU PTX e Registradores 
## Aula 28 30/6/25 - Revisão 
## Aula 29 3/7/25   Prova III






--------------------------------------------------------

Anos Anteriores

-------------------------------------------------------
   
---

### Aula  11/3 Loop Unrolling, escalonamento estático, Software Pipelining



---   
### Aula 14/3 
* [gravacao da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kiYKUxTg9ZAY4bg2zGuWom)
*  Escalonamento dinamico [exemplos](https://docs.google.com/document/d/11Kep0l6_UFheh5b5t3N8kaGj2hApEXlM3LkGB5kCNxM/edit?usp=sharing) ---- [simulador 1 com 10 exemplos](https://arthurmteodoro.github.io/tomasulo-simulator/index) ----- [simulador 2](https://naheel.xyz/tomasulo-sim/)  
* Folha de exercicios da [aula revisão escalonamento dinamico e multiplas unidades](https://docs.google.com/document/d/1S4xz6zUmKN1bZ77NH3JbNzx_O8Y4sMX9dPjFn9ZOfwY/edit?usp=sharing) mais outros [exercicios para treino](https://docs.google.com/document/d/1JEj7AfNjVGiLLP3w6dl_SSQEhomq2xYt8P81Bw6uPvI/edit?usp=sharing) mais sugestões de [exercicio para treino](https://docs.google.com/document/d/1W19ofIvCMIcWTam78DMwOXRO555nKc80cljbKpRJyCk/edit?usp=sharing)

-----

### Aula 18/3

* [Colab com exercícios de predição de desvios](https://colab.research.google.com/drive/1dfPUIWJB6WHXB4FSGvIvu7paOGFJ3hdg?usp=sharing)
*  Slides da apresentação para [implementação do preditor desvio MIPS WEAC](https://docs.google.com/presentation/d/1NoKyJ3UC34Rj6trYvjSHXAwF48wRzG9937nkRR48AnM/edit?usp=sharing)
*   [artigo com implementação do preditor ](https://drive.google.com/file/d/1OwYKriZ7ZO-vyjqkrxkEaGVxqul_YnwH/view?usp=sharing)]
*   [gravação da aula, parte da aula está no trabalho 2 (acima)](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mtGYVX9y5Dng7JA207IxHA)

---
#### Material adicional
* [playlist de video da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kY5VOzsPdB5Iqgsh40meuL)- Material do PEO para [Implementação do Preditor de Desvio](https://github.com/arduinoufv/inf450_peo/blob/master/semana/semana2.md#24-implementa%C3%A7ao-de-desvio-dinamico) e Material do Curso de [2021](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kyUihym8cOfDeSV4b4JdqK)

### Aula 21/3

* Elaboração de mais exemplos para trabalho 2 e atualização do [Colab com exercícios de predição de desvios](https://colab.research.google.com/drive/1dfPUIWJB6WHXB4FSGvIvu7paOGFJ3hdg?usp=sharing)
* [gravação de exemplos de calculo de CPI com desvios](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mEdSa3WbYflu2p2-SqGQj2)

### Aula 25/3
* [Motivação com experimentos](https://johnnysswlab.com/how-branches-influence-the-performance-of-your-code-and-what-can-you-do-about-it/#experiments)
* Ślides [preditores estáticos e dinâmicos](https://docs.google.com/presentation/d/1Fd3ZL187-p5zRFGn-lhfRlMppTzJG_d7Tvhq5uCU2mM/edit#slide=id.p51)
* [slides ETH](https://safari.ethz.ch/digitaltechnik/spring2021/lib/exe/fetch.php?media=onur-digitaldesign_comparch-2021-lecture17b-branch-prediction-i-afterlecture.pdf)
* [website of COMP3710 Special Topics course on Computer Microarchitecture](https://comp.anu.edu.au/courses/comp3710-uarch/assets/lectures/week5-part1.pdf)
* [Andre Seznec](https://team.inria.fr/alf/members/andre-seznec/branch-prediction-research/)
* [paper RNN branch preditor](https://cseweb.ucsd.edu/~atsmith/rnn_branch.pdf)

### Aula 1/4

### Aula 4/4 
* Revisão para Prova: Múltiplas Unidades, Loop Unrolling, Software Pipeline, Escalonamento Dinâmico, Superscalar, VLIW, Escalonamento em GPU, Predição de Desvio

### PROVA 1 8/4

### Aula 8/7 - Introdução a Cache
* [Tempo médio de acesso, Localidade Temporal e Espacial, Tipos de Cache playlist video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mWgCQPrPFnk3QVQCXTWIpX)
* [Colab com material teórico para Caches](https://colab.research.google.com/drive/1n2YcCXjPS0bZqhncxPiVg8nnOUv9A_4r?usp=sharing)

### Aula 11/7 - Simulador de Tipos de Cache e Politicas
* [Escrita e Substituição em Cache](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mBZbqqdc4Jj6b1bJClQnX3)
* [Colab do Trabalho 3](https://colab.research.google.com/drive/1bcJqZtCyqEoQvze2O5SJpIA84d6mLYX2?usp=sharing)

### Aula 15/7 - Memória Virtual e Paginação
* [Colab de Introdução a Memória Virtual](https://colab.research.google.com/drive/1yFMBKIOR94sudsBO0Z3nhZ4xExBITQnx?usp=sharing)
* [Playlist da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6neZ2mL7EUe50dxEqcm__pF)
### Aula 18/7 - Paginação em 2 Níveis e TLB
* [Exercícios de Memória Virtual (em manutenção)](https://colab.research.google.com/drive/1ohzBmtaEW1Rgx0zmhMlHg8bBYC2SzkD2?usp=sharing)
### Aula 22/7 - Segmentação e Introdução a Memória de GPU
### Aula 25/7 - GPU: Registros, Global, Cache, Compartilhada, Constante,Textura e Atômico
### Aula 29/7 - Revisão Cache e Virtual e GPU
### Aula 1/8 - Revisão: Cache, Virtual e GPU 
### Prova 2 - 5/8
### 8/8 - 
 #### [knn video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6k9AF53ZYVJW06ulOofJxz8) e [Colab](https://colab.research.google.com/drive/1beqQ1hFYReaCydp3RthAReK7PrmQqH2w?usp=sharing)
 #### [Introducao a GPU](https://www.youtube.com/playlist?list=PLcvOyD_LMr6m4_ze2EIJiG33kFHUXvxsV)
 #### [Colab de Introdução a GPU](https://colab.research.google.com/drive/1A9hGdkwqPrdzWcd339aeCd2uQ55DM6vg)
### 12/8 - [MMX, AVX e Processadores Vetoriais](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mCIFhWypzBmXAlktrLtSiY) 
### 15/8 - [Array Processors](https://www.youtube.com/playlist?list=PLcvOyD_LMr6nvab9q-FU68K9InStRnsBi)
### 19/8 - Dataflow
### 22/8 - [Sistólico playlist da Aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6lKw1ms9oN4oFT6nqQbbdOr), [tensor cores na GPU](https://developer.nvidia.com/blog/programming-tensor-cores-cuda-9/)
### 26/8 - GPU redução, desvios
### 29/8 - GPU e aprendizado de máquina
### 2/9 - [Revisão](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mFyP3-0l-mxfsetMey_hAj) e [colab](https://colab.research.google.com/drive/1YTPxp2t5KBBlTtdq6ThdgUnS4-u2a2xc?usp=sharing)
### 5/9 - Prova 3

