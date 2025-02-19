
# JAVABOJA Final Project

### 프로젝트 주제 : 분산 환경 MSA 아키텍처의 동영상 스트리밍 서버 웹 솔루션 개발<br>

#### PM - 권동빈<br>

#### PL - 이준경<br>

#### PA - 김용준<br>

#### PA - 유성욱<br>

#### DBA - 정민성<br>

---

### 프로젝트 역할
![포지션](https://private-user-images.githubusercontent.com/166098924/348584845-e55cd20b-8413-4933-bc75-8a51194f947e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjEwMDkwNTgsIm5iZiI6MTcyMTAwODc1OCwicGF0aCI6Ii8xNjYwOTg5MjQvMzQ4NTg0ODQ1LWU1NWNkMjBiLTg0MTMtNDkzMy1iYzc1LThhNTExOTRmOTQ3ZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcxNVQwMTU5MThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04MzlmNmFlY2E0ZTJlYmZkNGE5MTMzYTBiNWI4MTg4MjMzMDNkZTA4M2I4NWEyZWY0ODQ3NGExMDNiZWJkMmIyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.NjgdNe53V09HFm5lzBSn6RXYWu04AxPGjNgOcCNqA5w)

---

### 선정배경 
동영상 콘텐츠 소비가 꾸준히 증가하고, 
안정적이며 고성능의 스트리밍 서비스에 대한 수요가 높아짐에 따라 
이를 위해 분산환경에서 효율적으로 동영상 스트리밍을 제공하는 서비스를 개발
<br>

---

### 프로젝트 개요
-사용자 경험 향상  :  개인화된 재생목록 기능으로 사용자의 콘텐츠 관리 편의성 증대
-직관적인 인터페이스를 통한 동영상 공유 및 시청 경험 개선
-커뮤니티 활성화: 댓글 시스템을 통한 사용자 간 상호작용 촉진
-좋아요 기능으로 인기 콘텐츠 식별 용이
-확장성 및 유지보수성: 모듈화 된 구조로 향후 기능 추가 및 확장이 용이
-계층화 된 아키텍처로 각 부분의 독립적인 개선 및 유지보수 가능

---


### 개발환경
![개발환경](https://private-user-images.githubusercontent.com/166098924/348583501-9c97e24f-5976-45e4-bf9f-92a45e107d58.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjEwMDc5ODgsIm5iZiI6MTcyMTAwNzY4OCwicGF0aCI6Ii8xNjYwOTg5MjQvMzQ4NTgzNTAxLTljOTdlMjRmLTU5NzYtNDVlNC1iZjlmLTkyYTQ1ZTEwN2Q1OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcxNVQwMTQxMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hNjM5Y2YzYjg4NDBmMjVjMWM0MjRhODJkZjgxMDM5ZGJiODEyM2IyM2UyZmNkZTY0N2NiMWRlNTNhMjkzYjk1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.7gycW4iLNdjl_9ADaAx3sijYteFRlr6icJEjpJx228o)

---

### 개발 구조

#### 프론트엔드
-React.js를 사용하여 동적이고 반응형 사용자 인터페이스 구현<br>
-동영상 플레이어 컴포넌트 구현<br>
-재생목록 관리 인터페이스 개발<br>
-사용자 프로필 및 설정 페이지 구현<br>
#### 백엔드
-Spring Boot 3 기반의 RESTful API 서버 구축<br>
-MSA 패턴을 적용한 계층적 구조 설계<br>
-비디오 스트리밍 및 파일 업로드 처리 로직 구현<br>
-사용자 인증 및 권한 관리 시스템 구축<br>
#### 데이터베이스
-Oracle 21C를 사용한 데이터 관리 및 저장<br>
-비디오 메타데이터, 사용자 정보, 재생목록, 댓글 등의 데이터 모델 설계<br>
-JPA와 Hibernate를 활용한 객체-관계 매핑 구현<br>
#### 외부 API
-결제 시스템 (포트원)<br>

---

### 프로젝트 결과
1. 기술 스택 통합: Spring Boot 3와 React 통합하여  현대적이고 효율적인 웹 애플리케이션 구축<br>
2. Oracle 21C 데이터베이스와의 원활한 연동 구현<br>
3. 핵심 기능 구현: 동영상 업로드, 스트리밍, 재생목록 관리 등 주요 기능 성공적 구현<br>
4. 사용자 인증 및 권한 관리 시스템 구축<br>
5. 효율적인 데이터베이스 쿼리 설계로 응답 시간 개선<br>
6. 동영상 스트리밍 최적화로 사용자 경험 향상<br>

---

### 향후 계획
1. 보안 강화 계획<br>
정기적인 보안 감사 실시 및 취약점 대응 체계 구축<br>
데이터 암호화 범위 확대 및 보안 프로토콜 최신화<br>

2. 확장성 개선<br>
대규모 트래픽 처리를 위한 서버 아키텍처 최적화<br>

3. 사용자 경험 개선<br>
베타 테스트 피드백을 반영한 UI/UX 개선<br>
사용자 행동 분석을 통한 서비스 최적화<br>

4. 클라우드 배포<br>
AWS를 이용한 프로젝트 배포 실시<br>
