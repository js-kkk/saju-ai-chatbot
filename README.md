# 🔮 사주 AI 챗봇(https://ee130360e5c2e0983a.gradio.live)

> **📅 프로젝트 기간:** 2025년 4월 20일(토) ~ 2025년 4월 24일(목)

## 📌 프로젝트 개요
한국 전통 명리학(사주팔자)에 기반한 AI 챗봇<br/>
생년월일과 태어난 시간을 입력하면, 음력 변환 → 분석에 필요한 정보 추출 → 사주 분석 → 대화형 상담 진행<br/>
**한국천문연구원 OpenAPI**와 **EEVE-Korean-10.8B LLM**, **Gradio**를 활용하여 사주 정보를 제공

## 🖼️ 메인 화면

![Image](https://github.com/user-attachments/assets/a9d2e510-fc70-442b-b30c-0be15c27dae3) 
![Image](https://github.com/user-attachments/assets/68bb44fa-26e0-49ad-a6c1-327b741cfdd9) 

## 실제 플레이 화면

![Image](https://github.com/user-attachments/assets/62d760c4-b2b2-4b24-9bae-54796f7f4759) 
![Image](https://github.com/user-attachments/assets/243a9fb0-a7b9-44c4-8a0c-b3a1f4997389) 

---

## 🛠 기술 스택

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-FF6F61?style=for-the-badge&logo=gradio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/EEVE_Korean_10.8B-FFCC00?style=for-the-badge&logoColor=black"/>
</div>

---

## 💡 주요 기능

### 📆 사용자 입력 및 사주 분석에 필요한 정보 추출
- 이름/생년월일/태어난 시간 입력, 양력/음력 여부 선택
- 한국천문연구원 OpenAPI를 활용해 **정확한 음력 변환 및 간지 정보(세차, 월건, 일진)** 자동 파싱

### 🧠 사주 분석
- 이름/생년월일/태어난 시간을 기반으로 한 정교한 사주 분석
- **분석 항목**:
  1. 사주의 기초 정보 구성 (천간/지지/오행 등)
  2. 기본 성격 및 성향 분석
  3. 대운 분석
  4. 세운 흐름 및 시기별 특징
  5. 살(殺)과 신살 분석
  6. 신기와 귀문의 시기
  7. 단점 정리
  8. 장점 정리

### 💬 챗봇 대화 기능
- `ChatInterface`를 이용한 대화형 상담
- 사용자가 사주에 대해 추가 질문을 할 수 있으며, 지속적 맥락을 유지

---

## 📈 개선 방향
- ✅ **LLM 모델 변경**  
  EEVE 모델이 아닌 성능이 좋은 다른 모델 적용
- ✅ **사주 도메인 튜닝**  
  EEVE 모델에 실제 사주 명리학 데이터를 추가 학습시켜 더 정확한 해석 가능
- ✅ **사주 관련 질문 예시 버튼**  
  “나의 성격은 어떤가요?”, “올해의 운세는?” 등 추천 질문 탭 추가

