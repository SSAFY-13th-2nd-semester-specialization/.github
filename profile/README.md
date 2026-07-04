<div align="center">

<img src="./banner.png" alt="banner-image" width="100%" />

<h1>NewSpeaking</h1>
<h3>최신 뉴스 기반 AI 프리토킹 연습 플랫폼</h3>

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.0-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-19.1-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Whisper](https://img.shields.io/badge/Whisper-STT-412991?style=flat-square&logo=openai&logoColor=white)](https://github.com/openai/whisper)
[![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)](https://kafka.apache.org/)
[![License](https://img.shields.io/badge/License-Private-red?style=flat-square)]()

최신 뉴스 영어 단어 데이터 및 음소 분석 특화 AI 모델 기반 영어 프리토킹 연습 서비스

</div>

<br/>

# 아키텍처
<img src="./architecture.png" alt="service-architecture" width="100%" />

<br/>

# 기술 스택

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Web Speech API](https://img.shields.io/badge/Web_Speech_API-FF6F00?style=for-the-badge&logo=googlechrome&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### AI
![Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![librosa](https://img.shields.io/badge/librosa-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![g2p-en](https://img.shields.io/badge/g2p--en-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Data
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

### Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)

### DevOps & Tools
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Mattermost](https://img.shields.io/badge/Mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white)

<br/>

# 주요 기능

<table width="100%">
<tr align="center"><th width="25%">기능</th><th width="75%">설명</th></tr>
<tr><td><strong>음소 단위 발음 평가</strong></td><td>사용자의 음성을 녹음하고 음소 단위로 발음을 분석해 구체적인 교정 피드백 제공</td></tr>
<tr><td><strong>학습 대시보드</strong></td><td>누적 학습 기록을 그래프·차트로 시각화해 발음 정확도 및 학습 추이 확인</td></tr>
<tr><td><strong>뉴스 기반 학습</strong></td><td>BBC·CNN 등 최신 뉴스 문장을 활용해 시의성 있는 실전 영어 학습</td></tr>
<tr><td><strong>맞춤 단어 연습</strong></td><td>자주 틀리거나 연습하고 싶은 단어를 저장해 개인 맞춤 발음 연습</td></tr>
<tr><td><strong>쉐도잉</strong></td><td>원하는 유튜브 영상·뉴스를 선택해 따라 말하기 연습</td></tr>
</table>

<br/>

# 시스템 구성

<table width="100%">
<tr align="center"><th width="30%">구성</th><th width="70%">역할</th></tr>
<tr><td><strong>웹 프론트엔드</strong></td><td>발음 녹음·재생, 대시보드 시각화, 뉴스·쉐도잉 학습 UI 제공</td></tr>
<tr><td><strong>서비스 백엔드</strong></td><td>회원 인증·인가, 학습 기록 관리, AI 분석 요청 중계</td></tr>
<tr><td><strong>AI 발음 분석 서버</strong></td><td>Whisper STT와 g2p 음소 정렬 기반 발음 평가·피드백 생성</td></tr>
<tr><td><strong>데이터 파이프라인</strong></td><td>뉴스 기사 크롤링, Kafka·Spark 기반 단어 데이터베이스 구축</td></tr>
</table>

<br/>

# 레포지토리

<table width="100%">
<tr align="center"><th width="40%">Repository</th><th width="35%">설명</th><th width="25%">스택</th></tr>
<tr><td><code>specialization-pjt-newspeaking-fe</code></td><td>웹 프론트엔드</td><td>React · TypeScript</td></tr>
<tr><td><code>specialization-pjt-newspeaking-be-api</code></td><td>WAS 서버</td><td>Spring Boot</td></tr>
<tr><td><code>specialization-pjt-newspeaking-ai-judge-api</code></td><td>AI 발음 분석 모델</td><td>FastAPI · Whisper</td></tr>
</table>

<br/>

# 팀

<table width="100%">
<tr>
<th width="20%" align="center">Backend</th>
<th width="20%" align="center">Frontend</th>
<th width="20%" align="center">AI</th>
<th width="20%" align="center">Data</th>
<th width="20%" align="center">Infra</th>
</tr>
<tr align="center">
<td><a href="https://github.com/Yun-tellije"><img src="https://img.shields.io/badge/윤정은-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="윤정은"></a><br><a href="https://github.com/KSJ0314"><img src="https://img.shields.io/badge/김소중-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="김소중"></a></td>
<td><a href="https://github.com/KangGyeongGu"><img src="https://img.shields.io/badge/강경구-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="강경구"></a><br><a href="https://github.com/KSJ0314"><img src="https://img.shields.io/badge/김소중-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="김소중"></a></td>
<td><a href="https://github.com/daeyeol-yang"><img src="https://img.shields.io/badge/양대열-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="양대열"></a></td>
<td><a href="https://github.com/nove1080"><img src="https://img.shields.io/badge/나제법-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="나제법"></a><br><img src="https://img.shields.io/badge/유영훈-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="유영훈"></td>
<td><a href="https://github.com/KangGyeongGu"><img src="https://img.shields.io/badge/강경구-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="강경구"></a></td>
</tr>
</table>

<br/>

---

<div align="center">

본 프로젝트의 모든 권리는 [SSAFY](https://www.ssafy.com/)에 있으며, 무단 복제·배포·사용을 금합니다.

© 2025 [SSAFY](https://www.ssafy.com/). All rights reserved.

</div>
