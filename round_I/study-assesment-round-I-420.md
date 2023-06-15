# STUDY ASSESSMENT - ROUND I

Please replace '???' (triple question mark) in form below with respective answers. 
Note that this round doesn't assume deep dive into all datails of the paper materials.
All the answers are supposed to be found within Abstract and Introduction sections if present. 
Otherwise in other sections in skimming mode.


## Meta information

|                                                 |                                                                                        |
| ---                                             |----------------------------------------------------------------------------------------|
| 1. Assessor name                                | `Lev Bagryansky`                                                                       |
| 2. Assessment date (`DD.MM.YYYY`)               | `14.06.2023`                                                                           | 
| 3. Study title                                  | `Java Ranger: statically summarizing regions for efficient symbolic execution of Java` |
| 4. Publication year in format `YYYY`, e.g. 2023 | `2020`                                                                                 |
  
## Has the study raised any issues of Symbolic Execution?

Please examine the paper on the subject of mentioning issues/difficulties/challenges/etc. of Symbolic Execution.
  
5. (Yes/No): `Yes`

If you answered 'Yes' please provide references to the location(s) within the study supporting your answer:  
(add as many list items 5.x as required in format `page No., citation`. Remove unnecessary items)

5.1 `p. 123, Although symbolic analysis is a popular technique, scalability is a
substantial challenge for many applications.`  
5.2 `p. 123, In particular, symbolic
execution can suffer from a path explosion: complex software has
exponentially many execution paths, and baseline techniques that
explore one path at a time are unable to cover all paths.`  
5.3 `p. 124, In addition, many, if not most, Java bytecodes can throw exceptions,
leading to many small, dynamically dispatched fragments of code
with many non-local control jumps. In a naive implementation,
such non-local jumps reduce the size of the path-merged code that
can be created and increase the branching factor for exploration,
leading to poor performance`

## Has the study introduced any new technique within Symbolic Execution field?

Please examine the paper on the subject of mentioning any technique/approach/method related to Symbolic Execution.
  
6. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 6.x as required in format `page No., citation`. Remove unnessesary items)

6.1 `p. 124, We propose Dynamic Method Region Inlining: this allows us
to construct summaries for multi-path regions containing
dynamically dispatched method calls, once types are known.`  
6.2 `p. 124, We propose a technique named Single-Path Cases for splitting
regions into exceptional and non-exceptional outcomes, and
use Dynamic Symbolic Execution for the exceptional cases`  
6.3 `p. 124, We propose Early-Returns Summarization to collapse multiple returns into a disjunctive-conditional returned-expressions.`

## Has the study suggested any formal or informal proof of the limitations mentioned?

Please examine the paper on the subject of mentioning any description or references to
formal or empirical proof justifying any of Symbolic Execution problems.
  
7. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 7.x as required in format `page No., citation`. Remove unnessesary items)

7.1 `p. 130, We evaluated the performance of Java Ranger using the
nine benchmarking programs presented in Table 1.`  
7.2 `p. 130, JR achieves a total reduction of 38% and 71% reduction in total
running time and number of execution paths respectively across
all benchmarks. It also achieves an average of 63% reduction in
the number of solver queries.`  
7.3 `p. 130 JR reduces the number of execution paths by about 88% in replace but incurs an increase in execution time by 187%. The 67.3%
reduction in the number of solver queries causes a 240% increase
in solver time spent by JR`

## List of paper references which contain phrase "symbolic execution" in title and are not presented in the list of primary studies
(add as many list items 8.x as required. Remove unnessesary items)

8.1 `[5] Roberto Baldoni, Emilio Coppa, Daniele Cono D’elia, Camil Demetrescu, and Irene
Finocchi. 2018. A Survey of Symbolic Execution Techniques. ACM Comput. Surv.
51, 3, Article Article 50 (May 2018), 39 pages. https://doi.org/10.1145/3182657`  
8.2 `[10] Lori A. Clarke. 1976. A System to Generate Test Data and Symbolically Execute
Programs. IEEE Trans. Software Eng. 2, 3 (1976), 215ś222. https://doi.org/10.1109/
TSE.1976.233817`  
8.3 `[16] Trevor Hansen, Peter Schachte, and Harald Sùndergaard. 2009. State Joining
and Splitting for the Symbolic Execution of Binaries. In Runtime Verification,
Saddek Bensalem and Doron A. Peled (Eds.). Springer Berlin Heidelberg, Berlin,
Heidelberg`