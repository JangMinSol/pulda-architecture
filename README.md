# Pulda Learning Platform Architecture

Pulda는 교육 플랫폼으로  
단계형 학습, Q&A 커뮤니티, 학습 플래너 등 학습 중심 기능을 제공하는 서비스입니다.

---

## Tech Stack

- **Frontend**: Flutter / Dart
- **Backend**: Python (Flask)
- **Database**: PostgreSQL
- **API**: REST API

---

## System Architecture

Mobile App  
- Flutter 기반 모바일 애플리케이션

Backend Server  
- Python Flask 기반 REST API 서버

Database  
- PostgreSQL

---

## Key Features

### Step-based Learning
- 단계형 학습 흐름을 지원하기 위한 PostgreSQL 데이터 모델 설계
- 학습 단계 조회 및 진행 상태 관리를 위한 Flask REST API 개발

### Q&A Community
- 사용자 질문 및 답변 등록 · 조회 기능을 위한 REST API 개발
- Flutter 기반 질문 피드 및 상세 화면 UI 구현

### Study Planner
- 사용자 학습 계획 및 진행 상태 관리 기능 구현
- 학습 계획 조회 및 상태 관리 REST API 개발

### AI Workbook
- 사용자 학습 수준 및 난이도 기반 문제 생성 기능 구현
- 맞춤형 문제 조회를 위한 REST API 개발
