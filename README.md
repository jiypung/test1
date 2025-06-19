# 🎨 Gallery Auction

### 온라인 예술 작품 경매 시스템

---

## 📌 프로젝트 개요

**Gallery Auction**은 사용자가 온라인으로 예술 작품을 경매에 등록하고, 입찰 및 낙찰까지의 과정을 웹을 통해 진행할 수 있는 예술 경매 플랫폼입니다.

---

## 👥 프로젝트 구성원 및 역할

- **김지현**: 회원관리 API(Svelte 연동), 프론트엔드 & 백엔드 연결, 기능 추가
- **박소영**: 프론트엔드 설계 및 구현
- **이지영**: PostgreSQL DB 설계, 경매품 API 개발
- **공통**: DB 설계 (DataGrip 활용)

---

## 🛠️ 사용 기술 스택

- **Backend**: Java, Spring Boot, Spring Web, Spring JDBC  
- **Frontend**: Svelte (VSCode 환경)  
- **DB**: PostgreSQL  
- **테스트 및 연동 도구**: Postman  
- **개발 도구**: IntelliJ IDEA, Visual Studio Code

---

## 👤 회원 관리 기능

### 1. 회원 등록

사용자는 주소, 이메일, 전화번호를 입력하여 회원으로 등록할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/file-WRF7Ry7qo569D2pdVD1cbZ" alt="회원 등록 화면" width="500"/>
</p>

### 2. 전체 회원 목록 조회

등록된 모든 회원 정보를 테이블로 확인할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/file-GNqVirSaoMVaVkzWcTKVxj" alt="회원 목록 화면" width="800"/>
</p>

### 3. 회원 ID로 검색

회원 ID를 입력하면 해당 회원의 상세 정보를 조회할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/file-Shcoxk7ZcAi6CjMTSz4Rmd" alt="회원 ID 검색 화면" width="400"/>
</p>

### 4. 회원 삭제

회원 ID를 입력하면 해당 회원 정보를 삭제할 수 있으며, 삭제 후 회원 목록에서 제외됩니다.

<p align="center">
  <img src="https://github.com/user-attachments/file-2XQMsyoUJnp2vKyL5VWx3F" alt="회원 삭제 화면" width="500"/>
  <br/>
  <img src="https://github.com/user-attachments/file-MF8PuXknrUPHEp1XPgViqy" alt="회원 삭제 후 목록" width="800"/>
</p>

### 5. 회원 정보 수정

기존 회원의 주소, 이메일, 전화번호를 수정할 수 있는 기능도 제공합니다.

<p align="center">
  <img src="https://github.com/user-attachments/file-KEHZAyaFnr8eyc2AV1Mp2x" alt="회원 정보 수정 화면" width="500"/>
</p>

---

> ✅ 이로써 **회원 관리 기능**은 Svelte 프론트엔드와 Spring Boot 백엔드가 완전히 연동된 상태에서 성공적으로 구현되었습니다.

---

※ 다음은 "경매품 등록 및 관리" 기능으로 이어집니다.
