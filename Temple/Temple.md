---
title: <% tp.file.title %>
created:  <% tp.file.creation_date() %>
tag: 'project'
---

# PM-projectname
## π Goal
> νλ‘μ νΈμ λͺ©νλ₯Ό μμ±νλ€.

## π  Scheduel
> νλ‘μ νΈμ μΌμ μ μμ±νλ€. 
> νλ‘μ νΈμ μΌμ μ νννλ λΌλ νκ·Έλ₯Ό λ¬μμ tasksμμ λ³Ό μ μλλ‘ νλ€.
> λ΄κ° μ€μ ν Milestone λ§κ° κΈ°νλ μ΄κ³³μ μμ±νλ€.

##  πMilestones
> μ€κ° μ§μ μ νννλ€

## βTasks
- κ° λ§μΌμ€ν€μ λ¬μ±νκΈ° μν΄μ νμν νμ€ν¬λ€μ νλμ© μ΄κ±°νλ€.
- ν λΉμκ°κ³Ό κ·Έμ λ°λ₯Έ λ§κ°μΌ κΈ°λ‘νλ€.

## π Gantt
> μ€μΌμ₯΄μ λ°νμΌλ‘ Gantt μ°¨νΈλ₯Ό μμ±νλ€.
```mermaid
gantt
    dateFormat  YYYY-MM-DD
	title  Gantt
	
    section A section
    Completed task            :done,    des1, 2021-09-06,2021-09-08
    Active task               :active,  des2, 2021-09-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2021-09-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
	
	section test
	Active task 			: doc1, 2021-09-02, 2021-09-04
	
```
---
## Reference

μΆμ²: [https://olait.tistory.com/10?category=934740](https://olait.tistory.com/10?category=934740) [μ΄ν λ‘ μ¬μ΄ μ΅μλμΈ:ν°μ€ν λ¦¬]