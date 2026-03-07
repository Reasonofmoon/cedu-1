<div align="center">

# 🎓 CEDU AI Masterclass — 기초 과정

### *"AI에게 글을 시키다"*

**영어학원 원장을 위한 AI 실전 활용 12강 · 코딩 없이 학원 운영을 자동화한다**

[![Lectures](https://img.shields.io/badge/강의-12강-6366f1?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/01_branding.ipynb)
[![Gemini](https://img.shields.io/badge/AI-Gemini_2.5_Flash-22d3ee?style=for-the-badge&logo=google)](https://aistudio.google.com/)
[![Colab](https://img.shields.io/badge/Platform-Google_Colab-a78bfa?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge)](LICENSE)
[![Level](https://img.shields.io/badge/Level-No_Code-fb7185?style=for-the-badge&logo=notion)](https://github.com/Reasonofmoon/cedu-1)

<br/>

> **"학원을 운영한다는 것은 하루에 수십 개의 문서를 생산한다는 뜻이다."**
> CEDU AI Masterclass는 그 문서들을 **AI에게 위임**하는 실전 훈련 시스템이다.
> 브랜딩 · 상담 · 시험지 · 피드백 · 재등록 · 통합 대시보드까지 — **12강, 12개 자동화.**

[🚀 01강 바로 시작](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/01_branding.ipynb) · [📖 커리큘럼](#️-12강-커리큘럼) · [🐛 이슈 리포트](../../issues)

</div>

---

## 🧠 Philosophy — "원장의 시간을 되돌려준다"

영어학원 운장의 하루는 **문서와의 전쟁**이다.
상담자료, 성적 리포트, SNS 게시물, 재등록 안내문... 매번 처음부터 작성한다.

> *"좋은 교육을 하고 싶은데, 서류에 치인다."*
> CEDU는 그 서류를 AI에게 넘긴다. 단, **프롬프트 한 줄**로.

| 기준 | 기존 방식 | CEDU AI Masterclass |
|------|-----------|---------------------|
| **브랜드 슬로건** | 마케팅 회사 의뢰 → 수십만 원 | Gemini에 RTF+C 입력 → **30초** |
| **학생 피드백** | 선생님이 1명씩 수작업 | Python 반복문 → **전원 일괄 생성** |
| **성적 분석** | 엑셀 수동 작업 | Colab + matplotlib → **자동 차트** |
| **재등록 안내** | 매달 새로 작성 | 개인화 메시지 → **배치 자동화** |
| **통합 대시보드** | 파일 여기저기 | 12강 결과물 → **하나의 Cockpit** |

```
CEDU Learning Pipeline:

  [원장님의 학원 정보 입력]
          ↓
  ┌────────────────────────────┐
  │     RTF+C 프레임워크        │
  │  Role → Task → Format     │
  │      → Constraint          │
  └───────────┬────────────────┘
              ↓
  ┌──────────────────────────────────────────────────┐
  │                Gemini 2.5 Flash API              │
  └──────────────────────────────────────────────────┘
              ↓
  ┌───────┐ ┌───────┐ ┌────────┐ ┌────────┐ ┌──────────┐
  │브랜딩  │ │상담   │ │ 시험지  │ │ 피드백  │ │성적 분석  │
  │Lecture│ │Lecture│ │Lecture │ │Lecture │ │ Lecture  │
  │ 01    │ │ 02~03 │ │  05    │ │  04    │ │   06     │
  └───────┘ └───────┘ └────────┘ └────────┘ └──────────┘
              ↓
  📊 통합 Cockpit Dashboard (12강)
```

---

## 🔬 핵심 프레임워크 — RTF+C

이 과정의 모든 프롬프트는 **RTF+C** 4-레이어 구조를 따른다:

```
R  (Role)        — "너는 영어학원 10년 경력의 마케팅 전문가야."
T  (Task)        — "우리 학원 브랜드 슬로건 5개를 만들어줘."
F  (Format)      — "각 슬로건은 10자 이내로, 표 형태로 정리해줘."
C  (Constraint)  — "과장하지 말고 실현 가능한 약속만 담아줘."
```

> **Wow**: RTF+C 한 번 익히면 **어떤 AI 도구**에도 적용 가능 — Gemini, Claude, ChatGPT 모두 동작

---

## ⚙️ 12강 커리큘럼

### Module A · 학원 브랜딩 & 학생 유치 (1~3강)

| 강 | 주제 | 핵심 출력물 | Colab |
|----|------|------------|-------|
| 01 | 브랜딩 & 상담 준비 | 브랜드 슬로건 · 상담 질문 리스트 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/01_branding.ipynb) |
| 02 | 상담 브리핑 자동화 | 학부모 상담 스크립트 · 퍼스널라이징 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/02_counseling.ipynb) |
| 03 | 레벨테스트 자동화 | 수준별 테스트 문항 · 결과 분류표 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/03_level_test.ipynb) |

> **Wow**: 레벨테스트 30문항이 **2분** 만에 생성 — 직접 출력 즉시 사용

### Module B · 수업 & 피드백 자동화 (4~6강)

| 강 | 주제 | 핵심 출력물 | Colab |
|----|------|------------|-------|
| 04 | AI 피드백 시스템 | 학생 5명 배치 피드백 · `pandas` 자동화 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/04_feedback.ipynb) |
| 05 | 시험 대비 패키지 | 수능·모의고사 대비 문제지 자동 생성 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/05_exam_prep.ipynb) |
| 06 | 성적 분석 & 위험 감지 | `matplotlib` 라인 차트 · 하락생 자동 탐지 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/06_risk_radar.ipynb) |

> **Wow**: 06강 — 성적 하락 학생을 AI가 자동 감지 → 담임 교사에게 알림 문자 초안까지 생성

### Module C · 운영 & 마케팅 자동화 (7~10강)

| 강 | 주제 | 핵심 출력물 | Colab |
|----|------|------------|-------|
| 07 | 퇴원생 관리 & 재등록 | 개인화 재등록 안내문 · 퇴원 원인 분석 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/07_re_enroll.ipynb) |
| 08 | 마케팅 자동화 | SNS 게시물 · 카카오 채널 메시지 템플릿 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/08_marketing.ipynb) |
| 09 | 수업 계획 & 강사 매뉴얼 | 주간 수업 계획서 · 강사 표준 매뉴얼 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/09_class_standard.ipynb) |
| 10 | 연간 운영 캘린더 | 12개월 이벤트·시험·모집 일정 자동 편성 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/10_calendar.ipynb) |

