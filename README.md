# IMK AI POC

IMK AI 구축 프로젝트의 실험용 POC(Proof of Concept) 저장소입니다.  
AI 기술의 실무 적용 가능성을 검토하고, 내부 역량 강화를 목표로 세 가지 방향성을 중심으로 개발을 진행합니다.

## 🎯 프로젝트 목표

### 1. GPT API 연동 백엔드 구축
- OpenAI GPT-3.5/4o API 연동
- Spring Boot 기반 채팅 백엔드 구축
- MongoDB를 이용한 채팅 기록 저장
- 간단한 Web UI 또는 Postman 기반 테스트

### 2. 오픈소스 LLM 모델 로컬 배포
- Meta LLaMA, Mistral 등의 모델을 로컬에서 실행
- Ollama 및 Docker 환경 구성
- GPT API와 유사한 방식으로 응답 API 제공

### 3. Python 기반 커스텀 AI 모델 개발
- Pandas, Scikit-learn, TensorFlow 등 활용
- 예측/분류 모델 직접 학습 및 추론
- 업무 데이터 기반 실험 및 분석

---

## 📂 프로젝트 구조 (예정)
📦 imk-ai-poc/
              ├── backend/ # GPT API 연동 백엔드 (Java, Spring Boot)

              ├── local-llm/ # Ollama 등 로컬 LLM 실험 폴더

              ├── ai-models/ # Python 기반 커스텀 모델 개발 폴더

              ├── docs/ # 기획서, 회의록, 발표자료 등

              ├── README.md

              ├── .gitignore

              └── LICENSE



---

## 🛠️ 기술 스택

- Java 21, Spring Boot 3.3.x
- Python 3.11, Jupyter, Scikit-learn, Pandas
- Docker, Ollama, MongoDB
- OpenAI GPT-3.5 / GPT-4o API

---


