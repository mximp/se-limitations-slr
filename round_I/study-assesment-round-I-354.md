# STUDY ASSESSMENT - ROUND I

Please replace '???' (triple question mark) in form below with respective answers. 
Note that this round doesn't assume deep dive into all datails of the paper materials.
All the answers are supposed to be found within Abstract and Introduction sections if present. 
Otherwise in other sections in skimming mode.


## Meta information

|                                                 |       |
| ---                                             |  ---  |
| 1. Assessor name                                | `Roman Korostinskiy` |
| 2. Assessment date (`DD.MM.YYYY`)               | `18.07.2023` | 
| 3. Study title                                  | `Detecting MPI Usage Anomalies via Partial Program Symbolic Execution` |
| 4. Publication year in format `YYYY`, e.g. 2023 | `2018` |
  
## Has the study raised any issues of Symbolic Execution?

Please examine the paper on the subject of mentioning issues/difficulties/challenges/etc. of Symbolic Execution.
  
5. (Yes/No): `Yes`

If you answered 'Yes' please provide references to the location(s) within the study supporting your answer:  
(add as many list items 5.x as required in format `page No., citation`. Remove unnecessary items)

5.1 `p.1 ... static approaches introduce false positives (false alarms) due to their over-approximation of program execution paths. This is also especially challenging for MPI programs because of the conservative nature of static analysis approaches for parallel programs with distributed states.`  
5.2 `p.1, The fact that MPI is commonly used with weakly-typed imperative languages like C/C++ aggravates this problem because of the need to analyze low-level memory operations that may include pointer arithmetic and aliasing.`  
5.3 `p.1, This challenge is further exacerbated by a recent increase in the use of nonblocking MPI operations ...`  
5.4 `p.1, This poses multiple challenges for symbolic execution, since it may not successfully reach later points in a program execution due to path explosion contributing to excessive time and memory overheads`  
5.5 `p.5, Since a key requirement for PSE is to start symbolic execution from any function, a major challenge is how to initialize global/heap states that are expected to be defined on entry to that function?`  

## Has the study introduced any new technique within Symbolic Execution field?

Please examine the paper on the subject of mentioning any technique/approach/method related to Symbolic Execution.
  
6. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 6.x as required in format `page No., citation`. Remove unnessesary items)

6.1 `p.1, In this paper, we introduce a new debugging approach based on partial symbolic execution to identify anomalies in MPI usage`  
6.2 `p.1, ... we introduce a novel static analysis framework based on symbolic execution for detecting MPI usage anoma- lies in C/C++ applications`  
6.3 `p.1, By reasoning about the low-level memory operations in LLVM IR with symbolic execution, our approach can detect memory- related anomalies.`  
6.4 `p.1, Rather than applying symbolic execution to the whole program from the start, we demonstrate that starting symbolic executions from carefully selected interme- diate program points, which we refer to as partial symbolic execution, can be a key enabler of efficient anomaly detection for MPI programs.`  
6.5 `p.3, This section presents our approach to using symbolic exe- cution to detect anomalies in MPI programs.`  
6.6 `p.5 In this section, we present our partial symbolic execution (PSE) approach that supports the start of symbolic execution from a user-specified program point. There are two major techniques related to PSE, lazy initialization and shadow memory allocation.`

## Has the study suggested any formal or informal proof of the limitations mentioned?

Please examine the paper on the subject of mentioning any description or references to
formal or empirical proof justifying any of Symbolic Execution problems.
  
7. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 7.x as required in format `page No., citation`. Remove unnessesary items)

7.1 `p.2 An evaluation of our approach on real-world applications, compared with state-of-the-art static and dynamic MPI verification tools.`  

## List of paper references which contain phrase "symbolic execution" in title and are not presented in the list of primary studies
(add as many list items 8.x as required. Remove unnessesary items)
