<p align="center">
  <img src="https://github.com/bigmooon/bigmooon/blob/main/src/header.png?raw=true" alt="Junghee Im header banner" />
</p>

<h1 align="center">임정희 | LLM Application Engineer</h1>

<p align="center">
  아이디어를 실제로 사용할 수 있는 웹·앱으로 만드는 개발자입니다.<br/>
  화면과 서버, AI 기능이 자연스럽게 이어지는 제품을 고민합니다.
</p>

<p align="center">
  <a href="https://github.com/bigmooon?tab=repositories">Repositories</a>
  ·
  <a href="https://github.com/bigmooon?tab=projects">Projects</a>
</p>

## About

- LangGraph·LangChain 기반 에이전트 워크플로와 RAG 시스템을 설계합니다.
- LLM 출력을 스키마, 골든셋, 회귀 테스트로 검증하는 과정에 관심이 많습니다.
- Python 백엔드와 AI 서버를 연결하고 Docker·GitHub Actions 기반 배포 환경을 구성합니다.
- 기능 구현보다 먼저 문제 정의, 실패 조건, 평가 기준을 명확히 만드는 방식을 선호합니다.

## Featured Projects

### [AIGO-V2](https://github.com/bigmooon/aigo-youth) — 근거 제시형 임대차 계약서 분석

법률 Q&A 챗봇을 계약서 전체를 먼저 검사하는 evidence-first 탐지 시스템으로 개인 재설계했습니다.

- 계약서 조항 분해 → 법령·판례·표준계약서 근거 검색 → 발견 유형 리포트
- 주관적인 위험 등급 대신 검증 가능한 근거와 식별자를 제시하도록 출력 책임 범위 설계
- 골든셋 기반 자동 평가와 CI 회귀 테스트 구조 도입
- `Python` `LangGraph` `RAG` `Qdrant` `Streamlit` `GitHub Actions`

### 몽글마을 — AI 캐릭터와 함께하는 To-do Gamification

애착인형 사진으로 생성한 AI 캐릭터가 자연어 목표를 실행 가능한 할 일과 퀘스트로 바꾸고, 완료 결과를 피드와 마을 성장으로 연결하는 팀 프로젝트입니다.

- **담당:** 시스템 아키텍처 설계·문서화, Django ↔ FastAPI AI 서버 연동 구조 및 배포 흐름 설계
- **AI 흐름:** 캐릭터 생성 · TODO 분해 · 퀘스트 생성 · 피드 생성 에이전트
- **내부 모델 평가:** TODO 분해 5/5, JSON 파싱 5/5, 이미지 생성 19/20, 평균 SSIM 0.8378
- **시스템 검증:** 31개 시나리오, 295개 세부 항목 모두 통과
- `Django` `FastAPI` `LangChain` `Qwen2.5-7B` `SDXL + LoRA` `RunPod` `AWS` `Docker`

[AI repository](https://github.com/bigmooon/mongle-ai) · [Backend repository](https://github.com/bigmooon/mongle-server) · [Team organization](https://github.com/mong-studio)

> 수치는 팀 산출물의 제한된 내부 테스트셋 결과이며, 실제 사용자 환경의 성능을 의미하지 않습니다.

### [Love Imbalance Detector](https://github.com/bigmooon/love-imbalance-detector) — 카카오톡 대화 기반 관계 지표 분석

1:1 카카오톡 대화를 분석해 대화 지배성과 관계 의존도를 설명 가능한 지표로 시각화하는 개인 프로젝트입니다.

- KLUE-BERT 감정 분류와 KR-SBERT 문장 임베딩을 결합한 한국어 대화 분석
- 선톡, 답장 시간, 연속 메시지, 감정 비대칭, QA 유사도를 분리해 계산
- 대화 세션 분리부터 가중 지표 계산, Plotly 시각화까지 하나의 Streamlit 흐름으로 구현
- `Python` `Hugging Face` `Pandas` `Plotly` `Streamlit`

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

## What I value

```text
Problem definition → measurable acceptance criteria → implementation → evaluation → iteration
```

기능을 구현하는 데서 멈추지 않고, 사용 흐름과 결과를 확인하며 끝까지 다듬습니다.
