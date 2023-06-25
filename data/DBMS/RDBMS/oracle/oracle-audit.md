# oracle audit
: 오라클 데이터베이스 보안 감사 기능  



```sql
show parameter audit

alter system set audit_trail=db scope=spfile;

audit select table, insert table, update table, delete table by 유저;
```


audit_trail=none  

- none  
- os
- db
- db, extended
- xml 
- xml, extended
