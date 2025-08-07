<h1 align="left">Anne Maier입니다.</h1>
<h3 align="left">MSA 환경에서 확장 가능한 백엔드 시스템을 설계하는 개발자입니다.</h3>

<p align="left">

🔭 현재는 팀 소중한 기억을 통해 인지 건강 증진을 돕는 AI 서비스 <strong>'기억의 정원'</strong>을 개발하고 있습니다.<br>

💡 각 서비스의 목적에 맞는 최적의 기술을 선택하고, 견고한 데이터 파이프라인과 자동화된 아키텍처를 구축하고자 합니다..
</p>

<h3 align="left">연락처 (Connect with me)</h3>
<p align="left">
hhch98@gmail.com
</a>
</p>

<h3 align="left">기술 스택 (Tech Stack)</h3>

<details>
<summary><b>Languages & Backend</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>Python:</b> FastAPI를 활용하여 MSA 환경의 백엔드 서비스를 표준화하고, 데이터 분석 및 AI 모델 서빙 파이프라인을 구축합니다.</li>
<li><b>Node.js:</b> Express 프레임워크와 Socket.IO를 사용하여 실시간 통신이 필요한 서비스를 개발합니다.</li>
<li><b>Rust:</b> Tokio 런타임을 기반으로 높은 동시성 처리가 요구되는 실시간 데이터 분석 웹소켓 서버를 개발한 경험이 있습니다.</li>
</ul>
</div>
</details>

<details>
<summary><b>Database & Message Queue</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>PostgreSQL & MySQL:</b> SQLAlchemy(ORM)와 함께 사용하여 RDBMS를 설계하고 운영합니다. (Neon DB 경험 포함)</li>
<li><b>Apache Kafka:</b> MSA 환경에서 서비스 간 비동기 통신을 구현하여 시스템 결합도를 낮추고 데이터 파이프라인을 구축합니다.</li>
</ul>
</div>
</details>

<details>
<summary><b>AI / LLM</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>OpenAI API:</b> GPT(질문/설명 생성), DALL-E(이미콘 생성), Whisper(STT) 등 다양한 모델을 활용하여 서비스의 핵심 AI 기능을 구현합니다.</li>
<li><b>Dify:</b> LLM Ops 플랫폼인 Dify를 활용하여 RAG(검색 증강 생성) 파이프라인을 구축하고, 지식 베이스와 워크플로우를 통해 고도로 개인화된 AI 경험을 제공합니다.</li>
</ul>
</div>
</details>

<details>
<summary><b>DevOps & Cloud</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>Containerization:</b> Docker를 사용하여 모든 서비스를 컨테이너화하고, Docker Compose를 통해 통합 로컬 개발 환경을 구축합니다.</li>
<li><b>Orchestration:</b> Kubernetes(k8s)를 사용하여 컨테이너화된 애플리케이션을 배포하고 운영한 경험이 있습니다.</li>
<li><b>Cloud:</b> AWS의 EC2, S3, ALB, RDS, ElastiCache, SES, SNS 등 다양한 서비스를 활용하여 인프라를 설계하고 운영합니다.</li>
<li><b>CI/CD:</b> GitHub Actions를 사용하여 테스트, 빌드, 배포 자동화 파이프라인을 구축합니다.</li>
</ul>
</div>
</details>

<h3 align="left">프로젝트 경험 (Project Experience)</h3>

<!-- 현재 프로젝트: 기억의 정원 -->

