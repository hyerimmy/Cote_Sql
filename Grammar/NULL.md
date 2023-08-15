# NULL

### IFNULL
```sql
SELECT IFNULL(Column명, "Null일 경우 대체 값") FROM 테이블명; 
```

### IF() + IS NULL
```sql
SELECT IF(IS NULL(NAME), "No name", NAME) as NAME
FROM ANIMAL_INS
```

### IS NULL
```sql
SELECT COUNT(*) AS 'USERS'
FROM USER_INFO
WHERE AGE IS NULL
;
```