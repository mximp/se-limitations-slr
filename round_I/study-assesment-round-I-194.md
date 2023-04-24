# STUDY ASSESSMENT - ROUND I

Please replace '???' (triple question mark) in form below with respective answers. 

## Meta information

|                                               |                                                  |
| ---                                           |--------------------------------------------------|
| 1. Assessor name                              | `Eugene Darashkevich`                            |
| 2. Assessment date (`DD.MM.YYY`)              | `24.04.2023`                                     | 
| 3. Study title                                | `MPISE: Symbolic Execution of MPI Programs` |
| 4. Publication year in format YYYY, e.g. 2023 | `2014`                                           |
  
## Has the study raised any issues of Symbolic Execution?

Please examine Abstract, Introduction and Contribution sections on the subject of mentioning issues/difficulties/challenges/etc. of 
Symbolic Execution.
  
5. (Yes/No): `Yes`

If you answered 'Yes' please provide references to the location(s) within the study supporting your answer:  
(add as many list items 5.x as required in format `page No., citation`. Remove unnessesary items)

5.1 `p.1, In this paper, we employ symbolic execution to
ensure the input coverage, and propose an on-the-fly schedule algorithm
to reduce the interleaving explorations for non-determinism coverage,
while ensuring the soundness and completeness.`   

5.2 `p.2 While TASS [22] employs symbolic execution and model checking
to verify MPI programs, it only works on small programs due to the limited
support of runtime library models.`

5.3 `p.2 In this paper, we use symbolic execution to reason about all the inputs and try
to guarantee the coverage on both input and non-determinism.`

5.4 `p.2 We symbolically
execute the statements in each process of an MPI program to find input-related
bugs, especially runtime errors and deadlocks.`

5.5 `p.2 Furthermore, unlike the symbolic execution plus model checking
method in [22], which uses an MPI model to simulate the runtime behaviors of
MPI library, we use a true MPI library as the model, which enables us to analyze
real-world MPI programs.`

## Has the study introduced any new technique within Symbolic Execution field?

Please examine Abstract, Introduction and Contribution sections on the subject of mentioning any technique/approach/method related to Symbolic Execution.
  
6. (Yes/No): `Yes`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 6.x as required in format `page No., citation`. Remove unnessesary items)

6.1 `p.1  In this paper, we employ symbolic execution to
ensure the input coverage, and propose an on-the-fly schedule algorithm
to reduce the interleaving explorations for non-determinism coverage,
while ensuring the soundness and completeness.`

6.2 `p.2 Furthermore, unlike the symbolic execution plus model checking
method in [22], which uses an MPI model to simulate the runtime behaviors of
MPI library, we use a true MPI library as the model, which enables us to analyze
real-world MPI programs.`

## Has the study suggested any formal or informal proof of the limitations mentioned?

Please examine Abstract, Introduction and Contribution sections on the subject of mentioning any description or references to
formal or empirical proof justifying any of Symbolic Execution problems.
  
7. (Yes/No): `No`

If you answered 'Yes' please provide below references to the location(s) within the study supporting your answer:  
(add as many list items 7.x as required in format `page No., citation`. Remove unnessesary items)

## List of paper references which contain phrase "symbolic execution" in title and are not presetned in the list of primary studies
(add as many list items 8.x as required. Remove unnessesary items)

8.1 `Stefan Bucur, Vlad Ureche, Cristian Zamfir, and George Candea. Parallel symbolic
execution for automated real-world software testing. In Proceedings of the Sixth
Conference on Computer Systems, EuroSys ’11, pages 183–198, New York, NY,
USA, 2011. ACM.`

8.2 `Cristian Cadar, Patrice Godefroid, Sarfraz Khurshid, Corina S. P˘as˘areanu,
Koushik Sen, Nikolai Tillmann, and Willem Visser. Symbolic execution for software testing in practice: Preliminary assessment. In Proceedings of the 33rd International Conference on Software Engineering, ICSE ’11, pages 1066–1071, New
York, NY, USA, 2011. ACM.`

8.3 `Xianghua Deng, Jooyong Lee, and Robby. Bogor/Kiasan. A k-bounded symbolic
execution for checking strong heap properties of open systems. In Proceedings of the
21st IEEE/ACM International Conference on Automated Software Engineering,
ASE ’06, pages 157–166, 2006.`

8.4 `J.King. Symbolic execution and program testing. Communications of the ACM,
19(7):385–394, 1976.`
