# 🚀 Fitty - 백엔드 포트폴리오 (포크된 레포지토리)

> **💡 본 레포지토리는 팀 프로젝트 [Fitty_BE](https://github.com/Fitty-UMC-8th/Fitty_BE)를 기반으로, 백엔드 개발자 [상번]의 기여도를 중심으로 재구성된 포트폴리오용 레포지토리입니다.**

## 📌 1. 프로젝트 개요 및 나의 역할
- **프로젝트 한줄 소개:** 운동을 인증할 때마다 캐릭터가 성장하는 디지털 헬스케어 서비스
- **개발 기간:** 2025.09 ~ 2025.09 (1개월)
- **나의 역할:** Back-end (ㅇㅇ 도메인, ㅇㅇ API 개발 담당)

## 🛠 2. 활용 기술 스택 (Tech Stack)
*(팀 전체의 기술이 아닌, 본인이 직접 다루고 코드를 작성한 기술 위주로 작성했습니다.)*

- **Language & Framework**
  - `Java 21`
  - `Spring Boot 3.5.5`
- **Database & ORM**
  - `MySQL`
  - `Spring Data JPA`, `Spring Data JDBC`
- **API & Web**
  - `Spring Web` (RESTful API 설계 및 구현)
  - `Spring WebFlux` (비동기/논블로킹 처리 또는 외부 API 호출 활용)
  - `Swagger` (SpringDoc OpenAPI 3를 통한 API 문서화)
  - `Thymeleaf` (서버 사이드 렌더링 화면 구현)
- **Build & Environment**
  - `Gradle`
  - `Lombok`, `Bean Validation`

## 🔥 3. 주요 담당 업무 및 기여도 (My Contributions)
*(🚨여기에 상번님이 실제로 코드를 짜면서 구현한 핵심 비즈니스 로직을 적어주세요. 아래는 예시입니다.)*

- **[핵심 기능 A, 예: 운동 인증 및 캐릭터 경험치 부여 API 구현]**
  - Spring Data JPA를 활용하여 운동 기록 데이터와 캐릭터 상태 간의 복잡한 연관관계 매핑 및 비즈니스 로직 구현.
  - Bean Validation을 활용하여 클라이언트의 요청 데이터(DTO) 정합성 검증 로직 추가.

- **[핵심 기능 B, 예: Spring WebFlux를 활용한 비동기 로직 처리]**
  - 캐릭터 레벨업 시 외부 알림 API를 호출할 때 발생하는 지연 시간을 줄이기 위해 WebClient를 활용하여 비동기 논블로킹 처리.

- **RESTful API 설계 및 Swagger 명세화**
  - 프론트엔드와의 원활한 협업을 위해 SpringDoc을 활용하여 직관적인 API 문서 자동화 및 테스트 환경 구축.

## 💡 4. 트러블 슈팅 (Troubleshooting)
*(🚨가장 머리 아팠던 DB 쿼리 문제, 로직 에러, 또는 성능 개선 경험 1가지를 적어주세요)*

### 🚨 문제 상황 (Issue)
- (예시: 사용자가 운동 인증을 조회할 때 N+1 문제로 인한 쿼리 폭발 및 응답 속도 지연 현상 발생)

### 🎯 해결 방법 (Solution)
- (어떤 고민을 했고 어떻게 해결했는지 구체적으로 작성. 예: Fetch Join 적용으로 쿼리 수를 N개에서 1개로 줄이고 응답 속도 50% 개선)
- [관련 PR 혹은 블로그 링크](URL)

## 🔗 5. 링크
- **팀 프로젝트 원본 레포지토리:** [Fitty_BE 레포지토리 바로가기](https://github.com/Fitty-UMC-8th/Fitty_BE)
- **API 명세서:** [URL]
