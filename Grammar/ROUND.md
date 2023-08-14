# ROUND

예제 4-6 employees 테이블에서 salary를 30일로 나눈 후 나눈 값의 소수점 첫째 자리, 소수점 둘째 자리, 정수 첫째 자리에서 반올림한 값을 출력하세요.


```sql
SELECT salary,

       salary/30 일급,

       ROUND(salary/30, 0) 적용결과0,

       ROUND(salary/30, 1) 적용결과1,

       ROUND(salary/30, -1) 적용결과MINUS1

FROM   employees;
```