<div align="center">

# 👋 김영환 | Backend-focused Developer

Spring Boot 기반 백엔드 개발을 중심으로 학습하고 있으며,  
React 연동과 Docker 기반 배포까지 경험한 개발자입니다.

서버와 클라이언트 간 데이터 흐름, 인증 처리, DB 설계, API 연동에 관심이 있습니다.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-youngwhan0420--sketch-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/youngwhan0420-sketch)

</div>

---

## 🛠 Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-764ABC?style=for-the-badge)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)

### Database / Infra

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### AI / Voice

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

---

## 📁 Projects

### 🏃 Route In

> 운동 커뮤니티 웹 서비스  
> 3인 팀 프로젝트 · 팀원 · 2026.01 ~ 2026.02

Kakao Map 기반 러닝 코스 공유와 실시간 채팅 기능을 제공하는 운동 커뮤니티 웹 서비스입니다.

#### 주요 구현 내용

- **Java · Spring Boot · MyBatis** 기반 게시판, 코스, 루틴, 팔로우 API 구현
- **Spring Security · JWT · OAuth2** 기반 로그인 및 사용자 인증 흐름 구성
- **MySQL** 기반 사용자, 게시글, 코스, 채팅, 알림 데이터 구조 설계
- **React · React Query · Zustand · Axios**를 활용한 서버 데이터 조회 및 상태 관리 처리
- **WebSocket(STOMP)** 기반 실시간 채팅 및 알림 시스템 구현
- **Kakao Map API** 기반 러닝 코스 생성, 거리 계산, 지도 기반 코스 공유 기능 구현
- **Firebase Storage**를 활용한 프로필 이미지 관리
- **Gemini API**를 활용한 사용자 맞춤 운동 추천 기능 구현
- **Docker · Nginx · GCP · GitHub Actions** 기반 배포 자동화 구성

#### 사용 기술

`Java` `Spring Boot` `MyBatis` `Spring Security` `JWT` `OAuth2`  
`React` `React Query` `Zustand` `Axios` `MySQL`  
`WebSocket(STOMP)` `Docker` `Nginx` `GCP` `GitHub Actions`

---

### 🎙️ Mama Papa Teller

> 부모 음성 클로닝 기반 AI 구연동화 서비스  
> 6인 팀 프로젝트 · 팀원 · 2026.04 ~ 2026.05

부모의 목소리를 복제하여 감정 표현이 담긴 음성으로 동화를 읽어주는  
태블릿 기반 인터랙티브 구연동화 서비스입니다.

#### 주요 구현 내용

- **FastAPI** 기반 동화 목록, 음성 등록, TTS 스트리밍, 퀴즈 API 구현
- **React · Vite** 기반 태블릿형 동화 UI 구성
- **MediaRecorder API**를 활용한 부모 음성 녹음 기능 구현
- **DashScope Qwen3 TTS API**를 활용한 부모 목소리 등록 및 음성 합성 처리
- **Pydub · FFmpeg**를 활용한 녹음 파일 16kHz mono WAV 형식 변환
- **StreamingResponse**를 활용한 장면별 음성 데이터 스트리밍 처리
- **Docker** 기반 Hugging Face Spaces 배포 환경 구성

#### 사용 기술

`Python` `FastAPI` `Uvicorn` `React` `Vite`  
`MediaRecorder API` `DashScope Qwen3 TTS` `Pydub` `FFmpeg`  
`Docker` `Hugging Face Spaces`

---

## 📌 Focus

```txt
REST API 설계 및 구현
MyBatis 기반 데이터 조회 및 저장 로직 처리
Spring Security + JWT 인증 흐름 구성
React와 백엔드 API 연동
서버 상태 관리 및 캐시 무효화 처리
Docker 기반 배포 환경 구성
---

## 📚 Currently Learning

- Spring Boot 기반 백엔드 구조 설계
- 데이터베이스 모델링 및 SQL 최적화
- 인증/인가 및 보안 흐름
- AI API 연동 및 음성 데이터 처리

---

## 📫 Contact

- GitHub: [youngwhan0420-sketch](https://github.com/youngwhan0420-sketch)
