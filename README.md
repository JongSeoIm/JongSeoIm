# 임종서 | JongSeo Im

의료·헬스케어 데이터를 AI 모델과 실제 사용 흐름으로 연결하는 프로젝트를 수행해 왔습니다.

Android 키오스크와 발음 연습 프로젝트에서 UI 구현과 QA를 경험했으며, 이후 MRI 해마 분석과 ECG 생체인식 프로젝트에서 데이터 전처리, 모델 구현, API와 Web 연동을 담당했습니다.

- 관심 분야 — Medical AI · Biomedical Signal Processing · Web Application
- Email — [serendipty1401@gmail.com](mailto:serendipty1401@gmail.com)

## Medical AI & Healthcare Projects

### ECG 기반 심장 지문 생성 및 개인 식별

`2026.03–2026.06 · 5인 팀 · ENG2`

Galaxy Watch에서 수집한 ECG를 딥러닝 임베딩으로 변환하고 등록 신호와 비교하는 Wear OS·Web·AI 통합 인증 프로토타입입니다.

- ECG-ID 신호의 필터링, R-peak 검출과 심박 구간 분할 파이프라인 구현
- ResNet1D, Plain CNN1D, BiLSTM, CNN-BiLSTM 학습·평가 흐름 구성
- 256차원 임베딩과 cosine similarity 기반 등록·인증 로직 구현
- Galaxy Watch 수집 앱, Flask API, SQLite와 Web 대시보드 연결
- 네 모델 비교 후 Plain CNN1D를 Web 인증 흐름의 임베딩 모델로 적용

[프로젝트 자세히 보기 →](https://github.com/JongSeoIm/26_Capstone)

### HIPPIE Memora

`2025.09–2025.12 · 6인 팀 · ENG1`

MRI 영상에서 해마를 분할하고 정량 특징과 CN/AD 모델 출력을 Web 화면에서 확인하는 연구·교육용 프로토타입입니다.

- HippMapp3r 기반 좌·우 해마 분할 흐름 구성
- ICV와 해마 부피, 비대칭 지수 및 정규화 특징 계산
- 10개 특징을 사용하는 XGBoost 학습·추론 코드 구성
- AI 처리 결과를 FastAPI, MySQL과 Web Viewer에 연결

[프로젝트 자세히 보기 →](https://github.com/JongSeoIm/HIPPIE_Memora)

### ClearTalk

`2024년 2학기 · 5인 팀 · QA`

기준 단어 듣기, Android 음성 인식과 반복 학습을 연결한 발음 연습 애플리케이션입니다.

- 요구사항 분석서와 요구사항 심사서 작성
- 위험관리 및 품질관리 계획 수립
- 단위시험과 통합시험 계획 및 결과 정리
- 팀 구현 기능과 개인 QA 담당 범위를 분리해 문서화

[프로젝트 자세히 보기 →](https://github.com/JongSeoIm/ClearTalk)

## Other Projects

| 프로젝트 | 내용 | 주요 작업 |
| --- | --- | --- |
| [NUGUJU](https://github.com/JongSeoIm/DSC_NUGUJU) | 시니어 사용자를 위한 단계형 Android 키오스크 | 클릭형 UI 프로토타입, Kotlin 주문 흐름과 장바구니 구현 |
| [React Stock](https://github.com/JongSeoIm/React_Stock) | Finnhub 기반 미국 주식 정보 대시보드 | Next.js API Route, 종목 검색·차트·관심 종목 |
| [WorkGrid](https://github.com/JongSeoIm/WorkGrid) | SQLite 기반 로컬 우선 개인 플래너 | 일정·프로젝트·반복 일정과 월간 달력 구현 |

## Technologies

**AI · Data**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/XGBoost-EB5B29?style=flat-square" alt="XGBoost">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">

**Backend · Database**<br>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">

**Web · App**<br>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111" alt="React">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111" alt="JavaScript">
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android">
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
<img src="https://img.shields.io/badge/Wear_OS-4285F4?style=flat-square&logo=wearos&logoColor=white" alt="Wear OS">
