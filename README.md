# 🚀 Delivery Service

**Delivery Service**는 배달/픽업 주문을 처리하는 웹 애플리케이션입니다. JWT 인증을 통한 로그인 및 주문 관리 기능을 제공합니다.\

---

## 📌 기술 스택

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.3-green?logo=spring)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)
![MySQL](https://img.shields.io/badge/MySQL-8.0.36-blue?logo=mysql)
![Redis](https://img.shields.io/badge/Redis-7.4.2-red?logo=redis)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)

- **Backend:** Spring Boot, Spring Security, JPA, MySQL  
- **Authentication:** JWT (Access Token + Refresh Token)
- **Cache:** Redis (Docker 컨테이너 기반, 데이터 조회 성능 최적화)
- → 현재 Docker와 Redis 입문 단계 학습 중  
- **Build:** Gradle  

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 🔐 JWT 인증 | Access Token, Refresh Token 기반 로그인 |
| 🛒 장바구니 | 메뉴를 장바구니에 추가/삭제 |
| 📦 주문 관리 | 배달/픽업 주문 생성 및 상태 변경 |
| 🏠 가게 관리 | 사장님 계정이 메뉴 및 주문을 관리 |
| 💳 결제 서비스 |	주문에 대한 결제 처리 및 결제 상태 관리 (예정) |
---

## 🗂 ERD 및 아키텍처

ERD 변경 과정\
[ERD](https://drive.google.com/file/d/1NwxAfwWm77QdKvtVt4K1UndHKuJ1FdgL/view?usp=sharing)\
[ERD 1차 변경](https://drive.google.com/file/d/1xJN1zos4hOb2IoZAH681U0JbehwFDfNI/view?usp=sharing)\
[ERD 2차 변경](https://drive.google.com/file/d/1uE4hROb0lU1AZjo-qNGRsaL5nsAWcUHs/view?usp=sharing)\
[ERD 3차 변경](https://drive.google.com/file/d/11MP8k2anu-_WZYavYzYC1PNzRgoMvrgH/view?usp=sharing)\
[ERD 4차 변경](https://drive.google.com/file/d/1y74OE9vOHWuTnC3YISA0UDA689GYEMq1/view?usp=sharing)\
[ERD 5차 변경](https://drive.google.com/file/d/1vfxFoXPVWFIdTNrlR8xAwDWAfgnOgbB3/view?usp=sharing)\
[ERD 6차 변경](https://drive.google.com/file/d/1tHLph0VJp2bRF5eRd_zH2hK50pRFzCLA/view?usp=sharing)\
[ERD 7차 변경](https://drive.google.com/file/d/1PV8I4u3kLPMx8DgiyJzjQVLFhwCwfmUM/view?usp=sharing)


---

## 📑 API 명세

본 프로젝트의 모든 API 명세는 Postman을 통해 관리하고 있습니다. 아래 파일을 다운로드하여 Postman에서 **Import** 하시면 상세한 요청/응답 구조를 확인하실 수 있습니다.

- **API 명세서 파일:** [delivery_service_api.json](./delivery_service_api.json) 
  *(※ 파일 클릭 후 상단 'Download raw file' 버튼을 눌러 내려받으세요.)*

---

## 👥 팀원 정보

| 이름 | 역할 |
|------|------|
| 이다검 | 백엔드 개발 |
| 정상인 | 프론트엔드 개발 |
