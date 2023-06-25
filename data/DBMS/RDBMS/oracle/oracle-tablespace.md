# oracle tablespace 
: 오라클 데이터베이스의 데이터 저장 단위  



**데이터 저장 단위**
- 물리적 = data file 
- 논리적
  - tablespace
  - segments
  - extends
  - data blocks



```sql 

-- 조회
select * from dba_tablespaces;


-- 생성
create tablespace 테이블스페이스명 

```