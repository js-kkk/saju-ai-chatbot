# 🔮 사주 AI 챗봇

> **📅 프로젝트 기간:** 2025년 4월 20일(토) ~ 2025년 4월 24일(목)

한국 전통 명리학(사주팔자)에 기반한 AI 챗봇입니다.  
생년월일과 시간을 입력하면, 음력 변환 → 사주 분석 → 대화형 상담까지 자동으로 진행됩니다.  
**한국천문연구원 OpenAPI**와 **EEVE-Korean-10.8B LLM**, **Gradio**를 활용하여 직관적인 UI와 몰입형 상담 경험을 제공합니다.

---

## 🛠 기술 스택

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-FF6F61?style=for-the-badge&logo=gradio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/EEVE_Korean_10.8B-FFCC00?style=for-the-badge&logoColor=black"/>
</div>

- **LLM 모델:** Ollama 기반 EEVE-Korean-10.8B
- **UI/UX:** Gradio
- **API 연동:** 한국천문연구원 음력 변환 OpenAPI
- **백엔드:** Python, requests, datetime, ElementTree

---

## 💡 주요 기능

### 📆 사용자 입력 및 음력 변환
- 양력/음력 여부 선택
- 한국천문연구원 OpenAPI를 활용해 **정확한 음력 변환 및 간지 정보(세차, 월건, 일진)** 자동 파싱

### 🧠 사주 분석 (8단계)
- 이름/생년월일을 기반으로 한 정교한 사주 분석
- **분석 항목**:
  1. 사주의 기초 정보 구성 (천간/지지/오행 등)
  2. 성격과 장단점 분석
  3. 대운 분석
  4. 세운 흐름 및 시기별 특징
  5. 직업적성/관계운/재물운
  6. 신살/귀문살/역마살 등 포함
  7. 극복 방법 및 조언
  8. 사주 전체 해석 요약

### 💬 챗봇 대화 기능
- `ChatInterface`를 이용한 대화형 상담
- 사용자가 사주에 대해 추가 질문을 할 수 있으며, 지속적 맥락을 유지

### 🧩 유저 컨텍스트 저장
- 이름, 생년월일, 시간 정보를 저장하여 챗봇이 사용자의 맥락을 유지
- 추후 상담에서도 이전 대화 기반으로 응답 가능 

---


