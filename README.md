# 오호민 | AI 연구·개발

단국대학교 수학과 학사, 아주대학교 인공지능학과 석사입니다. 석사 과정에서는 강화학습과 시퀀스 모델링을 연구했고, GrowPath에서는 모델 응답을 검증해 학습 로드맵에 반영하는 기능을 개발했습니다.

## 석사 연구 · Decision Transformer 기반 WSN 클러스터링

무선 센서의 데이터를 모아 기지국으로 보내는 노드인 클러스터 헤드를 고르는 정책을 설계했습니다. MATLAB에서 DQN과 LEACH-RLC를 구현해 12개 조건에서 첫 방전 시점과 평균 노드 수명을 비교했습니다. 센서 1,000개를 100×100 m² 영역에 배치하고 초기 에너지를 노드당 0.5 J로 설정한 실험에서, 첫 방전은 LEACH-RLC에서 940라운드, 제안 정책에서 2,277라운드에 발생했습니다.

- [석사학위논문](https://dcoll.ajou.ac.kr/dcollection/srch/srchDetail/000000035524)
- [ICAIIC 2026 제1저자 논문](https://doi.org/10.1109/ICAIIC68212.2026.11454374)

## GrowPath · 사내 역량 진단과 학습 로드맵

SK네트웍스 Family AI 캠프 5인 팀 프로젝트입니다. Ollama 응답의 자료 ID를 사용자 선택 목록과 대조하고, 누락된 과제만 다시 요청하도록 구현했습니다. React 화면의 요청 상태와 PostgreSQL에서 수정안이 중복 등록되는 경우도 맡았습니다. Qwen 27B 미세조정과 LangGraph 기반 멀티에이전트 작업에는 팀원과 함께 참여했습니다.

- [GrowPath 저장소](https://github.com/20260528-skn-family-ai-33/SKN33-Final-2Team)
- [응답 검증 구현 기록](https://github.com/20260528-skn-family-ai-33/SKN33-Final-2Team/pull/265)
