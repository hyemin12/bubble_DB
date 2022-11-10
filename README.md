1. json server를 전역으로 설치

```
npm install -g json-server
```

2. DB 사용할 JSON파일이 있는 위치에서 data를 load할 수 있도록 명령어 입력

```
 json-server --watch [파일명].json


json-server --watch [파일명].json --port [사용할 포트번호]
```

포트번호 입력하지 않으면 3000번 포트로 열려서 클라이언트 서버와 충돌할 수 있음...!

```
json-server --watch db.json --port 3001
```
