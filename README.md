<h2 align="center">권소희 | Backend Developer</h2>

<p align="center">맡은 기능을 끝까지 구현하고, 생긴 문제는 원인부터 찾아 해결하는 백엔드 개발자입니다.</p>

<br>

<h3 align="center">Tech Stack</h3>

<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</div>
<div align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white">
</div>

<h3 align="center">Tools</h3>

<div align="center">
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
</div>

<br>

## Projects

### [덕모임](https://github.com/potenup-final/duckmoim-backend) | 2026.08 ~ 2026.09
생일카페와 팝업 같은 팬 행사를 위치 기준으로 보고, 행사별로 동행을 구해 채팅하는 서비스 ([duckmoim.com](https://duckmoim.com))
- 배포 중 SSE 채팅이 끊기던 문제를 서버 종료 시점 연결 정리로 해결
- 배포 중 컬럼 삭제로 저장이 실패하던 문제를 재현하고 단계별 DB 변경 규칙으로 해결
- 매일 수집되는 공연 데이터를 외부 ID 기준 upsert로 중복 없이 적재

`Java 17` `Spring Boot` `MySQL` `Redis` `Flyway` `AWS` `Docker` `GitHub Actions`

### [WhyNaGo](https://github.com/neogul-neogul/WhyNaGo) | 2026.07 ~ 2026.08
CS 문제에 답하면 "왜?"를 이어 묻는 꼬리질문으로 개념을 깊게 공부하는 서비스 ([why-na-go.vercel.app](https://why-na-go.vercel.app))
- 서술형 풀이를 3턴 대화로 설계하고, Gemini 채점과 꼬리질문 생성을 단일 호출로 처리
- Spring AI ChatMemory로 대화 이력을 세션 단위로 관리
- AI 호출 실패 시 대화 이력을 호출 직전 상태로 되돌려 흐름이 깨지지 않도록 처리

`Java 21` `Spring Boot` `Spring AI` `MySQL` `Testcontainers` `AWS` `GitHub Actions`
