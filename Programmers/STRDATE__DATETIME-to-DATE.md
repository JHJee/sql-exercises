# [STRDATE] DATETIME에서 DATE로 형 변환 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59414

```sql
SELECT ANIMAL_ID, NAME, date_format(DATETIME, '%Y-%m-%d') AS '날짜'
FROM ANIMAL_INS
ORDER BY ANIMAL_ID
```
