# Avaliação
 
* 2 provas de 30 pontos e uma prova de 27 pontos (87 pts) - Prova I 14/4/25, Prova II 26/5/25, Prova III 3/7/25
* Trabalhos (10 pontos - serão cobrados na prova - Trabalho em Grupo mas a arguição é individual)
    * Simulador Tomasulo em Python 3 pontos - 24/4/25 - [Especificação Video](https://www.youtube.com/watch?v=wXvhKRUkJq4&list=PLcvOyD_LMr6nZYSK4Dfr7b55qBRUgxJXV&index=7) e [Colab](https://colab.research.google.com/drive/1YHrcZgxybtBlIu6SW-BQZRux1MpRfN6T?usp=sharing). Enviar email para agendar a apresentação do Grupo.
    * Simulador Cache 4 Way 5 pontos - 6/6/25 - [Colab base](https://colab.research.google.com/drive/11StANB9MMLfcuuqtwbZMe9MbUNz48NOs?usp=sharing) e [Explicações para fazer o trabalho - video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mCZoxo2plWQGRiA_GI9rye)
    * Simulador Arquiteturas Paralelas 2 pontos - 30/6/25 [Colab Trabalho 3](https://colab.research.google.com/drive/1P2lJGYkuZW_tU-M_D_S3gCTdhNSEBL6T?usp=sharing) e [explicações para fazer o trabalho](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kcLkHwzOfX6AcPkFsAG5YF) e link para [enviar aqui](https://forms.gle/63ofcey3kpkJWRJb9)
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

## Aula 6 27/3/25 - Predição de Desvios (síncrona) [gravação da aula](https://drive.google.com/file/d/1C0GhhnyfdHWuANuKWyHlDiyOFV1VpFe5/view?usp=sharing)
* [Simulador de Preditor Dinâmica para fazer a correção](https://colab.research.google.com/drive/19ffbZEbwlhMq95FpKd1S1TaN4IZcE-Yx?usp=sharing)
* [NOVO ! playlist de video separado](https://www.youtube.com/playlist?list=PLcvOyD_LMr6nuoeBKHtTPUWAR4tTiI1Fr)
  
## Aula 7 31/3/25 - Superscalar, VLIW  (assíncrona)
* [Aula com as dicas para fazer o exercício 2](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kFiUbMsrqcF0BR_-L5Hp8S)
* [exercicio para entregar em papel, escrito a mão](https://docs.google.com/document/d/1LkOcmb5JF6cJj34Zog1XTgs2I4KWLS1foS_CLlfQQIU/edit?usp=sharing) - Entregar até 7 de Abril no escaninho da secreatria do DPI.
## Aula 8 03/4/25 - Assembler PTX da GPU e escalonamento estático (assíncrona) - Não é matéria da prova 1 (só prova 3)
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
* Vídeos estão na aula anterior.
## Aula 11 14/4/25 - Prova I (semana santa/tiradentes)
* Prova no Auditorio II do PVB, lista de GPU será para prova 3. GPU não será cobrado na prova 1.
## Aula 12 24/4/25 - Introdução as Caches e seus tipos [play list da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mAsSf8X1e2bDfz2cxHAqwE)
* [Colab com material teórico para Caches](https://colab.research.google.com/drive/1n2YcCXjPS0bZqhncxPiVg8nnOUv9A_4r?usp=sharing)
## Aula 13 28/4/25 - Implementação de uma Cache em Verilog (trabalho)
## Aula 14 5/5/25  - Continuação da Implementação Caches e Politicas de Substituição  
* [Explicações para fazer o trabalho - video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mCZoxo2plWQGRiA_GI9rye)
## Aula 15 8/5/25  - Tempo, Níveis, Compartilhamento
* [video aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mSIksEPqTVTw2aVHfsxr3q)
* [mesi - protocolo de simulação de cache](https://www.scss.tcd.ie/jeremy.jones/VivioJS/caches/MESIHelp.htm)
## Aula 16 12/5/25 - Memória Virtual e Paginação, 2 Niveis 
* [Playlist Introdução + Exercicio Paginacao 1 nivel, um exemplo de 2 niveis](https://www.youtube.com/playlist?list=PLcvOyD_LMr6l1XmvLXJ7HeQM44wQYr-wV)
## Aula 17 15/5/25 - Paginação em 2 níveis, TLB
* [Colab de Introdução a Memória Virtual](https://colab.research.google.com/drive/1yFMBKIOR94sudsBO0Z3nhZ4xExBITQnx?usp=sharing)
* [Colab com os exercícios para Prova II](https://colab.research.google.com/drive/1ohzBmtaEW1Rgx0zmhMlHg8bBYC2SzkD2?usp=sharing)
## Aula 18 19/5/25 - Revisão  (santa rita)
* [prova 2024](https://docs.google.com/document/d/16YGtPHkZGC75hZjaCi7h12wSKg5GiUZPQTn6tj8bNSc/edit?usp=sharing)
* [prova 2023](https://docs.google.com/document/d/1O81P4sPiwqNEIgymIdEAubdqdjn6q6pPMf10V146leQ/edit?usp=sharing)
## Aula 19 26/5/25 - Prova II - Auditorio do PVB
* [exercicios de revisão para PROVA II](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kOq1Vp66q4rXiG8LOGr5An)
## Aula 20 29/5/25 - [Introdução a GPU](https://www.youtube.com/playlist?list=PLcvOyD_LMr6k2S59XvoMOr2UHICwbfAHb)
## Aula 21 2/6/25  - Maquina Vetorial & Dataflow 
* [Colab de Dataflow](https://colab.research.google.com/drive/1_c1iMekCu21Dddo0ruIXlYIouuy54Bkh?usp=sharing)
* [Colad de Arquiteturas Vetoriais](https://colab.research.google.com/drive/1DVloAhfVcDYnMeB97gHmARMFBJuf7rE6?usp=sharing)
## Aula 22 5/6/25  - Multiprocessadores, Extensões Vetoriais e  Arquiteturas Sistólicas
* [Colab com vários sistólicos: filtro, Matriz 2D e Knn](https://colab.research.google.com/drive/1kJiYnlqIaQryCEpl48o0Eno78bMp_RwC?usp=sharing)
* [Array Processor, Vetorial e Sistólicos](https://colab.research.google.com/drive/1YTPxp2t5KBBlTtdq6ThdgUnS4-u2a2xc?usp=sharing)
* [Multiprocessadores](https://colab.research.google.com/drive/1aXdpEg4TCGCgQJ4mliXYxrYSLS1fqWdl?usp=sharing)
## Aula 23 9/6/25  - Arquiteturas SIMD Array Processors
* [Colab de Array Processors](https://colab.research.google.com/drive/1_2OoAaCe_do0135Q3nDr7wCeBu6go_eQ?usp=sharing)
## Aula 24 12/6/25 - Modelo Programação GPU
* [Playlist Video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6k-jRSG7Mqzdy7lMTiwPeev)
* [Colab Demo](https://colab.research.google.com/drive/1QMRzDW3xsVlvo8kiEnkPDEqftkdTPvOx?usp=sharing)
## Aula 25 16/6/25 - Arquitetura GPU memórias  (corpus)
* [Playlist video Memorias](https://www.youtube.com/playlist?list=PLcvOyD_LMr6ku0YPpJJMWQjKMYlN814eh)
## Aula 26 23/6/25 - Arquitetura GPU multiprocessadores
## Aula 27 26/6/25 - Arquitetura GPU PTX e Registradores 
## Aula 28 30/6/25 - Revisão 
* [playlist video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6khQhwvx9rvlkCmGxOA5jho)
* [prova 2024](https://docs.google.com/document/d/1FXchJlMIZwI7P9RFEMHK-MPH89XY3bGjx8-HnKMLJss/edit?usp=drive_link)
* [prova 2023](https://docs.google.com/document/d/1rCpnwK2b_OJ0UvyDxRptrsamWxd2veiWTQL2g1zYycI/edit?usp=drive_link)
## Aula 29 3/7/25   Prova III no auditório do PVB




