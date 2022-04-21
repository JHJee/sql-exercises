# [STRDATE] 중성화 여부 파악하기 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59409

```sql
SELECT ANIMAL_ID, NAME, IF((SEX_UPON_INTAKE LIKE 'Neutered%') OR (SEX_UPON_INTAKE LIKE 'Spayed%'), 'O', 'X') AS '중성화'
FROM ANIMAL_INS
ORDER BY ANIMAL_ID
```
