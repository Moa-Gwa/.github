## 모아과

![모아과](https://raw.githubusercontent.com/Moa-Gwa/.github/main/profile/assets/hero.png)

<br />

**대학 본부·학과·학생자치단체**에 흩어진 가톨릭대학교 학내 공지를 한곳에 모아, 필요한 소식과 일정을 놓치지 않도록 돕는 **학내 통합 공지 플랫폼** <br />
2026 컴퓨터공학과 학술제 출품작

<br />

## 목차
- [팀원](#팀원)
- [저장소](#저장소)
- [주요 기능](#주요-기능)
- [기술 스택](#기술-스택)

<br />

## 팀원

|<img src="https://avatars.githubusercontent.com/u/197102497?v=4" width="150" height="150" alt="이윤호"/>|<img src="https://avatars.githubusercontent.com/u/111987574?v=4" width="150" height="150" alt="김현지"/>|
|:-:|:-:|
|이윤호<br/>[@uknowe](https://github.com/uknowe)|김현지<br/>[@kimhyunji24](https://github.com/kimhyunji24)|

<br />

## 저장소

| 저장소 | 설명 |
| --- | --- |
| [FE](https://github.com/Moa-Gwa/FE) | 학생·관리자 웹 애플리케이션 |
| [BE](https://github.com/Moa-Gwa/BE) | API 서버, 공지 크롤러, 실시간 이벤트, 결제 |

<br />

## 주요 기능

### 공통

| 기능명 | 기능 설명 |
| --- | --- |
| **로그인** | • 학생: Google·Kakao 소셜 로그인 <br> • 관리자: 아이디·비밀번호 로그인 <br> • HttpOnly 쿠키 기반 세션 |
| **공지 수집** | • 학교 홈페이지 공지 주기적 크롤링 <br> • 학생회 Instagram 게시물과 캐러셀 이미지 수집 |
| **실시간 반영** | 공지 등록·수정·삭제를 학생 화면에 SSE로 즉시 반영 |

### 학생

| 기능명 | 기능 설명 |
| --- | --- |
| **홈** | 학내 주요 소식, 카테고리, 나를 위한 공지, 최신 공지 |
| **공지 탐색** | • 발행 주체·카테고리 필터, 키워드 검색 <br> • 최신순·마감 임박순·일정순·인기순 정렬 <br> • 공지 상세 조회와 북마크 |
| **일정** | 공지의 행사·마감 일정을 달력으로 확인 |
| **관심 설정** | 주전공, 관심 학과·학생자치단체·카테고리 기반 맞춤 피드 |
| **알림** | 관심 학과·단체의 새 공지, 중요 공지 알림함과 수신 설정 |

### 생활

| 기능명 | 기능 설명 |
| --- | --- |
| **재학생 인증** | 학교 이메일 인증 코드 확인 |
| **중고거래** | 물품 등록·수정·삭제, 찜, 거래 요청과 수락, 판매 상태 변경 |
| **같이 사기** | • 모집글 등록, 참여와 취소, 모집 마감 <br> • 유료 모집 참여 결제(토스페이먼츠 결제위젯) <br> • 참여 취소·모집 취소·목표 미달 시 전액 자동 환불 |
| **채팅** | 거래·같이 사기 인앱 채팅(STOMP), 읽음 표시 |
| **내 거래** | 내 물품, 찜 목록, 보낸 요청, 같이 사기 내역 |

### 관리자

| 기능명 | 기능 설명 |
| --- | --- |
| **대시보드** | 진행 중인 공지와 마감 처리, 공지 수·조회·저장·공유 성과 |
| **공지 관리** | 공지 등록·수정·삭제·복제, 즉시·예약 게시, 마감 처리, 이미지 첨부 |
| **일정** | 게시 예정, 행사 시작, 신청 마감 일정 확인 |
| **조직 관리** | 단체 소개, 공식 홈페이지·SNS 정보 관리 |

<br />

## 기술 스택

### FrontEnd
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white) ![Toss Payments](https://img.shields.io/badge/Toss%20Payments-0064FF?style=for-the-badge&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

### BackEnd
![Java](https://img.shields.io/badge/Java%2017-007396?style=for-the-badge&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### Crawler
![Jsoup](https://img.shields.io/badge/Jsoup-263238?style=for-the-badge&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logoColor=white)

### DB
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### CI
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

<br />
