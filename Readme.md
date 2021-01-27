# sofis4server
sofis for server

# setting environment
## install DBMS for local test - AWS DBMS 사용시에는 설치 불필요
install & steeing: https://velog.io/@inyong_pang/MySQL-%EC%84%A4%EC%B9%98%EC%99%80-%EC%B4%88%EA%B8%B0-%EC%84%A4%EC%A0%95

## clone git source
bash> git clone https://github.com/secuworks2020/sofis4server.git

## install library
bash> cd backend

bash backend> npm install

## make backend/config/Database.json file
~~~
{
    "host": "localhost", // server access point
    "user": "{user name}", 
    "password": "{user password}",
    "database": "{use database}"
}
~~~

. SOFIS와 연동이 가능한 Database.json 파일을 프로젝트에 추가함

## run
bash backend> npm i nodemon -g

bash backend> nodemon

. 노드실행시 자동으로 테이블이 생성됨

## Android/iOS App API 
. version check API

. register push token API

. set allow push API

