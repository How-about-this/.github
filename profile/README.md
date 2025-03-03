# 혼자야? - 위치, 취향 기반 채팅 매칭 서비스
<img width="800" alt="image" src="https://github.com/user-attachments/assets/e57cb6ac-3185-4790-a2bd-e28d4474e892" />

<br><br>

## 📕 프로젝트 소개
'혼자야?' 웹 애플리케이션은 [카카오X구름 기업 연계 프로젝트]로 카카오 API들을 적극 활용하여 현대 사회에서 바쁜 일상을 보내는 사람들이 소셜 라이프를 갈망하며 느끼는 외로움을 해소할 수 있도록 도와주는 웹 서비스입니다.
취향 및 위치 기반 추천 알고리즘으로 1대1 랜덤 채팅, 다대다 랜덤 채팅, 커뮤니티 기능을 통해 사용자들이 쉽게 접근하여 매력적인 만남을 경험할 수 있는 플랫폼을 제공합니다.

<br><br>

## ⏰ 개발 기간
2024-05-13 ~ 2024-06-20

<br><br>

## 🛠️ 기술 스택
### Front-End
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=Typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat-square&logo=Tailwind CSS&logoColor=white"/> <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white">

### Back-End
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>

### DevOps
<img src="https://img.shields.io/badge/Kakao Cloud-FFCD00?style=flat-square&logo=kakao&logoColor=black"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/> 

<br><br>

## ▶️ 시연 영상

### 로그인, 회원가입, 로그아웃
<img src="https://github.com/user-attachments/assets/e45903b7-f4a6-4cb3-8ab2-a5934bd55fcc" width="500"/>

<br>

### 마이페이지
<img src="https://github.com/user-attachments/assets/8b7931a1-662b-420c-8c6d-2155bab6163c" width="500"/>

<br>

### 프로필 이미지 갤러리
<img src="https://github.com/user-attachments/assets/a1eaefd6-742b-4e32-9579-2bd59ed0274a" width="500"/>

<br>

### 게시판
<img src="https://github.com/user-attachments/assets/61e1422e-da78-44c6-9f62-1c21694c1fdb" width="500"/>

<br>

### 매칭 및 채팅
<img src="https://github.com/user-attachments/assets/2696b07b-164c-4222-bd4b-f1dcf3c73724" width="500"/>

<br><br>

## 📖 ERD
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/491d8e86-df96-442e-87ab-d5d2b0305a53" />

<br><br>

## ⚙️ 아키텍처 구성도
<img width="800" alt="image" src="https://github.com/user-attachments/assets/33cec456-c19e-4ad0-90fe-9d8d7037724b" />

<br><br>

## 🤝 커밋 컨벤션
- `Feat`: 새로운 기능 추가
- `Fix`: 버그 수정
- `Docs`: 문서 수정
- `Style`: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- `Refactor`: 코드 리팩토링
- `Test`: 테스트 코드, 리팩토링 테스트 코드 추가
- `Chore`: 빌드 업무 수정, 패키지 매니저 수정, production code와 무관한 부분들 (.gitignore, build.gradle 같은)
- `Comment`: 주석 추가 및 변경
- `Remove`: 파일, 폴더 삭제
- `Rename`: 파일, 폴더명 수정
- `Design`: CSS 등 사용자가 UI 디자인을 변경했을 때

<br><br>

## 🌊 브랜치 전략
Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용합니다.
- main 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
- dev 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
- feat 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해줍니다. (예: feat/chat)
