# 연습 저장소 - 우버 클론

nomad academy의 우버 강의를 보고 기록한 저장소 입니다.

## 기술 스택

- ReactJS
- GraphQL
- Typescript
- NodeJS

---

### Back-End note

**미들웨어(middleware)**

> 앱의 연결이나 요청들을 다루는 방식을 수정
> 예를 들어, 모든 요청을 콘솔에 로깅(기록)하는 미들웨어를 만들고 싶어 우리의 앱에 일어나는 모든 행동을들을 콘솔에 기록 하게 되는데 누군가가 우리 앱의 API로 무언가를 할 때마다, 이 미들웨어가 요청을 가로채서 기록하고, 다음 단계로 진행 되도록 함.

**[graphql-yoga](https://github.com/prisma/graphql-yoga)**

- subscription, tools, graphql playground등을 빠르게 설정 할 수 있도록 도와주는 라이브러리

**[helmet](https://github.com/helmetjs/helmet)**

- helmet은 보안을 위한 **미들웨어**이며, 요청 때마다 미들웨어가 요청을 잠시 멈추고 검사한 후에 위험하지 않다고 판단되면 요청을 계속 진행시키는 라이브러리

**[TypeORM](https://github.com/typeorm/typeorm)**

- 복잡한 데이터베이스(SQL)언어의 작업을 ORM(Object Relational Mapper)를 사용함으로써 SQL언어로 바꿔주는 라이브러리
- TypeORM은 Typescript로 만들어 졌으며 Typescript로 개발하는 환경에 적합해 보인다.

**Issue**

- npm bcrypt 설치시 오류 발생 할 경우 node 버전을 확인 하고 Current버전 이라면 삭제 후 LTS 버전으로 재설치.
