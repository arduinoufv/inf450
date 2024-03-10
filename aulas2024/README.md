# Aulas 2024

## Avaliação

* 3 provas (80 pontos): Prova 1 (30 pontos) data 8/4/24, Prova 2 (30 pontos) data 13/5/24, Prova 3 ( 20 pontos) data 24/6/24
* trabalhos (20 pontos):
    * Software Pipeline (1 ponto)
    * Predição Desvio (4 pontos)
    * Cache Emulador (1 ponto)
    * Cache Maquina Estados (4 pontos)
    * Multiplicador Matriz Esparsa ( 5 pontos)
    * KNN GPU ( 5 pontos)
## Referências

## Cronograma de Aulas

1.  [4/3 Apresentação do Curso - Slides ](https://docs.google.com/presentation/d/1_LykWtdGVN7RCOvt1C8jXhd5BZuPTYUz1-FzViksB7w/edit?usp=sharing)
   - Gravação da aula [Playlist (sem som...vou ver como resolver)](https://www.youtube.com/playlist?list=PLcvOyD_LMr6miSfrLNHoPpu04j_utvQsE)
     
## Parte I Processador 
### Aula 7/3 Múltiplas Unidades Funcionais 

[slides](https://docs.google.com/presentation/d/14wxD1nXVCHVqidB4S4sbar_OGkiAhkooeNXDyEL-RZ8/edit?usp=sharing), exemplos da [aula com colab](https://colab.research.google.com/drive/1zhO5TzSEAy0P_EKT5oNtp_BR0lg-ZZhO?usp=sharing) - [gravação da aula  (sem som...vou ver como resolver)](https://www.youtube.com/playlist?list=PLcvOyD_LMr6nFp5YHAOmOaS5umpZnTAun) exemplos: [exercicio 1](https://docs.google.com/document/d/1Ib10ajsfOkAV2flKp2jx3ZnB1YXGRCnuYECg1935kz0/edit?usp=sharing)

---

### Aula  11/3 Loop Unrolling, escalonamento estático, Software Pipelining

* [slides](https://docs.google.com/presentation/d/14wxD1nXVCHVqidB4S4sbar_OGkiAhkooeNXDyEL-RZ8/edit?usp=sharing), [exemplos: unroll](https://docs.google.com/document/d/1VbJ5KoNpPBL990Hxp9_J4r0wJ1ThuCHeWmGWwinRLhQ/edit?usp=sharing)  [colab com "emulação" em python](https://colab.research.google.com/drive/1VXYg4UgnspfATiabb-CAkvkoII4IO0Nn?usp=sharing)

* Software Pipelining da aula com 2 exemplos + [colab com a execucao](https://colab.research.google.com/drive/1oeHtya06AMZBuPofLHvckZfkf8Q1DMX1?usp=sharing) 

---   

6. 14/3 Software Pipelining da aula com 2 exemplos + [colab com a execucao](https://colab.research.google.com/drive/1oeHtya06AMZBuPofLHvckZfkf8Q1DMX1?usp=sharing) dos exemplos e alguns [exercicios para treino](https://docs.google.com/document/d/1iMePpBllLPABsJtC3P1knk6QhF9Mo2XuHR_l24cL4lw/edit?usp=sharing) - [exemplos resolvidos](https://docs.google.com/document/d/1J-BHI6DYczwqqI01_H-GWNVTFY-30ll7dSgDrcagcH0/edit?usp=sharing)
7. 18/3   Escalonamento dinamico [exemplos](https://docs.google.com/document/d/11Kep0l6_UFheh5b5t3N8kaGj2hApEXlM3LkGB5kCNxM/edit?usp=sharing) ---- [simulador 1 com 10 exemplos](https://arthurmteodoro.github.io/tomasulo-simulator/index) ----- [simulador 2](https://naheel.xyz/tomasulo-sim/)
8. 21/3 Folha de exercicios da [aula revisão escalonamento dinamico e multiplas unidades](https://docs.google.com/document/d/1S4xz6zUmKN1bZ77NH3JbNzx_O8Y4sMX9dPjFn9ZOfwY/edit?usp=sharing) mais outros [exercicios para treino](https://docs.google.com/document/d/1JEj7AfNjVGiLLP3w6dl_SSQEhomq2xYt8P81Bw6uPvI/edit?usp=sharing) mais sugestões de [exercicio para treino](https://docs.google.com/document/d/1W19ofIvCMIcWTam78DMwOXRO555nKc80cljbKpRJyCk/edit?usp=sharing)
9. 25/3 Slides da apresentação para desvios [WEAC](https://docs.google.com/presentation/d/1NoKyJ3UC34Rj6trYvjSHXAwF48wRzG9937nkRR48AnM/edit?usp=sharing) Alguns exercícios em construção no [colab](https://colab.research.google.com/drive/1dfPUIWJB6WHXB4FSGvIvu7paOGFJ3hdg?usp=sharing)
10. [13/4] Implementacao do Preditor de Desvio [artigo com implementação do preditor ](https://drive.google.com/file/d/1OwYKriZ7ZO-vyjqkrxkEaGVxqul_YnwH/view?usp=sharing), slides da apresentação [WEAC](https://docs.google.com/presentation/d/1NoKyJ3UC34Rj6trYvjSHXAwF48wRzG9937nkRR48AnM/edit?usp=sharing) + [playlist de video da aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kY5VOzsPdB5Iqgsh40meuL)- Material do PEO para [Implementação do Preditor de Desvio](https://github.com/arduinoufv/inf450_peo/blob/master/semana/semana2.md#24-implementa%C3%A7ao-de-desvio-dinamico) e Material do Curso de [2021](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kyUihym8cOfDeSV4b4JdqK)

11. [18/4] Revisão Prova 1 [Multiplas Unidades, Unroll e Software Pipeline](https://www.youtube.com/playlist?list=PLcvOyD_LMr6lvn_wC_KJBNxMkouDPfSEY) e [Colab interativo](https://colab.research.google.com/drive/1D4t6FIDFG53A0IDi4hVftWt1IjuZBYJe?usp=sharing) - Pasta com várias [provas](https://drive.google.com/drive/folders/1ypruNWlIt7wZmCbiMuIsOE--XXmfTlFW?usp=sharing): Tem questões com MIPS (semelhantes a RISCV) e as questões de software pipelining não incluem balanceamento.
12. [20/4] Aula [ETH Prof. Onur, Execucao Fora de Ordem](https://youtu.be/AhtIrJNSQws)
13. [24/4] Revisao
14. [27/4] Prova I - **ATENÇÂO PVA, PVA**...PVA 277
15. [4/5]  [Cache e Tipos](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kXe1ov2pKVgZAY_HemWrCI) e [Colab](https://colab.research.google.com/drive/1EBcmbqwhJYq17t9Z9XXHUXhDzC_ER3C1?usp=sharing)
16. [8/5]  [Calculo de Custo dos tres tipos de cache e sequencia de acesso](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mBui1oFPC7Aq3q7_dNrjBx)
17. [11/5] [Projeto de Cache](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kDv1GhR8eLMkzxwKzXGDvo) 
     * [Trabalho com Valgrind](https://www.youtube.com/playlist?list=PLcvOyD_LMr6k4DCosr9i5zlxGcpn2ZEB-) - [Colab do trabalho](https://colab.research.google.com/drive/180L9FGEtb_tdiVCG8KC8xHwM8YbdED-n?usp=sharing)
     * [Exercicio de calculo dos campos de endereçamento de cache](https://www.youtube.com/playlist?list=PLcvOyD_LMr6ltCswpJJRnzLmMoHnzPtNO) 
18. [15/5] [Colab com Projeto de Cache - 4 pontos](https://colab.research.google.com/drive/1gmnfeqsi-miA8MIGxB5Fnwx4-4YlESfB?usp=sharing) e [playlist com explicacoes](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kDv1GhR8eLMkzxwKzXGDvo)
19. [18/5] [Trabalho 1 de GPU exemplo de pipeline com Warp 4](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mH7Z_2fBoihUdprWn8vMwC) e [colab](https://colab.research.google.com/drive/1VXbM1N26nDHAuJRaHPfvhxhwSLQ6A0ZL?usp=sharing)
20. [25/5] [Trabalho 2 de GPU Gerador de Código para Kmeans com uso de registradores e Shared](https://www.youtube.com/playlist?list=PLcvOyD_LMr6ksGBHUdku-T5PEATDaSoUt)
21. [29/5] [Memoria Virtual e Paginacao](https://colab.research.google.com/drive/1yFMBKIOR94sudsBO0Z3nhZ4xExBITQnx?usp=sharing) e [playlist de video](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kmDWdSDxut5b9tiGGQmShN)
22. [1/6]  [Paginacao em 2 niveis](https://www.youtube.com/playlist?list=PLcvOyD_LMr6m0Y0VWa3-WVEPweD_WVGHf)
23. [5/6] Paginacao e Segmentacao + TLB e [revisao para Prova 2 playlist](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kbiw55_AEups4QkdHmnnCW)
24. [12/6] Revisao - **Considerar ponteiros 1 byte, iremos considerar de 1,2 ou 4 bytes em 2023**
    * [prova 2017 - parcialmente resolvida](https://docs.google.com/document/d/1vNQ8rBP9eO_DR46n3OHDM1eiyWYPYLqhUNnTPLFhxUI/edit?usp=sharing)
    * [prova 2018 - parcialmente resolvida](https://docs.google.com/document/d/1GnXvFZty9qmiLOXlLJjiL45b0sRnOiopVUkGW1ijkmY/edit?usp=sharing)
    * [prova 2019](https://docs.google.com/document/d/1FXlvwP3eP_mYe7Cq-6rv3OvqieQeDpqpXwHXS9htp1Y/edit?usp=sharing)
    * [prova 2022 - parcialmente resolvida](https://docs.google.com/document/d/1YuPwcR1I4XObY9WYr3lx2N-Qb_9RZfOUlXPi7gCHzfs/edit?usp=sharing)
    * [**COLAB** para treinar as questões de memória Virtual](https://colab.research.google.com/drive/1rJG96TvqEgK6h8YKWTdIXcw5DGYTgHmC?usp=sharing)
    * [Cache e Tipos](https://www.youtube.com/playlist?list=PLcvOyD_LMr6kXe1ov2pKVgZAY_HemWrCI) e [Colab](https://colab.research.google.com/drive/1EBcmbqwhJYq17t9Z9XXHUXhDzC_ER3C1?usp=sharing)
    * [Calculo de Custo dos tres tipos de cache e sequencia de acesso](https://www.youtube.com/playlist?list=PLcvOyD_LMr6mBui1oFPC7Aq3q7_dNrjBx)
    
25. [15/6] [Dataflow](https://colab.research.google.com/drive/1_c1iMekCu21Dddo0ruIXlYIouuy54Bkh?usp=sharing) 
26. [19/6]  Prova - **Reservamos a sala 201 do PVA para INF 450.**
27. [22/6] GPU [Colab de Introdução a Arquitetura GPU](https://colab.research.google.com/drive/1QMRzDW3xsVlvo8kiEnkPDEqftkdTPvOx?usp=sharing)
28. [26/6] GPU
29. [29/6] GPU
30. [3/7] Array Processors e Maquinas Vetoriais [Questão Teoricas para Prova](https://www.youtube.com/playlist?list=PLcvOyD_LMr6l52AN8m5MbuxSkAus-yJdM)
31. [6/7]  Sistólicos [Questão com Colab](https://colab.research.google.com/drive/1BffB0qFphSnF-YkYuKMTanfnRH8_jqLm?usp=sharing)
32. [10/7] Trabalhos Dúvidas finais
33. [13/7] Prova pva 277
 
