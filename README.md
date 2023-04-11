# Symbolic Execution Limitations - Systematic Literature Review

This repo contains supplementary artifacts produced in the process of work on the systematic review.
The main goal of the review is to collect the ultimate list of known issues/problems within symbolic 
execution field as well as exising approaches to solve those problems.

## Review process overview

The key activity of the review is to assess information within exising studies to acquire answers
to interesting questions. The list of studies is compiled from papers published within relevant engineering 
conferences that have been held starting from 1975. The studies are collected into [primary list of studies](/primary-list-of-studies.md). 

The assessment is accomplished within two rounds. _Round I_ (pre-assessment) is aimed at filtering out those
papers which have no relevant information as per review goals. Purpose of _Round II_ is to extract relevant
information.

For both rounds studies for assessment are assigned centrally by research initiators.

Collected assessment results are further analyzed to answer primary questions of the review.

## How to contribute

Contribution can be made in form of Round I or Round II assessment.

---
**!AUTHORITY NOTE!** Be aware that contribution into the assessement does not imply inclusion into the list of survey authors. Along with that every assessment contributor will be mentioned in acknoledgments section of the produced paper.

---

If you would like to contribute to either round please raise an issue in this repository and tag `@mximp`. You will be given a set of studies IDs from primary list for assessment.

### Round I assessment contribution
For every assigned ID from primary list of studies do the following:
1. Copy the file `study-assesment-round-I-<ID>.md` replacing `<ID>` with the study ID (available as `(ID)` part within primary list of studies).
2. Populate the form replacing `???` with respective answers based on study content. Follow the qeustions and instructuions in the form.
3. Create pull request adding the file into `\round_I\` folder.

### Round II assessment contribution
For every assigned ID from primary list of studies do the following:
1. Check corresponding `round_I\study-assessment-round-I-***.md` file. It must present and be populated. If not contact the requestor.
1. Copy the file `study-assesment-round-II-<ID>.md` replacing `<ID>` with the study ID (available as `(ID)` part within primary list of studies).
2. Populate the form replacing `???` with respective answers based on the study content. Use information from corresponding `round_I\study-assessment-round-I-***.md`. Follow the qeustions and instructuions in the form.
3. Create pull request adding the file into `\round_II\` folder.
