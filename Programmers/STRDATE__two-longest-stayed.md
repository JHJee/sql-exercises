# [STRDATE] 오랜 기간 보호한 동물(2) - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59411

```sql
SELECT A.ANIMAL_ID, A.NAME
FROM ANIMAL_INS AS A INNER JOIN ANIMAL_OUTS AS B
WHERE A.ANIMAL_ID = B.ANIMAL_ID
ORDER BY B.DATETIME-A.DATETIME DESC
LIMIT 2
```
