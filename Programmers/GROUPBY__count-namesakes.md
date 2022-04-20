# [GROUP BY] 동명 동물 수 찾기 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59041

```sql
SELECT NAME, count(*) AS COUNT
FROM ANIMAL_INS
WHERE NAME IS NOT NULL
GROUP BY NAME
HAVING count(*) > 1
ORDER BY NAME
```
