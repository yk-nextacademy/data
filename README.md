```sql
CREATE TABLE emp03 (                             
   emp_id      NUMBER         NOT NULL,
   emp_name    VARCHAR2(100)  NOT NULL,
   gender      VARCHAR2(10)       NULL, 
   age         NUMBER             NULL,
   hire_date   DATE               NULL,
   etc         VARCHAR2(300)      NULL,
   PRIMARY KEY ( emp_id )
);
```

```sql
INSERT INTO emp03 ( emp_id, emp_name, gender, age, hire_date )
VALUES ( 1, '홍길동', '남성', 33, '2018-01-01' );

INSERT INTO emp03 ( emp_id, emp_name, gender, age, hire_date )
VALUES ( 2, '김유신', '남성', 44, '2018-01-01' );

INSERT INTO emp03 ( emp_id, emp_name, gender, age, hire_date )
VALUES ( 3, '강감찬', '남성', 55, '2018-01-01' );

INSERT INTO emp03 ( emp_id, emp_name, gender, age, hire_date )
VALUES ( 4, '신사임당', '남성', 45, '2018-01-01' );
```
