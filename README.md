# 오호민 | AI 연구·개발

단국대학교 수학과를 졸업하고 아주대학교 인공지능학과에서 석사 학위를 받았습니다. 대학원에서는 강화학습으로 무선 센서의 방전을 늦추는 방법을 연구했습니다. GrowPath에서는 모델이 만든 학습 계획을 확인하고, 빠진 과제만 다시 요청하는 기능을 개발했습니다.

## 석사 연구 · Decision Transformer 기반 WSN 클러스터링

Decision Transformer로 무선 센서의 데이터를 모아 기지국으로 보낼 노드를 골랐습니다. MATLAB에서 DQN과 LEACH-RLC를 구현해 같은 조건에서 비교했습니다. 센서 1,000개를 배치한 한 실험에서 첫 방전은 LEACH-RLC의 경우 940라운드, 제가 설계한 방법에서는 2,277라운드에 일어났습니다. 이 조건에서 평균 노드 수명은 DQN과 비슷했습니다.

- [석사학위논문](https://dcoll.ajou.ac.kr/dcollection/srch/srchDetail/000000035524)
- [ICAIIC 2026 제1저자 논문](https://doi.org/10.1109/ICAIIC68212.2026.11454374)

## GrowPath · 사내 역량 진단과 학습 로드맵

SK네트웍스 Family AI 캠프 팀 프로젝트입니다. Ollama가 반환한 자료 ID를 사용자가 고른 목록과 대조하고, 과제가 빠진 스킬만 다시 요청하도록 구현했습니다. React 화면에 수정안 생성 상태를 표시했고, PostgreSQL에서는 기존 작업 조회와 새 작업 등록을 같은 트랜잭션에서 처리했습니다. Qwen 27B 미세조정과 LangGraph 기반 멀티에이전트 작업은 팀원과 함께했습니다.

- [GrowPath 저장소](https://github.com/20260528-skn-family-ai-33/SKN33-Final-2Team)
- [응답 검증 구현 기록](https://github.com/20260528-skn-family-ai-33/SKN33-Final-2Team/pull/265)

## SKN AI 캠프 실습·프로젝트 모음

Python과 데이터베이스 실습, 데이터 수집·분석, 머신러닝과 LLM 실습, 캠프에서 진행한 팀 프로젝트를 모았습니다.

- [SKN-Project 저장소 목록](https://github.com/orgs/SKN-Project/repositories)
