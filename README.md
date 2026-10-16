## 김동원 (Dongwon Gim)

서울에서 일하는 Product Engineer입니다. 무엇을 만들지 정하는 단계부터 배포하고 운영하는 단계까지 한 사람이 끝까지 가져가는 방식으로 일합니다.

자료를 뽑아 달라는 요청을 3년 가까이 받다가 데이터팀 신설을 건의해 팀을 만들었고, 그 뒤로 데이터 파이프라인과 사내 시스템, 그 아래의 인프라를 만들고 운영하고 있습니다. 일이 조용히 실패하는 지점을 찾는 데 시간을 많이 씁니다. 그래서 기능을 만들 때 그 기능이 죽었을 때 알아내는 방법도 같이 만듭니다.

[블로그](https://dorori.club) | [no1dongwon@gmail.com](mailto:no1dongwon@gmail.com)

### 지금 하는 일

광고 테크 회사 Alliswell에서 데이터팀을 맡고 있습니다(2020년 입사, 2023년부터 팀장). 회사 저장소는 비공개라 여기에는 무엇을 하는지만 적습니다.

- **데이터 파이프라인**: Airflow로 유동인구, 교통 데이터를 여러 DB에 적재하고, 옥외광고 노출량을 계산해 지도로 서빙합니다
- **사내 시스템**: 회계 대사와 정산을 다루는 ERP, 옥외광고 매체 관리 플랫폼, 사내 데이터 조회 시스템의 프론트엔드와 백엔드를 만듭니다
- **온프렘 인프라와 관측**: Docker Compose를 Git으로 관리하고 Jenkins로 배포하며, Prometheus, Grafana, Loki, Alertmanager로 실제 장애에서 뽑은 알림 규칙을 운영합니다
- **AI 에이전트 연동**: 사내 메일과 문서를 MCP로 노출하는 OAuth 2.1 인증 서버를 직접 구현했고, 에이전트가 할 수 있는 일의 상한을 코드로 고정하는 데 관심이 많습니다

### 사이드 프로젝트

테크노 DJ로 디깅하고 트랙을 트는 게 취미라, 사이드 프로젝트도 대부분 거기서 시작합니다.

| 프로젝트 | 설명 | 스택 |
|---|---|---|
| Bandcamp Toolkit | Bandcamp에서 파형, BPM, 위시리스트, 카트를 다루는 크롬 확장과 동기화 서버 | WXT, React, Next.js, Postgres |
| DJ Library | 텔레그램으로 받은 음원을 수집하고 BPM, 키, 비트 그리드를 분석해 rekordbox로 내보내는 개인 음악 클라우드 | FastAPI, librosa, Essentia, Web Audio |
| dj-kick-monitor | CDJ 두 대의 킥이 어긋나는 순간을 실시간으로 보여 주는 모니터 | Python, numpy |
| Toss Quant | 토스증권 Open API로 KRX 데이터를 모아 신호를 백테스트하고, 기각한 가설까지 기록하는 퀀트 리서치 | Python, vectorbt, DuckDB |
| [Claude Tab Janitor](https://github.com/DongwonGim/chrome-claude-tab-janitor) | Claude in Chrome이 남기는 탭 그룹을 정리하는 크롬 확장 | Chrome MV3 |

### 주로 쓰는 것

- **Data**: Python, Airflow, PostgreSQL, PostGIS, DuckDB, pandas
- **Web**: TypeScript, Next.js, React, FastAPI
- **Infra**: Docker Compose, Jenkins, Prometheus, Grafana, Loki, Nginx, Tailscale
- **AI**: Claude Code, MCP, OAuth 2.1
