# STUDY ASSESSMENT - ROUND I

Please replace '???' (triple question mark) in form below with respective answers. 
Note that this round doesn't assume deep dive into all datails of the paper materials.
All the answers are supposed to be found within Abstract and Introduction sections if present. 
Otherwise in other sections in skimming mode.


## Meta information

|                                                 |       |
| ---                                             |  ---  |
| 1. Assessor name                                | `Roman Korostinskiy` |
| 2. Assessment date (`DD.MM.YYYY`)               | `03.07.2023` | 
| 3. Study title                                  | `SymTuner: maximizing the power of symbolic execution by adaptively tuning external parameters` |
| 4. Publication year in format `YYYY`, e.g. 2023 | `2022` |
  
## Has the study raised any issues of Symbolic Execution?

Please examine the paper on the subject of mentioning issues/difficulties/challenges/etc. of Symbolic Execution.
  
5. (Yes/No): `Yes`

If you answered 'Yes' please provide references to the location(s) within the study supporting your answer:  
(add as many list items 5.x as required in format `page No., citation`. Remove unnecessary items)

5.1 `p.1, Practical symbolic execution tools have important external parameters (e.g., symbolic arguments, seed input) that critically affect their performance. Due to the huge parameter space, however, manually customizing those parameters is notoriously difficult even for experts.`  
5.2 `p.1, As a consequence, symbolic execution tools have typically been used in a suboptimal manner that, for example, simply relies on the default parameter settings of the tools and loses the opportunity for better performance.`  

## Has the study introduced any new technique within Symbolic Execution field?

Please examine the paper on the subject of mentioning any technique/approach/method related to Symbolic Execution.
  
6. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 6.x as required in format `page No., citation`. Remove unnessesary items)

6.1 `p.1, In this paper, we aim to change this situation by automatically configuring symbolic execution parameters. With SymTuner that takes parameter spaces to be tuned, symbolic executors are run without manual parameter configurations; instead, appropriate parameter values are learned and adjusted during symbolic execution.`  
6.2 `p.2, The key technical contribution is the domain-specific learning algorithm for symbolic execution, which observes the behavior of symbolic execution with randomly sampled parameters and gradually learns to sample effective parameter values.`  

## Has the study suggested any formal or informal proof of the limitations mentioned?

Please examine the paper on the subject of mentioning any description or references to
formal or empirical proof justifying any of Symbolic Execution problems.
  
7. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 7.x as required in format `page No., citation`. Remove unnessesary items)

7.1 `p.2, We applied SymTuner to KLEE [11], a representative symbolic execution tool for C programs, and evaluated it on the latest versions of 12 GNU open-source programs (ranging from 5K to 161K LoC). KLEE with SymTuner covered 56% and 31% more branches on average than conventional KLEE with its default parameter values`  
7.2 `p.2, SymTuner enabled KLEE to discover 11 different bugs that cause the latest versions of the open-source programs to crash, far outweighing the conventional KLEE that ended up finding three of them. Compared to KLEE with a naive approach that randomly samples parameter values, SymTuner succeeded in increasing the number of covered branches and found bugs by 12% and 45%, respectively.`  

## List of paper references which contain phrase "symbolic execution" in title and are not presented in the list of primary studies
(add as many list items 8.x as required. Remove unnessesary items)

8.1 `TimotejKapus,MartinNowack,andCristianCadar.2019.ConstraintsinDynamic Symbolic Execution: Bitvectors or Integers?. In Tests and Proofs, Dirk Beyer and Chantal Keller (Eds.). Springer International Publishing, Cham, 41–54.`  
8.2 `Corina S Păsăreanu and Neha Rungta. 2010. Symbolic PathFinder: symbolic exe- cution of Java bytecode. In Proceedings of the IEEE/ACM international conference on Automated software engineering (ASE ’10). 179–180.`  
8.3 `ShiqiShen,ShwetaShinde,SoundaryaRamesh,AbhikRoychoudhury,andPra- teek Saxena. 2019. Neuro-Symbolic Execution: Augmenting Symbolic Execution with Neural Constraints.. In Proceedings of the Symposium on Network and Dis- tributed System Security (NDSS ’19).`  
8.4 `Jiri Slaby, Jan Strejček, and Marek Trtík. 2013. Symbiotic: synergy of instrumen- tation, slicing, and symbolic execution. In International Conference on Tools and Algorithms for the Construction and Analysis of Systems (TACAS ’13). 630–632.`  
