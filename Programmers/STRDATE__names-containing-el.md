# [STRDATE] 이름에 el이 들어가는 동물 찾기 - MySQL

https://programmers.co.kr/learn/courses/30/lessons/59047

```sql
SELECT ANIMAL_ID, NAME
FROM ANIMAL_INS
WHERE (NAME LIKE '%el%' OR '%El%' OR '%EL%' OR '%eL%' )AND ANIMAL_TYPE = 'Dog'
ORDER BY NAME
```
