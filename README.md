<div align="center">

# Hi, I'm Minsu Cha 👋

**Backend Developer** · 직접 운영하며 만난 병목을 비용과 안전성을 통제할 수 있는 자동화로 해결하고, 그 해결이 남긴 다음 질문을 따라가며 성장합니다.

📫 **gkdltpa9987@gmail.com** · 🌐 [Portfolio](https://portfolio-olive-chi-5y8wahaumf.vercel.app/) · 📄 [Resume](https://portfolio-olive-chi-5y8wahaumf.vercel.app/resume)

</div>

<br>

## Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Messaging & Communication**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

<br>

## Featured Projects

### 🍽️ [바이트픽 — 실서비스 운영 (30개 점주)](https://github.com/Bite-Pick/bitepick-back)
B2B 외식업 플랫폼 Backend를 책임지고 개발한 실서비스 프로젝트.
- 앱스토어 다운로드 순위 163위 달성
- 정적 분석 도구(JaCoCo, SpotBugs) 도입 — SpotBugs High/Medium 이슈 전체 해소, Branch 커버리지 19%→40.2%
- S3 PreSigned URL 업로드 플로우로 서버 부하 감소

### 🤖 [LLM 기반 자동 모니터링 시스템](https://github.com/Minsu4302/Auto-Logging-Monitoring-By-LLM)
수동 모니터링 병목을 자연어 챗봇 하나로 해결한 운영 자동화 시스템.
- 자연어 → Intent 분류 → 화이트리스트 검증 → 실행 파이프라인으로 임의 명령 실행 차단
- LLM이 생성한 PromQL을 Prometheus API로 자동 검증·보정해 환각 대응
- 실서비스(Spring Boot + OTel) 연동 완료

### ⚙️ [하네스 엔지니어링 + AI Orchestration](https://github.com/Minsu4302/Harness_Infra)
AI 에이전트 실행 환경 전체를 설계한 2레이어 인프라 (Harness + Orchestration).
- Skeleton-of-Thought 기법으로 CoT 출력 토큰 75% 절감
- PR 오픈 시 GitHub Actions로 다중 에이전트(review/security/test-gen) 병렬 실행
- 멀티모델 라우팅(Claude/Gemini/GPT)으로 역할별 동적 배분

### 🛰️ [TaskScope — AI Agentic Task Tracer for Multi-Agent Systems](https://github.com/Minsu4302/taskscope)
멀티 에이전트 시스템의 task 단위 trace·비용 추적 시스템.
- dispatcher부터 LLM 호출까지 19개 span을 단일 trace로 귀속 — propagation 정확도 100%
- Prometheus 기반 비용 가드레일로 모델 자동 강등, 건당 비용 3.2배 절감
- 비용 절감이 결함 탐지 품질에 미치는 영향까지 정직하게 측정해 가드레일의 한계 식별

### 🏗️ [인프라 자동화 / CI·CD 파이프라인 구축](https://github.com/Minsu4302/DevOps_Infra)
Terraform·Ansible·Kubernetes 기반 end-to-end 무인 배포 파이프라인.
- GitLab Webhook → Jenkins → Docker Registry → K8s 롤링 배포까지 전 단계 자동화
- MetalLB·Calico로 베어메탈 클러스터 네트워킹 구성

<br>

## Top Languages

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Minsu4302&layout=compact&hide_border=true&theme=default" alt="Top Languages" width="45%" />

</div>
