# [GROUP BY] 입양 시각 구하기(1) - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59412

```sql
SELECT hour(DATETIME) AS HOUR, count(*) AS COUNT
FROM ANIMAL_OUTS
WHERE hour(DATETIME) BETWEEN 9 AND 19
GROUP BY hour(DATETIME)
ORDER BY hour(DATETIME)
```
