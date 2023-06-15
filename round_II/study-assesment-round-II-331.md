# STUDY ASSESSMENT - ROUND II - DETAILED DATA COLLECTION

Please replace '???' (triple question mark) with respective answers.

## Meta information

|                                                 |                                                           |
|-------------------------------------------------|-----------------------------------------------------------|
| 1. Assessor name                                | `Vladimir Zakharov`                                       |
| 2. Assessment date (`DD.MM.YYYY`)               | `15.06.2023`                                              | 
| 3. Study title                                  | `Complete Shadow Symbolic Execution with Java PathFinder` |
| 4. Publication year in format `YYYY`, e.g. 2023 | `2019`                                                    |

## 5. Problems of Symbolic Execution approach identified within the study

Please list below identified problems/issues/challenges related to symbolic
execution. Add as many list items 5.x as required. Specify _problem description_
and _scope of applicability_ for the issue. Also provide the _page reference_
where the problem is found. Remove unnecessary items.

5.1 Shadow Symbolic Execution (SSE) has several implementation problems and
can't find all possible paths that can contain uncovered bugs or errors.
Particular problems of the old SSE approach:

- "Deeper divergences might be missed in the BSE phase"
- "The initial input has to cover potential divergence points"

Scope: Shadow Symbolic Execution (SSE), Symbolic Execution (SE), Tests
Generation
References: Page 2, Section 2.3, "Need for further Research"

## 6. Techniques and methods of symbolic execution suggested within the study

Please list below identified techniques or methods related to symbolic
execution. Add as many list items 6.x as required. Specify _technique
descriptions_ and_problem it addresses_. Also provide the _page reference_ where
the technique is found. Remove unnecessary items.

6.1 Technique: Conservative approach that executes the change-annotated program
with bounded symbolic execution and four-way forking in a depth first manner,
while detecting divergences on the fly
Problem addressed: "Deeper divergences might be missed in the BSE phase" and  
"The initial input has to cover potential divergence points"
References: Page 2, Section 3, "Approach"

## 7. Proofs of limitations mentioned within the study

Please list below identified proofs/justifications for the problems of symbolic
execution. Add as many list items 7.x as required. Specify _problem/issue_ and
_proof description_ for it. Also provide the _page reference_ where the proof is
found. Remove unnecessary items.

7.1 The limitations of the previous SSE approach is quite well described by
several practical examples that shows problematic cases which wasn't covered by
the plain old SSE algorithm.
References: Page 2, Section 2.3, "Need for further Research"
