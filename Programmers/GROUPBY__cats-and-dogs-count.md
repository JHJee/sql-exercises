# [GROUP BY] 고양이와 개는 몇 마리 있을까 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59040

```sql
SELECT ANIMAL_TYPE, count(*) AS count
FROM ANIMAL_INS
GROUP BY ANIMAL_TYPE
ORDER BY ANIMAL_TYPE
```
