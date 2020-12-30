# ToDoList-with-Django

장고로 ToDoList 만들기

sqlLite 접속 : python manage.py dbshell
table 목록 확인 : .tables
table 정보 확인 : PRAGMA table_info(테이블명);
순서(단순 Number) | 이름 | 형태 | notnull 여부 | pk 여부

- notnull은 필수인지 선택인지, 0일경우 선택, 1일경우 필수
- pk는 primary key, 0일경우 아니고, 1일경우 맞음

table 데이터 값 확인 : select 필드 from 테이블명;
