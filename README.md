## 📁 1. 프로젝트

### 🏃 Route In — 운동 커뮤니티 웹 서비스 (팀 프로젝트)

> 3인 팀 팀원 · 2026.01 ~ 2026.02 (5주)

Kakao Map 기반 러닝 코스 공유 + 실시간 채팅 커뮤니티 서비스
## 🛠 Tech Stack
- **Java · Spring Boot · MyBatis** 기반으로 게시판, 코스, 루틴, 팔로우 API 구현
- **Spring Security · JWT · OAuth2**를 활용한 로그인 및 사용자 인증 흐름 구성
- **MySQL**을 활용해 사용자, 게시글, 코스, 채팅, 알림 데이터 구조 설계
- **React · React Query · Zustand · Axios**를 활용해 서버 데이터 조회 및 상태 관리 처리
- **WebSocket(STOMP)** 기반 실시간 채팅 및 알림 시스템 구현
- **Kakao Map API**를 활용한 러닝 코스 생성, 거리 계산, 지도 기반 코스 공유 기능 구현
- **Firebase Storage**를 활용한 프로필 이미지 관리
- **Gemini API**를 활용한 사용자 맞춤 운동 추천 기능 구현
- **Docker · Nginx · GCP · GitHub Actions** 기반 배포 자동화 구성


## 📁 2. 프로젝트

### mama-papa-tellar — 부모 음성 클로닝 기반 AI 구연동화 서비스(팀 프로젝트)

> 6인 팀 팀원 · 2026.04 ~ 2026.05 (3주)
> 
> 부모의 목소리를 복제하여 감정 풍부하게 읽어주는 태블릿 기반 인터랙티브 구연동화 서비스
## 🛠 Tech Stack
- **FastAPI** 기반으로 동화 목록, 음성 등록, TTS 스트리밍, 퀴즈 API 구현
- **React + Vite** 기반 태블릿형 동화 UI 구성
- **MediaRecorder** API를 활용해 부모 음성 녹음 기능 구현
- **DashScope Qwen3** TTS API를 활용해 부모 목소리 등록 및 음성 합성 처리
- **Pydub + FFmpeg**를 활용해 녹음 파일을 16kHz mono WAV 형식으로 변환
- **StreamingResponse**를 활용해 장면별 음성 데이터를 스트리밍 방식으로 전달
- **Docker** 기반 Hugging Face Spaces 배포 환경 구성
