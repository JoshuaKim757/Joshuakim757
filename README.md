# 김동욱 (Joshua Kim)

**데이터가 어디서 무너지는지 찾고, 기준을 세워 고치고, 검증한 결과만 의사결정으로 넘깁니다**

Data Analyst | Risk · Customer · Decision Analytics
Python · SQL · Statistics | UIUC Econometrics & Statistics | ADsP · SQLD | 서울, 대한민국

각 프로젝트에는 결과뿐 아니라 **검증 과정과 분석이 설명하지 못하는 한계까지 함께 기록했습니다.**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge\&logo=python\&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge\&logo=postgresql\&logoColor=white)

---

## 포트폴리오 프로젝트

### [IVE Korea — 광고 이상 트래픽 탐지 & 매체 리스크 분석](https://github.com/JoshuaKim757/ad-fraud-detection-ive-korea)

* **기간** · 2026.01 – 2026.03
* **문제** · 정답 라벨이 없는 환경에서 189개 매체의 이상 트래픽 리스크를 탐지·정량화하고, 사후 분석 결과가 실제 운영 시점에서도 탐지 가능했는지 검증
* **결과** · 클릭 1,683만 건 중 고신뢰 이상 트래픽 639만 건(38.0%) 식별. 고신뢰 이상 ₩67.1M, 모니터링 대상 포함 총 ₩260.7M의 재무 노출 규모 정량화. 저위험 잔여 트래픽 CVR 30.50%(전체 플랫폼 8.74%)
* **검증** · 14개월 과거 데이터, 임계값 민감도 분석, 미래 정보 참조를 제거한 Out-of-Time 백테스트를 수행하고 최초 알림 규칙의 Null Result도 그대로 보고
* **기술** · Python, Pandas, NumPy, Gemini 2.0 Flash API

### [Starbucks — 리워드 오퍼 비용 누수 & 고객 반응 분석](https://github.com/JoshuaKim757/offer-cost-leak-starbucks)

* **기간** · 2025.11 – 2025.12
* **문제** · 구매 행동 변화 없이 지급되는 리워드 비용을 식별하고, 오퍼별 구매 유도 효과를 추정해 세그먼트별 발송 전략과 예산 재배분으로 연결
* **결과** · Discount 추정 Lift +32.8pp가 PSM 이후 +32.1pp로 유지되어 BOGO(+9.5pp)의 약 3배. 20개 세그먼트 중 5개만 리워드 조건 강화 시 순편익 +$4,134, 나머지 15개는 동일 조치 시 −$22,888
* **검증** · 사전 구매활동 비교와 1:1 PSM으로 선택편향을 점검하고 Power Analysis로 세그먼트별 결과의 해석 범위를 확인. Social 채널 추가 시 최대 약 $21,465의 절감 가능성 추정
* **기술** · Python, Pandas, scikit-learn, XGBoost, statsmodels

### [다이캐스팅 — 공정 불량 예측 & 의사결정 지원](https://github.com/JoshuaKim757/defect-prediction-die-casting)

* **기간** · 2025.10 – 2025.11
* **문제** · 공정·센서 데이터로 불량 가능성을 예측하고 주요 기여 변수를 작업자가 확인할 수 있는 판정 로직으로 연결
* **결과** · LightGBM으로 주요 3개 불량 그룹 F1 0.78–0.80. SHAP 결과를 정상군 비교 기반 4단계 판정 로직으로 연결하고, 가정 기반 시뮬레이션에서 10일당 약 ₩3.5M의 비용 절감 가능성 추정
* **역할** · 팀 프로젝트 — 데이터 전처리, 모델 비교 및 임계값 선정, 판정 로직, 비용 시뮬레이션 담당
* **기술** · Python, scikit-learn, XGBoost, LightGBM

### [서울 부동산 — 투자 후보군 스크리닝 & 검증](https://github.com/JoshuaKim757/investment-screening-seoul-realestate)

* **기간** · 2025.09 – 2025.10
* **문제** · 성장률·가격·변동성을 결합해 투자 성향별 구 × 건물유형 후보군을 선별하고, 해당 스코어링이 미래 구간에서도 유효한지 검증
* **결과** · 중랑구가 세 투자 성향 모두의 핵심 후보군에 포함. OLS(R²=0.543)를 통해 낮은 평균 가격이 순수한 입지 저평가뿐 아니라 건물 연식·유형 등 주택 재고 구성과도 연결됨을 확인
* **검증** · 7개 가중치 시나리오에서는 순위가 안정적이었지만 Temporal Holdout에서 2022–2024 서울 평균을 하회. 결과를 사후 조정하지 않고 정적 스코어링의 시장 국면 변화 취약성으로 보고
* **기술** · Python, Pandas, statsmodels, SciPy · React/SVG 인터랙티브 대시보드

---

## 자격증

* **ADsP** — 데이터분석 준전문가, 한국데이터산업진흥원 · 2026.03
* **SQLD** — SQL 개발자, 한국데이터산업진흥원 · 2026.06

---

## Contact

📧 [jkim43844@gmail.com](mailto:jkim43844@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/joshua-kim-87b478263/)
🌐 [English Portfolio](https://github.com/Jkim8436)
