---
layout: default
---

# Abstract

Refactoring is a non-trivial maintenance activity. Developers spend time and effort refactoring code to remove structural problems, i.e., code smells. Recent studies indicated that developers often apply *composite refactoring* (composite, for short), i.e., two or more interrelated refactorings. However, previous studies revealed that only 10% of composite refactorings are considered *complete*, i.e., those fully removing code smells. Many of the incomplete refactorings end up even introducing or replacing smells, which have to be further removed later in the project. However, developers are missing catalogs that guide them to fully refactor code smells out, alerting them about possible side effects of alternative composite recommendations. To fill this gap, we performed a mixed-matched study to create an enhanced catalog of complete composites derived from their recurring application across software projects. The derived catalog includes empirically-observed side effects for each alternative composite and proposes refactoring combinations to fully remove more than one code smell, minimizing those side effects. The recommendations were extracted from 42 software projects, both open and closed-source, with more than 250K refactorings. Then, our catalog recommendations were evaluated by nine software developers. The evaluation indicates that 78% of developers reported that their solutions could have worse side effects without our recommendations, increasing the effort to remove smells critical to them. Thus, our catalog can guide both developers and researchers on how to better combine refactorings in composites that effectively reduce side effects in the practice. 

# Artifacts

| #      | Artifact | Description |
| ----------- | ----------- | ----------- |
| 1      | [Information of Software Projects](https://github.com/compositerefactoring/site/raw/main/downloads/general-data-per-project.xlsx) | General information about the software projects that were investigated in this study. |
| 2      | [Refactorings](https://drive.google.com/drive/folders/1Bdaho1Vs4qDnwnu1CDW22meqw4F6JqyO?usp=sharing) | All Refactorings collected in this study. |
| 3      | [Composite Refactorings](https://drive.google.com/drive/folders/1pNI2LYNANySKazd3rSV_U9RRWrlq0trG?usp=sharing) | All Composite Refactorings collected in this study. |
| 4      | [Complete Composite Refactorings](https://drive.google.com/drive/folders/15Kx0cx2g3Qxl6FmT7CHhgQXcL2DMVvWL?usp=sharing) | All Complete Composite Refactorings collected in this study. |
| 5      | [Most Common Combinations of Composites](https://drive.google.com/drive/folders/1u3X0cYBeBXFnlo0XQaBfeO0LGz8RoxBE?usp=sharing) | Most common combinations of Composite Refactorings collected in this study. |
| 6      | [Side Effects per Composite Combination](https://drive.google.com/drive/folders/11GxQOSV_sZHRazXVfsOA_bn-jkUqpVMH?usp=sharing) |(Side) Effects of Combinations of Complete Composites investigated in this study. |
| 7      | [Code Smells](https://1drv.ms/u/s!AuaYEGY-_fTJrt4y8mFO6d6A0MnQzg?e=AEqnSt) | All code smells collected in this study. |
| 8      | [Interviews - Answers](https://docs.google.com/spreadsheets/d/1HPZH1xXrIFjvKNiEFoMq4c_5jDBSBa9s/edit?usp=sharing&ouid=112357502681826466479&rtpof=true&sd=true) | The questions, answers and summarization of our interviews. |
| 8      | [Interviews - Sample Code](https://drive.google.com/drive/folders/1NXPfASIfng0LD4nmbHnrMcS1C_uxWbG6?usp=sharing) | The smelly code that was presented for subjects |