### 240516
# SQLite3 
### <br/><br/><br/>

## sqlite 설치(windows)
### (https://www.sqlite.org/download.html)[sqlite download 페이지]
### 여기서 아래 tools라고 적힌 것으로 다운로드한다.
#### ![image](https://github.com/Shin-jongwhan/sqlite/assets/62974484/b0172cbf-dfb0-437d-a254-69f44d1186cb)
### 압축을 풀고 sqlite3.exe를 실행한다.
#### ![image](https://github.com/Shin-jongwhan/sqlite/assets/62974484/56f94279-4cff-4794-b4d6-bd81201fb8c4)
### 그러면 이렇게 cmd 창이 나타난다.
#### ![image](https://github.com/Shin-jongwhan/sqlite/assets/62974484/1ef268cd-94f0-4415-962c-71e0311ccaba)
### <br/><br/><br/>

## db 생성 방법
### * mysql과 똑같이 쿼리문의 기능들은 대소문자 상관 없이 사용할 수 있다(컬럼, 값 이런 것은 구분해야 함).
```
# db 생성
.open Test.db

# create table
create table test(
    idx     int, 
    name    varchar(50)
)

# table 스키마 조회
.schema test;

# insert(값 넣기)
insert into test values(1, 'test');

# select(조회)
select * from test;
```
### <br/><br/><br/>

