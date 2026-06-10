# 약이 몸속에서 헤엄친다 🧪 — 분포용적(V<sub>d</sub>) 쉽게 배우기

![교재 썸네일](thumbnail.png)

초등학생도 이해할 수 있는 **임상약동학 입문 인터랙티브 교재**입니다.
ABSwitch 프로젝트 학생들을 위해 만들었습니다.

**🔗 바로 보기: https://sdkparkforbi.github.io/abswitch-pk-textbook/**

## 📖 구성

`교재 → 문제 → 실제문제` 순서로, **스스로 결정하는 힘**을 기릅니다.

1. **1부 · 교재** — 설탕물 비유로 시작해 V<sub>d</sub> 공식, 세 친구(Vc · Vss · Vz)의 차이, 왜 V<sub>z</sub>를 써야 하는지까지. 두 등장인물(나리 & 닥터 디)의 대화와 그림으로 풀어냅니다.
2. **2부 · 문제** — 즉시 채점되는 개념 퀴즈, V<sub>d</sub> 계산 연습, 생각 문제.
3. **3부 · 실제문제** — 우리가 모은 항체 약물 데이터(466건)를 직접 보고, "이 데이터를 어떻게 정리할까"를 스스로 결정하는 의사결정 시나리오.

## 🚀 보는 방법

- **웹에서 바로 보기:** GitHub Pages 링크 (저장소 Settings → Pages 에서 활성화 후 생성됨)
- **내려받아 보기:** `index.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다. (인터넷 연결·설치 불필요, 단일 파일)

## ✨ 특징

- 🎨 SVG 그림 (설탕물, 세 지표 비교, 결정 지도)
- 💬 두 캐릭터의 대화로 풀어가는 설명
- 🧮 직접 만져보는 V<sub>d</sub> 계산기
- ✅ 즉시 채점 퀴즈 & 의사결정 시나리오
- 📦 외부 라이브러리 없는 단일 HTML 파일 (오프라인 동작)

## 📚 이론적 근거

Greenblatt DJG et al. *Volume of distribution in pharmacokinetics and clinical medicine: a critical update*, J Pharm Pharmacol (2026).

핵심 결론: 분포를 가장 잘 나타내는 지표는 **V<sub>d</sub>(area) = V<sub>z</sub>** 이며, V<sub>ss</sub>는 실제 분포를 과소평가(1300개 약물 평균 V<sub>ss</sub>/V<sub>z</sub> ≈ 0.71), V<sub>c</sub>는 분포가 아닌 중심구획 부피입니다.

## 🔬 실제 데이터 사례

우스테키누맙(ustekinumab)은 우리 데이터에 V<sub>ss</sub>(≈4.5 L)와 V<sub>z</sub>(≈4.9 L)가 모두 있어, "V<sub>z</sub>가 더 크다"는 원리를 직접 검증할 수 있습니다. 다만 항체 약물은 비율이 ~0.92로 1에 가까워, 논문의 평균값 0.71을 그대로 곱하는 변환이 위험하다는 점도 함께 배웁니다.

---

학습용으로 자유롭게 사용·수정하세요. 🎓
