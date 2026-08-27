# 김조슈아 (Joshua Kim)

**데이터 분석가 — 프로덕트, 리스크 & 고객 분석**
UIUC 계량경제학·통계학 · ADsP · SQLD · 서울, 대한민국

데이터가 어디서 무너지는지 찾아내고, 고치고, 그 수정을 실제 의사결정으로 연결합니다. 아래 네 개 프로젝트에는 전체 방법론, 검증 과정, 그리고 데이터가 뒷받침하지 못하는 부분까지 솔직하게 담았습니다.

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge) ![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 포트폴리오 프로젝트

### [IVE Korea — 광고 부정클릭 탐지 & 매체 리스크 분석](https://github.com/Jkim8436/IVE-Korea-Ad-Fraud-Detection)
**목표:** 라벨링된 정답 데이터 없이 189개 매체 파트너의 광고 부정클릭 리스크를 탐지·정량화하고, 해당 플래그가 사후 분석용이 아닌 실시간 탐지기로도 작동할 수 있는지 검증.
**결과:** 16.8M건의 이벤트 중 고신뢰 이상 클릭 639만 건(38.0%) 식별, ₩260.7M 규모의 노출 금액 정량화, 클린 트래픽 전환율 8.74% → 30.50%로 회복. Out-of-time 백테스트를 통해 실제로 어떤 알림 설계가 실시간으로 이 사건을 잡아낼 수 있었는지(혹은 없었는지)를 솔직하게 보고.
**기술:** Python, Pandas, Gemini 2.0 Flash API (룰 기반 + LLM 하이브리드 도메인 분류)

### [Starbucks — 리워드 오퍼 낭비 분석](https://github.com/Jkim8436/Starbucks-Marketing-Offer-Optimization)
**목표:** 실제 구매 행동을 유도하지 못하고 새는 리워드 비용을 찾아내고, 완료율이 아닌 각 오퍼 유형의 실제 인과 효과를 측정.
**결과:** Discount 오퍼의 마케팅 효과(+32.8pp)는 성향점수매칭(PSM) 이후에도 +32.1pp로 유지 — BOGO의 3배 수준. 20개 고객 세그먼트 중 5개만 리워드 조건 강화로 이득(+$4,134)을 보며, 나머지 15개는 $22,888 손실. 채널 기반 개선으로 $21,465 절감 추정.
**기술:** Python, scikit-learn (PSM), XGBoost, statsmodels

### [다이캐스팅 — 실시간 불량 예측](https://github.com/Jkim8436/Die-Casting-Defect-Prediction)
**목표:** 사후 대응적인 수동 육안검사를 실시간으로 불량을 예측하고 근본 원인까지 추적하는 모델로 대체.
**결과:** PR-AUC 기준으로 LightGBM 선정 — 3개 불량 그룹에서 F1 0.79–0.80 달성; SHAP으로 각 불량 유형별 원인 공정 변수 식별; 명시된 FN/FP 단위 비용 기준 10일당 약 ₩3.5M 절감 추정.
**기술:** Python, scikit-learn, XGBoost, LightGBM, SHAP · *팀 프로젝트 — 전처리, 모델링, 판정 로직, 비용 영향 분석을 개별적으로 담당*

### [서울 부동산 — 투자 전략 & 스크리닝 대시보드](https://github.com/Jkim8436/Seoul-Real-Estate-Investment-Strategy)
**목표:** 세 가지 투자자 성향별 구(區) × 건물유형 투자 대상을 추천하고, 이 스코어링 프레임워크가 실제로 미래를 예측하는지 검증.
**결과:** 모든 투자자 성향에서 중랑구가 1순위; OLS 회귀분석(R²=0.543) 결과, "저렴해 보이는" 구의 가격 할인은 대부분 위치 프리미엄이 아니라 노후 건물 비중 효과였음을 확인; Temporal holdout 검증 결과 이 프레임워크는 2022–2024년 시장을 **underperform**했음을 확인 — 조정 없이 있는 그대로 보고. 프로필별로 실시간 전환 가능한 인터랙티브 React 대시보드 포함.
**기술:** Python, statsmodels, SciPy · React/SVG 대시보드

---

## 자격증
- ADsP — 데이터분석 준전문가, 한국데이터산업진흥원 (2026년 3월)
- SQLD — SQL 개발자, 한국데이터산업진흥원 (2026년 6월)

## Contact
📧 jkim43844@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/joshua-kim-87b478263/)
