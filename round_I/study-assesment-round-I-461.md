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
| 3. Study title                                  | `Tainting-Assisted and Context-Migrated Symbolic Execution of Android Framework for Vulnerability Discovery and Exploit Generation` |
| 4. Publication year in format `YYYY`, e.g. 2023 | `2020` |
  
## Has the study raised any issues of Symbolic Execution?

Please examine the paper on the subject of mentioning issues/difficulties/challenges/etc. of Symbolic Execution.
  
5. (Yes/No): `Yes`

If you answered 'Yes' please provide references to the location(s) within the study supporting your answer:  
(add as many list items 5.x as required in format `page No., citation`. Remove unnecessary items)

5.1 `p.2, While many symbolic execution systems have been proposed for analyzing Windows programs [7], [27], [28], Unix programs [4], [8], [9], and Android apps [1], [37], [46], [47], [64], none has explored how to symbolically analyze such complex middleware as Android Framework. Due to unique characteristics of the framework, many new challenges arise.`  
5.2 `p.2, Unlike an independent program, Android Framework is a large piece of middleware consisting of many system services, atop which Android applications are started and run. It is not surprising that Android Framework has a complex initialization phase, which parses system and application settings and then prepares all the system services. Symbolic execution that starts from the main entry of Android Framework, SystemServer.main, would quickly cause state explosion and hence cannot reach deep code paths.`  
5.3 `p.2, ... how to deal with the situation of the missing context information is a challenging problem`
5.4 `p.3, How to automatically identify variables derived from the malicious app, among the large number of data structures in the framework, is an intriguing new problem as well as a challenge.`  
5.5 `p.3, ... how to design an architecture that can make use of the Android execution environment without leading to a complex coupled implementation is a challenge`

## Has the study introduced any new technique within Symbolic Execution field?

Please examine the paper on the subject of mentioning any technique/approach/method related to Symbolic Execution.
  
6. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 6.x as required in format `page No., citation`. Remove unnessesary items)

6.1 `p.3, Unlike previous symbolic execution techniques that either start analysis from the main function or analyze a non-main function without the context information, we propose techniques that allow service interface methods of middleware to be analyzed sep- arately, for much improved scalability, without harming the soundness of the analysis results.`  
6.2 `p.3, An innovative architecture that builds the symbolic executor out of the Android system is proposed. An enabling algorithm that migrates the execution con- text information from the Android system to the symbolic executor is designed.`  

## Has the study suggested any formal or informal proof of the limitations mentioned?

Please examine the paper on the subject of mentioning any description or references to
formal or empirical proof justifying any of Symbolic Execution problems.
  
7. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 7.x as required in format `page No., citation`. Remove unnessesary items)

7.1 `p.3, We have implemented CENTAUR and demonstrated its effectiveness and precision through applications of vulnerability discovery and PoC exploit genera- tion.`  
7.2 `p.3, We concretely demonstrate how CENTAUR can be applied to vulnerability discovery. In contrast to recent research that relies on laborious and error-prone manual work for finding framework vulnerabilities [54], [56], we show that how it is automated and guarantees zero-false positives.`  

## List of paper references which contain phrase "symbolic execution" in title and are not presented in the list of primary studies
(add as many list items 8.x as required. Remove unnessesary items)

8.1 `D. Davidson, B. Moench, T. Ristenpart, and S. Jha, “FIE on firm- ware: Finding vulnerabilities in embedded systems using symbolic execution,” in Proc. 22nd USENIX Conf. Security, 2013, pp. 463–478.`  
8.2 `D. A. Ramos and D. Engler, “Under-constrained symbolic execu- tion: Correctness checking for real code,” in Proc. 24th USENIX Conf. Security Symp., 2015, pp. 49–64.`  
8.3 `S. Rasthofer, S. Arzt, S. Triller, and M. Pradel, “Making malory behave maliciously: Targeted fuzzing of android execution envi- ronments,” in Proc. IEEE/ACM 39th Int. Conf. Softw. Eng., 2017, pp. 300–311.`  
