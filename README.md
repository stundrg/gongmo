# gongmo

## 주제 선정
- 최근 데이터 중 광진구의 사고가 너무 적어 이 후 패턴을 분석하기 어렵다.
- 교통사고와, 고령 보행자의 관한 내용을 분석이 어려워 다른 주제로 넘어가기로 한다.

## 이후 방향
- 가로등 데이터와 여러가지를 가지고 답사를 나갈 예정

## 답사 시 관련 내용 확인하기
- 답사 예상 지역 - 중곡4동, 자양4동, 중곡2동, 자양1동, 구의3동, 능동시장
~
## 진행 현황

- 최신 분석 진행 상황은 [진행상황](./src/docs/progress.md) 에서 확인할 수 있습니다.


## 📂 폴더 구조  

```plaintext
.
├── README.md               # 프로젝트 개요 (현재 파일)
├── pdm.lock                # PDM 환경 설정 파일
├── pyproject.toml          # 패키지 & Python 환경 설정
├── src/
│   ├── configs/            # 환경 설정 파일 (.env, config.json)
│   ├── data/               # 원본 데이터 및 가공 데이터 저장
│   ├── docs/               # 보고서, 논문, 발표자료
│   ├── gongmo/             # 공모전 관련 코드 (분석, 모델링)
│   │   ├── __init__.py
│   ├── logs/               # 로그 파일 저장
│   ├── notebooks/          # Jupyter Notebook (EDA, 분석)
│   ├── references/         # 참고 논문 및 자료
│   ├── results/            # 분석 결과 저장 (시각화, CSV 등)
│   ├── scripts/            # 데이터 처리 및 실행 코드
│   ├── tests/              # 테스트 코드
│   │   ├── __init__.py
└── tests/                  # 테스트 코드 (별도 테스트용)
    ├── __init__.py
