# 🌍 PIN-UP 프로젝트 개요

여행을 기록하고, 영토를 넓히며, 전국을 점령하라!  
**PIN-UP(Pin-Up)**은 국내 여행 경험을 *데이터와 시각화로 즐기는* 새로운 형태의 여행 기록 서비스입니다.

---

## 🧩 프로젝트 개요

최근 MZ세대를 중심으로 **여행 인증·기록 문화**가 빠르게 확산되며,  
단순히 방문을 기록하는 단계를 넘어  
**경쟁 요소와 시각적 재미를 제공하는 서비스**에 대한 수요가 증가하고 있습니다.

PIN-UP은 사용자가 실제 방문한 지역을  
**지도 위 ‘영토(territory)’로 점령하는 방식**으로 여행을 기록하게 합니다.

이를 통해
- 나만의 여행 지도 만들기
- 지역 정복 현황 시각화
- 월간·전체 랭킹 경쟁
- 여행 기록 기반의 커뮤니티 요소

등을 제공하는 **게임형 여행 기록 플랫폼**입니다.

국내 여행을 더욱 흥미롭고 도전적으로 만드는 새로운 경험을 목표로 합니다.


# 🛠 Tech Stack

### 💻 Backend
![Java](https://img.shields.io/badge/Java-21-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-JWT%20%2B%20OAuth2-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-Hibernate-59666C?style=for-the-badge)
![Swagger](https://img.shields.io/badge/Swagger-OpenAPI_3-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### 🎨 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-HTTP_Client-5A29E4?style=for-the-badge)

### 🪄 Design
![Figma](https://img.shields.io/badge/Figma-Design-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

### 🗄️ Database
![MariaDB](https://img.shields.io/badge/MariaDB-Database-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Cache-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🤖 AI / OCR Service
![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-OCR_Service-009688?style=for-the-badge&logo=fastapi&logoColor=white)
[EasyOCR](https://img.shields.io/badge/EasyOCR-Korean_Text_Recognition-FF6F00?style=for-the-badge)


### 🚀 DevOps / Infrastructure
![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy-009639?style=for-the-badge&logo=nginx&logoColor=white)

### ⚙️ Tools
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-IDE-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-Editor-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-API_Testing-FF6C37?style=for-the-badge&logo=postman&logoColor=white)


## 💻 Backend
<p>
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?logo=spring&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?logo=springsecurity&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square"/>
  <img src="https://img.shields.io/badge/JWT-black?logo=jsonwebtokens&style=flat-square"/>
  <img src="https://img.shields.io/badge/MyBatis-b31b1b?style=flat-square"/>
</p>


# ✨ 주요 기능 (Features)

## 🔐 Auth (인증)

### 👤 사용자(User)
- Google / Kakao / Naver OAuth2 기반 **소셜 로그인**
- 외부 플랫폼 인증 후 사용자 정보 자동 저장
- 세션 기반 사용자 로그인 상태 관리

### 🛡 관리자(Admin)
- **JWT 기반 인증**
- Access / Refresh Token 발급 및 검증
- 관리자 전용 세션/보안 처리

---

## ⚙️ Config (환경 설정)
- 글로벌 설정 및 **공통 예외 처리**
- CORS 설정
- Spring Security 환경 구성
- Swagger 기반 API 문서 자동화

---

## 🏳️ Conquer (영토 점령)
- 사용자의 실제 방문 지역을 **지도 기반으로 점령 등록**
- 지역 좌표(Polygon / GPS)와 연동된 점령 정보 저장
- 지역별 점령 이력 조회 & 정복 현황 **시각화**

---

## 📝 Feed (피드)
- 유저별 여행 기록 피드 생성
- 게시글 **작성 / 수정 / 삭제**
- 좋아요, 댓글 등 **소셜 인터랙션 기능**
- 사진 기반 여행 기록 관리

---

## 🏠 Home (홈)
- 서비스 메인 화면
- 요약 통계(점령 수, 활동 포인트)
- 최근 점령 지역 / 최신 공지 요약 표시
- 오늘의 추천 기능(선택)

---

## 👥 Member (회원)
- 회원 프로필 조회 및 수정
- 닉네임 / 성별 / 선호 지역 관리
- 포인트, 활동 통계, 등급 표시
- 내 점령 지역 리스트 조회
- 구매한 아이템 조회 및 적용

---

## 📢 Notice (공지)
- 공지사항 **등록 / 수정 / 조회**
- 업데이트 알림 및 이벤트 안내

---

## 🔔 Notification (알림)
- 점령, 댓글, 좋아요 등 **실시간 알림**
- 읽음 / 미확인 상태 관리
- SSE(Server-Sent Events) 기반 실시간 푸시

---

## 🏆 Ranking (랭킹)
- 점령 지역 수 + 활동 점수 기반 순위 산정
- **지역별 / 전국 단위 랭킹 제공**
- 월별 랭킹 자동 집계(스케줄러 연동)

---

## 📊 Report (리포트)
- 여행 통계 자동 생성
- 방문 횟수, 점령 비율 분석
- 지역별 정복 현황 **지도 시각화**

---

## 🛒 Store (상점)
- 아이템 목록 / 카테고리별 조회
- 아이템 **구매 / 장착 / 해제**
- 한정판 테마, 이벤트 아이템 관리

---

## 🎯 Recommendation (AI 여행 추천)
- 사용자 나이 / 성별 / 선호 카테고리 / 선호 계절 / 현재 계절 기반 맞춤 추천 팝업 이벤트 제공
- 여행지 점수 계산(카테고리 선호도, 계절 적합도, 연령대 가중치)을 통한 관광지 1곳 선정과 연관된 지역 관광지 2곳 추가 선정
- OpenAI GPT을 활용하여 관광지 3곳에 대한 **1일 여행 일정 자동 생성**


## 🗂️ 요구사항 명세서
[👉 요구사항명세서 자세히 보기](https://docs.google.com/spreadsheets/d/1Zkx9firrpHB_p1HVR-SOyMTRuEOYPh6jcCsCMcN00kU/edit?gid=113130719#gid=113130719)
<br><br>

## 📋 와이어프레임
[👉 와이어프레임 자세히 보기](https://www.figma.com/design/ijWgL81qNKehtyY8nsjgwV/PIN-UP?node-id=0-1&p=f&t=K7tTnCVhZXM4uh7F-0)
<br><br>

## 🧩 화면설계서
[👉 화면설계서 자세히 보기](https://docs.google.com/spreadsheets/d/15GUetaqF7ZzyMlfNaMSTGY3QHphQJDatddCM2ZH7ZNg/edit?gid=0#gid=0)
<br><br>

## ✅ 테스트 케이스

<details>
  <summary>로그인</summary>

- 구글 로그인<br>
  ![Image](https://github.com/user-attachments/assets/e7f5e196-9fc2-4a84-aaba-e3ce22eca34e)

- 네이버 로그인<br>
  ![Image](https://github.com/user-attachments/assets/88810a05-d6ce-4365-81c3-bf9d27716fce)

- 카카오 로그인<br>
  ![Image](https://github.com/user-attachments/assets/ff5d2d9e-0763-4720-9d23-7a192bcc4613)

- 관리자 로그인<br>
  ![Image](https://github.com/user-attachments/assets/fc78136b-ccff-46f2-804e-b545005132f1)

</details>

<details>
  <summary>관리자 회원관리</summary>

- 회원 정지<br>
  ![Image](https://github.com/user-attachments/assets/a6ea0053-7797-4360-9d43-6ae854b40bc7)

- 회원 활성화<br>
  ![Image](https://github.com/user-attachments/assets/d817200c-ceda-4bb8-85a6-0452cee3513d)

- 페이지네이션<br>
  ![Image](https://github.com/user-attachments/assets/15c6df88-d63d-44e7-bf19-ea32d56ec23e)

</details>

<details>
  <summary>홈 화면</summary>

- 홈<br>
  <img width="700" alt="Image" src="https://github.com/user-attachments/assets/a4690cc2-711d-46d5-827c-4e690a3f9948" />

- 추천 팝업<br>
  ![진짜추천팝업](https://github.com/user-attachments/assets/028624b1-a25d-41da-9676-208c7e4848cb)

- 랭킹 전체보기<br>
  ![Image](https://github.com/user-attachments/assets/7bce638d-865f-42c5-9697-aa79b618ac79)

- 공지사항 이동<br>
  ![Image](https://github.com/user-attachments/assets/832f345c-eba1-4564-9257-f7ad36fda381)

</details>

<details>
  <summary>마이페이지</summary>

- 회원 정보 수정<br>
  ![Image](https://github.com/user-attachments/assets/f6fc7db4-8600-419c-9d8f-475d033527a9)

- 포인트 상세 내역 조회 이동<br>
  ![Image](https://github.com/user-attachments/assets/61697c32-2141-4d4a-b0bb-00da00d0ff8c)

- 내 피드 모아보기&클릭시 해당 피드로 이동<br>
  ![Image](https://github.com/user-attachments/assets/ccbdd0d2-cfb9-46c6-81a6-a6ddc70a24bc)

</details>

<details>
  <summary>피드</summary>

- 피드 작성<br>
  ![write-successimg](https://github.com/user-attachments/assets/b23f69fd-3147-4d63-9bbc-be80e45423a9)
 
- 피드 조회<br>
 ![list-successimg](https://github.com/user-attachments/assets/80494e33-ce71-44c3-8d24-5b1aac7b093a)

- 피드 수정<br>
  ![edit-successimg](https://github.com/user-attachments/assets/65a05779-9255-428d-90a3-f1442fc595a3)

- 피드 삭제<br>
  ![delete-successimg](https://github.com/user-attachments/assets/0f7ecc09-c784-4d09-8908-a7600dbef29b)

- 피드좋아요<br>
  ![feedlike-successimg](https://github.com/user-attachments/assets/0dbed72a-490d-47be-9772-8fff00eb7728)

</details>

<details>
  <summary>상점</summary>

- 아이템 등록<br>
![ezgif-1f2d9e2ff2f7290f](https://github.com/user-attachments/assets/fc9db298-dec8-41f0-834f-c810243d8f5a)

- 아이템 수정<br>
![아이템 수정](https://github.com/user-attachments/assets/f96fe94b-be6f-4d35-84f1-05230058689a)

- 아이템 삭제<br>
 ![아이템 삭제](https://github.com/user-attachments/assets/b5918312-0255-40e4-abc9-6e3803ede724)
 
- 아이템 조회<br>
![아이템 조회](https://github.com/user-attachments/assets/616facdb-00e8-4027-aa9e-90e686a86a7f)


</details>

<details>
  <summary>신고 처리</summary>

  - 신고 처리<br>
  ![신고 처리](https://github.com/user-attachments/assets/f8072048-7432-488a-90a5-087ae14b9891)
</details>

<details>
  <summary>공지사항</summary>

  - 공지사항<br>
  ![공지사항](https://github.com/user-attachments/assets/9d811aa8-2ded-4f9a-96c2-c9cb33a38cb1)
</details>

<details>
  <summary>사용자 알림</summary>

  - 사용자 알림<br>
  ![알림](https://github.com/user-attachments/assets/4740e163-f1f8-4cf0-8a73-c3610b872587)
</details>

<details>
  <summary>점령하기 - 점령지 추가</summary>

- 점령하기 - 점령지 추가<br>
  ![점령하기 기능.gif](../../Downloads/%EC%A0%90%EB%A0%B9%ED%95%98%EA%B8%B0%20%EA%B8%B0%EB%8A%A5.gif)
</details>

<details>
  <summary>점령하기 - 포인트 획득</summary>
  ![Screen-Recording-2025-11-27-at-10.50.36 AM_2.gif](../../Downloads/Screen-Recording-2025-11-27-at-10.50.36%E2%80%AFAM_2.gif)
- 점령하기 - 포인트 획득<br>
  
</details>
