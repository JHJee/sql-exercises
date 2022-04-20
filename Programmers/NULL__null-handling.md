# [NULL] NULL 처리하기 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59410

```sql
SELECT ANIMAL_TYPE, IFNULL(NAME, "No name"), SEX_UPON_INTAKE
FROM ANIMAL_INS
```