### Module D · AI 성장 & 통합 시스템 (11~12강)

| 강 | 주제 | 핵심 출력물 | Colab |
|----|------|------------|-------|
| 11 | AI 역량 진단 & 성장 | `numpy` 레이더 차트 · 90일 성장 로드맵 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/11_ai_compass.ipynb) |
| 12 | 통합 대시보드 Cockpit | 1~11강 결과물 통합 · 학원 운영 전체 요약 | [![Open](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/cedu-1/blob/main/notebooks/12_cockpit.ipynb) |

> **Wow**: 12강 Cockpit — 12개 자동화 결과물이 **하나의 대시보드**로 통합

---

## 🎯 수준별 활용 가이드

### 🟢 Starter — "5분 안에 첫 AI 결과물"

```
Step 1 → Google AI Studio (aistudio.google.com) 접속
Step 2 → Get API Key → Create API Key 클릭 → 키 복사
Step 3 → labs/01-branding/ 폴더 → 프롬프트 Gemini에 붙여넣기
Step 4 → 학원명·위치·대상 수정 후 Enter
Step 5 → 브랜드 슬로건 5개 즉시 출력 ✅
```

> 코딩 0줄. 복사-붙여넣기만 할 수 있으면 됩니다.

### 🔵 Professional — "Colab으로 배치 자동화"

```python
# Colab Secret에 API 키 저장 (1번만)
# 이름: GEMINI_API_KEY / 값: 발급받은 키

# 그 다음 모든 노트북에서 자동 참조
from google.colab import userdata
api_key = userdata.get('GEMINI_API_KEY')
```

1. 위 Colab 뱃지 클릭 → 노트북 오픈
2. `런타임` → `모두 실행`
3. 학원 정보 셀만 수정 → 자동 실행
4. 마지막 셀 → 결과 파일 자동 다운로드

### 🟣 Enterprise — "12강 전과정 + 연속 과정 연결"

- **cedu-2 (중급)**: "AI에게 앱을 시키다" — No-Code 앱 제작
- **cedu-3 (고급)**: "AI로 제국을 세우다" — 멀티에이전트 자동화
- **12강 완주 후**: 학원 운영 AI 시스템 전체 구축 완료
- **본인 학원 커스텀**: `shared/` 폴더의 공용 데이터를 실제 학원 DB로 교체

---

## 🔧 확장 우선순위

| 우선순위 | 방법 | 난이도 | 범위 |
|----------|------|--------|------|
| **1st** | `labs/` 프롬프트를 내 학원 정보로 교체 | ⭐ | 즉시 실무 적용 |
| **2nd** | Colab Secrets에 API 키 저장 | ⭐ | 보안 + 재사용 |
| **3rd** | `notebooks/` 학원 데이터 셀 수정 | ⭐⭐ | 배치 자동화 |
| **4th** | 6강 `matplotlib` 차트 + 7강 재등록 연동 | ⭐⭐ | 운영 통합 |
| **5th** | 12강 Cockpit → Google Sheets 연동 | ⭐⭐⭐ | 실시간 대시보드 |

---

## 📂 프로젝트 구조

```
cedu-1/
├── notebooks/          ← Google Colab 실행 파일 (12개)
│   ├── 01_branding.ipynb
│   ├── 02_counseling.ipynb
│   ├── ...
│   └── 12_cockpit.ipynb
├── labs/               ← 강의별 프롬프트 + 실습 가이드
│   ├── 01-branding/
│   │   └── README.md   ← 복사-붙여넣기용 프롬프트 모음
│   ├── 02-counseling/
│   └── ... (총 12개 강의 폴더)
└── shared/             ← 공용 샘플 데이터 (학생 CSV 등)
```

---

## 🌐 연결된 과정

| 과정 | 슬로건 | 레포 |
|------|--------|------|
| 📙 **cedu-1** 기초 | "AI에게 글을 시키다" | **현재 과정** |
| 📘 **cedu-2** 중급 | "AI에게 앱을 시키다" | [cedu-2](https://github.com/Reasonofmoon/cedu-2) |
| 📕 **cedu-3** 고급 | "AI로 제국을 세우다" | [cedu-3](https://github.com/Reasonofmoon/cedu-3) |
| 📖 **사과의 무게** | 이 과정의 "왜"를 다루는 책 | [weight-of-one-apple](https://github.com/Reasonofmoon/weight-of-one-apple) |

---

<div align="center">

**Made with ❤️ by [ConnectEdu × Reasonofmoon](https://github.com/Reasonofmoon)**  
*영어학원 원장을 위한 AI 실전 교육 · "코딩보다 원리가 먼저다"*

</div>
---

## Shared Data & Release

- Shared repository: [CEDU-data](https://github.com/Reasonofmoon/CEDU-data)
- Shared docs: 공통 운영 문서, 최신 AI 도구 가이드, 자산 생성 스크립트
- Current BKIT release: `CEDU BKIT 2026.03 R1`
- Current Git tag: `v2026.03-bkit.1`
- Release standard: [RELEASE_BKIT.md](https://github.com/Reasonofmoon/CEDU-data/blob/main/RELEASE_BKIT.md)