<details open>
<summary><b src="https://github.com/orgs/kibwa-fullstack-web-team1/repositories">🌳 기억의 정원 (Garden of Memories) - AI 기반 인지 건강 증진 서비스 (진행중)</b></summary>
<div markdown="1" style="padding-left: 20px;">
<p>사용자의 소중한 기억을 디지털 정원으로 시각화하고, RAG(검색 증강 생성) 파이프라인을 통해 개인화된 AI 경험을 제공하는 MSA 기반 서비스입니다.</p>
<ul>
<li>
<strong>아키텍처 설계:</strong>
<ul>
<li>모든 서비스를 <strong>Python(FastAPI)</strong> 기반으로 표준화하고, <strong>Docker Compose</strong>를 통해 통합 개발 환경을 구축했습니다.</li>
<li>서비스 간의 비동기 통신을 위해 <strong>Apache Kafka</strong>를 메시지 브로커로 도입하여 시스템의 결합도를 낮추고 확장성을 확보했습니다.</li>
<li><strong>PostgreSQL(Neon DB)</strong>과 <strong>SQLAlchemy(ORM)</strong>를 사용하여 데이터베이스를 관리합니다.</li>
</ul>
</li>
<li>
<strong>핵심 서비스 개발:</strong>
<ul>
<li><strong>RAG & Dify 파이프라인 구축:</strong> 사용자의 기억 데이터를 <strong>Dify</strong> 지식 베이스와 동기화하고(<code>dify-data-sync-service</code>), Dify 워크플로우를 활용하여 개인화된 '오늘의 질문'(<code>daily-question-service</code>)과 AI 보상 이미지(<code>reward-service</code>)를 생성하는 RAG 파이프라인의 핵심 로직을 개발했습니다.</li>
<li><strong>AI 기반 보상 시스템(<code>reward-service</code>):</strong> <strong>Kafka Consumer</strong>를 통해 비동기적으로 보상 생성 요청을 처리하고, Dify 워크플로우와 <strong>DALL-E API</strong>를 연동하여 사용자의 기억을 기반으로 한 개인화된 픽셀 아트 이미지를 생성하여 S3에 저장하는 기능을 구현했습니다.</li>
<li><strong>음성 분석(<code>voice-analysis-service</code>):</strong> <strong>Whisper API</strong>로 사용자의 음성 답변을 텍스트로 변환하고, <strong>librosa</strong>와 머신러닝 모델(<strong>XGBoost</strong>)을 활용해 인지 건강 점수를 산출하는 기능을 개발했습니다.</li>
</ul>
</li>
<li>
<strong>클라우드 및 인프라:</strong>
<ul>
<li><strong>AWS S3</strong>를 이미지 및 음성 파일의 저장소로 활용하고, <strong>AWS SES/SNS</strong>를 통해 보호자에게 주간 보고서 및 알림을 발송하는 기능을 구현했습니다.</li>
<li>중앙화된 <code>operations</code> 서비스를 통해 전체 MSA 환경의 Docker Compose 설정과 배포 스크립트를 관리합니다.</li>
</ul>
</li>
</ul>
</div>
</details>

<!-- 이전 프로젝트: Attention -->

<details>
<summary><b>👁️ Attention: 웹캠 기반 실시간 집중도 분석 서비스</b></summary>
<div markdown="1" style="padding-left: 20px;">
<p>실시간으로 사용자의 집중도를 측정하고, 분석 리포트와 AI 코칭 피드백을 제공했던 프로젝트입니다. 전체 코드는 <a href="https://www.google.com/search?q=https://github.com/kibwa-fullstack-web-team1/attention-ops">하나의 모노레포</a>에서 관리되었습니다.</p>
<ul>
<li><strong>Polyglot Backend:</strong> <strong>Rust</strong>(실시간 데이터 처리), <strong>Python/FastAPI</strong>(보고서 API), <strong>Node.js/Express</strong>(클라이언트 서비스) 등 각 목적에 맞는 언어와 프레임워크를 조합하여 MSA를 구축했습니다.</li>
<li><strong>AI & Data Handling:</strong> <strong>EXAONE</strong> 모델을 파인튜닝하여 개인화된 코칭 피드백을 제공하고, Python 스크립트로 학습용 데이터셋을 직접 생성 및 관리했습니다.</li>
<li><strong>DevOps & Cloud:</strong> <strong>Docker/Kubernetes</strong>를 사용해 서비스를 배포하고, <strong>GitHub Actions</strong>로 CI/CD를 자동화했으며, <strong>AWS</strong>(EC2, S3, ALB 등)를 활용하여 전체 인프라를 구축했습니다.</li>
</ul>
</div>
</details>
