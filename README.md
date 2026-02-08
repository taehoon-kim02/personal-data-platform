# Personal Data Platform

개인 학습 및 포트폴리오 목적으로 진행하는 데이터 엔지니어링 프로젝트입니다.  
데이터 수집 → 저장 → 처리 → 활용까지의 전 과정을 직접 설계하고 구현하는 것을 목표로 합니다.

---

## Project Purpose

- 데이터 엔지니어 관점에서 End-to-End 데이터 파이프라인 경험
- Python과 SQL을 활용한 데이터 수집 및 가공
- 로컬 환경에서 시작하여 확장 가능한 구조로 설계
- GitHub를 통한 버전 관리 및 프로젝트 기록

---

## Planned Workflow
Data Source (API / Crawling)
↓
Data Collection
↓
Raw Data Storage
↓
Processing & Cleaning
↓
Database (RDBMS)
↓
Analysis / Visualization
---

## Tech Stack (Planned)

- Language: Python
- Database: PostgreSQL / MySQL
- Data Processing: pandas
- Version Control: Git, GitHub
- Environment: macOS, VS Code

---

## Project Structure (WIP)
personal-data-platform/
├── README.md
├── src/
│   ├── collector/
│   ├── processor/
│   └── loader/
├── tests/
├── docs/
└── .gitignore
---

## Notes

- API Key, DB 계정 정보 등 민감한 정보는 `.env` 파일로 관리합니다.
- 주요 변경 사항은 커밋 단위로 기록합니다.
- 학습 목적의 프로젝트이며 구조는 점진적으로 개선할 예정입니다.

---

## Current Status

- [x] GitHub 저장소 생성
- [x] 로컬 Git 환경 세팅
- [ ] 데이터 소스 선정
- [ ] 1차 데이터 수집 파이프라인 구현
- [ ] 데이터베이스 연동

---

## Author

- 김태훈  
- GitHub: https://github.com/taehoon-kim02
