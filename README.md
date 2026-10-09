<p align="center">
  <img src="https://github.com/bigmooon/bigmooon/blob/main/src/header.png?raw=true" alt="Junghee Im — LLM Application Engineer" />
</p>

<p align="center">
  화면과 서버, AI 기능을 연결해 실제로 사용할 수 있는 웹·앱을 만듭니다.
</p>

<p align="center">
  <a href="https://github.com/bigmooon?tab=repositories">Repositories</a>
  ·
  <a href="https://github.com/bigmooon?tab=projects">Projects</a>
</p>

## About

- 웹·앱의 사용자 흐름부터 백엔드와 AI 기능까지 하나의 제품으로 연결합니다.
- LangGraph·LangChain 기반 에이전트 워크플로와 RAG 시스템을 설계합니다.
- 스키마, 골든셋, 회귀 테스트와 배포 자동화를 통해 결과를 확인하고 개선합니다.

## Featured Projects

### [AIGO-V2](https://github.com/bigmooon/aigo-youth) — 근거 제시형 임대차 계약서 분석

- **문제:** 질문에만 답하는 법률 챗봇은 사용자가 놓친 위험 조항을 먼저 발견하기 어렵습니다.
- **역할:** 계약서 전체를 검사하는 evidence-first 탐지 흐름을 개인 프로젝트로 재설계하고 구현했습니다.
- **결과:** 조항 분해부터 법령·판례·표준계약서 검색, 근거 식별자 제시까지 연결하고 골든셋 기반 CI 회귀 테스트를 구성했습니다.
- **기술:** `Python` `LangGraph` `RAG` `Qdrant` `Streamlit` `GitHub Actions`

---

### 몽글마을 — AI 캐릭터와 함께하는 To-do Gamification

- **문제:** 막연한 목표를 구체적인 행동으로 옮기고 꾸준히 이어갈 동기가 필요합니다.
- **역할:** 시스템 아키텍처를 설계·문서화하고 Django와 FastAPI AI 서버의 연동 및 배포 흐름을 설계했습니다.
- **결과:** 캐릭터 생성, TODO 분해, 퀘스트·피드 생성 흐름을 연결했으며 내부 시스템 검증 31개 시나리오·295개 세부 항목을 통과했습니다.
- **기술:** `Django` `FastAPI` `LangChain` `Qwen2.5-7B` `SDXL + LoRA` `RunPod` `AWS` `Docker`

[AI repository](https://github.com/bigmooon/mongle-ai) · [Backend repository](https://github.com/bigmooon/mongle-server) · [Team organization](https://github.com/mong-studio)

<details>
<summary>내부 평가 결과와 해석 범위</summary>

- TODO 분해 5/5, JSON 파싱 5/5
- 이미지 생성 19/20, 평균 SSIM 0.8378
- 시스템 검증 31개 시나리오, 295개 세부 항목 통과

위 수치는 팀 산출물의 제한된 내부 테스트셋 결과이며 실제 사용자 환경의 성능을 의미하지 않습니다.

</details>

---

### [Love Imbalance Detector](https://github.com/bigmooon/love-imbalance-detector) — 카카오톡 대화 기반 관계 지표 분석

- **문제:** 대화 관계의 불균형은 단순 메시지 수만으로 설명하기 어렵습니다.
- **역할:** 데이터 전처리와 세션 분리부터 감정·응답·의존도 지표 계산, 시각화까지 전체 분석 흐름을 구현했습니다.
- **결과:** KLUE-BERT와 KR-SBERT를 결합해 선톡, 답장 시간, 감정 비대칭, QA 유사도를 분리하고 설명 가능한 지표로 시각화했습니다.
- **기술:** `Python` `Hugging Face` `Pandas` `Plotly` `Streamlit`

## Engineering Focus

**AI & LLM**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Frontend & Client**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Backend & Data**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Infra & Delivery**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![RunPod](https://img.shields.io/badge/RunPod-673DE6?style=flat-square&logoColor=white)

---

<p align="center">
  기능을 구현하는 데서 멈추지 않고, 사용 흐름과 결과를 확인하며 끝까지 다듬습니다.
</p>
