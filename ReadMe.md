# 🐳 BuddyMe
프리다이빙 / 스쿠버다이빙을 즐기는 사람들을 위한 커뮤니티 사이트

## 📖 서비스 소개
커뮤니티에서 다이빙 관련 정보를 공유하고, 다이빙을 함께 즐길 수 있는 버디 매칭 기능을 제공하는 커뮤니티 서비스


## 🙋🏻‍♂️ 팀원
백엔드 3명 , 디자이너 1명, 프론트엔드 2명

## 🖥 내가 개발한 기능

### 백엔드 개발
- 유저서비스 - Oauth2.0을 활용한 소셜 로그인 (카카오, 구글 , 네이버), 마이페이지
- 인증서비스 - Spring Security, JWT를 활용한 인증 / 인가 구현
- 알림서비스 - Kafka를 활용한 비동기 푸시 알림

### 인프라 1인 개발
- Github Actions, Docker를 활용한 CI & CD 환경 구축
- 운영환경 클라우드 서버 구축 AWS (EC2, Cloudfront, S3, CodeDeploy) , GCP 등 인스턴스 생성 및 관리
- 개발환경 홈서버 구축 (Self-Hosted, MacMini)

## 📌 사용 기술
- Language : Java 21
- FrameWork : Spring Boot 3.2, Spring Cloud (MSA)
- Database : Postgresql, Redis
- DevOps : Git, Github Actions, Docker, AWS, Kafka, GCP



## 📚 협업을 위해 주도한 부분
- [협업 컨벤션을 위한 Github Project 사용 규칙 정하기](https://github.com/freediving-community/api-server/issues/3)
- [유저 서비스 도메인 모델링](https://github.com/freediving-community/api-server/issues/1)
- [Oauth 2.0 기반 소셜로그인, JWT 인증/인가 로직 개발 코드](https://github.com/freediving-community/api-server/pull/26/commits/f2a7f94e1cf96d63e821cb1e2099e1ae484854d1)
- [MSA 환경에서 유저 조회 API 설계](https://github.com/freediving-community/api-server/issues/86)
- [알림이력 FLOW 및 kafka 메시징 사용법 정리](https://github.com/freediving-community/api-server/issues/191)
- [Spring Cloud 환경 내 MSA CI & CD 환경 구축](https://github.com/freediving-community/api-server/wiki/CI-&-CD-%EA%B5%AC%EC%B6%95)
- [이미지 최적화를 위한 AWS S3 Presigned URL](https://github.com/freediving-community/api-server/issues/66)
- [인프라 구성 및 망분리 정보 정리](https://github.com/freediving-community/api-server/wiki/%EC%9D%B8%ED%94%84%EB%9D%BC-%EA%B5%AC%EC%84%B1%EB%8F%84)



## ⚙️ 애플리케이션 구성도
<img width="1338" alt="image" src="https://github.com/user-attachments/assets/74b15fa6-8aa8-41ee-84bd-132511e3a337" />


## ✌🏻 클라이언트 화면

### 회원가입 화면
<img width="711" alt="image" src="https://github.com/user-attachments/assets/10e8f7fa-b3e3-40ce-930f-8d74194a9f3e" />

### 홈 화면
<img width="563" alt="image" src="https://github.com/user-attachments/assets/aa90cd27-8aff-42cc-9ac4-ce5709e657b9" />

### 버디매칭
<img width="565" alt="image" src="https://github.com/user-attachments/assets/ab652914-4d98-4581-89cf-80cec29f9310" />

### 스토리
<img width="562" alt="image" src="https://github.com/user-attachments/assets/a82c562d-d799-4120-896b-292ccd67c823" />

### 내 활동
<img width="560" alt="image" src="https://github.com/user-attachments/assets/1ec584b1-deb2-436d-8c8e-2d7639fae1e9" />

### 마이페이지
<img width="566" alt="image" src="https://github.com/user-attachments/assets/9b52b653-151c-46cd-a771-bf16fc775bba" />

### 알림이력
<img width="563" alt="image" src="https://github.com/user-attachments/assets/47ab4c4a-bf8b-4615-a998-2ba8fb5057a5" />
