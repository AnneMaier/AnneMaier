<h1 align="left">Hi, I'm Hyuichan Hyun (Anne Maier)</h1>
<h3 align="left">An engineer proficient in AWS infrastructure and container technologies, equipped with strong backend capabilities.</h3>

<h3 align="left">Connect with me</h3>
<p align="left">
hhch98@gmail.com
</a>
</p>

<h3 align="left">Tech Stack</h3>

<details>
<summary><b>Languages & Backend</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>Python:</b> Standardized backend services in an MSA environment using FastAPI and built data analysis and AI model serving pipelines.</li>
<li><b>Node.js:</b> Developed services requiring real-time communication using the Express framework and Socket.IO.</li>
<li><b>Rust:</b> Have experience developing a real-time data analysis WebSocket server that required high concurrency processing, based on the Tokio runtime.</li>
</ul>
</div>
</details>

<details>
<summary><b>Database & Message Queue</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>PostgreSQL & MySQL:</b> Designed and operated RDBMS using SQLAlchemy (ORM). (Includes experience with Neon DB)</li>
<li><b>Apache Kafka:</b> Implemented asynchronous communication between services in an MSA environment to reduce system coupling and build data pipelines.</li>
</ul>
</div>
</details>

<details>
<summary><b>AI / LLM</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>OpenAI API:</b> Implemented core AI features of services by utilizing various models such as GPT (for generating questions/descriptions), DALL-E (for generating "emoticons"), and Whisper (STT).</li>
<li><b>Dify:</b> Built a Retrieval-Augmented Generation (RAG) pipeline using the LLM Ops platform, Dify, to provide a highly personalized AI experience through knowledge bases and workflows.</li>
</ul>
</div>
</details>

<details>
<summary><b>DevOps & Cloud</b></summary>
<div markdown="1" style="padding-left: 20px;">
<ul>
<li><b>Containerization:</b> Containerized all services using Docker and built an integrated local development environment with Docker Compose.</li>
<li><b>Orchestration:</b> Have experience deploying and operating containerized applications using Kubernetes (k8s).</li>
<li><b>Cloud:</b> Designed and operated infrastructure utilizing various AWS services such as EC2, S3, ALB, RDS, ElastiCache, SES, and SNS.</li>
<li><b>CI/CD:</b> Built automated testing, building, and deployment pipelines using GitHub Actions, AWS CodeBuild, and CodePipeline.</li>
</ul>
</div>
</details>

<h3 align="left">Recent Project</h3>

<!-- Current Project: Garden of Memories -->

<details open>
<summary><a href="https://www.google.com/search?q=https://github.com/orgs/kibwa-fullstack-web-team1/repositories">🌳 Garden of Memories - AI-Powered Cognitive Health Enhancement Service</a></summary>
<div markdown="1" style="padding-left: 20px;">
<p>An MSA-based service that visualizes a user's precious memories into a digital garden and provides a personalized AI experience through a Retrieval-Augmented Generation (RAG) pipeline.</p>
<ul>
<li>
<strong>Architecture Design:</strong>
<ul>
<li>Standardized all services based on <strong>Python (FastAPI)</strong> and established an integrated development environment using <strong>Docker Compose</strong>.</li>
<li>Introduced <strong>Apache Kafka</strong> as a message broker for asynchronous communication between services, reducing system coupling and ensuring scalability.</li>
<li>Managed the database using <strong>PostgreSQL (Neon DB)</strong> and <strong>SQLAlchemy (ORM)</strong>.</li>
</ul>
</li>
<li>
<strong>Core Service Development:</strong>
<ul>
<li><strong>RAG & Dify Pipeline Construction:</strong> Developed the core logic for the RAG pipeline, which syncs user memory data with the <strong>Dify</strong> knowledge base (<code>dify-data-sync-service</code>) and utilizes Dify workflows to generate personalized 'Today's Questions' (<code>daily-question-service</code>) and AI reward images (<code>reward-service</code>).</li>
<li><strong>AI-based Reward System (<code>reward-service</code>):</strong> Implemented a feature that processes reward generation requests asynchronously via a <strong>Kafka Consumer</strong>, and generates personalized pixel art images based on user memories by linking Dify workflows with the <strong>DALL-E API</strong>, then stores them in S3.</li>
<li><strong>Voice Analysis (<code>voice-analysis-service</code>):</strong> Developed a feature that converts user's voice answers to text with the <strong>Whisper API</strong> and calculates a cognitive health score using <strong>librosa</strong> and a machine learning model (<strong>XGBoost</strong>).</li>
</ul>
</li>
<li>
<strong>Cloud & Infrastructure:</strong>
<ul>
<li>Utilized <strong>AWS S3</strong> as storage for image and voice files and implemented a feature to send weekly reports and notifications to guardians via <strong>AWS SES/SNS</strong>.</li>
<li>Managed the Docker Compose configurations and deployment scripts for the entire MSA environment through a centralized <code>operations</code> service.</li>
</ul>
</li>
</ul>
</div>
</details>

<!-- Previous Project: Attention -->

<details>
<summary><b>👁️ Attention: Real-time Concentration Analysis Service via Webcam</b></summary>
<div markdown="1" style="padding-left: 20px;">
<p>A project that measured user concentration in real-time and provided analysis reports and AI coaching feedback. The entire codebase was managed in a <a href="https://github.com/AnneMaier/attention-ops">single monorepo</a>.</p>
<ul>
<li><strong>Polyglot Backend:</strong> Built an MSA by combining languages and frameworks suited for each purpose, such as <strong>Rust</strong> (for real-time data processing), <strong>Python/FastAPI</strong> (for the report API), and <strong>Node.js/Express</strong> (for client services).</li>
<li><strong>AI & Data Handling:</strong> Provided personalized coaching feedback by fine-tuning the <strong>EXAONE</strong> model and directly created and managed datasets for training with Python scripts.</li>
<li><strong>DevOps & Cloud:</strong> Deployed services using <strong>Docker/Kubernetes</strong>, automated CI/CD with <strong>GitHub Actions</strong>, and built the entire infrastructure utilizing <strong>AWS</strong> (EC2, S3, ALB, etc.).</li>
</ul>
</div>
</details>
