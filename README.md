# 임종서 (JongSeo Im)

- 관심 분야 — Medical AI · Biomedical Signal Processing · Web Application
- Email — [serendipty1401@gmail.com](mailto:serendipty1401@gmail.com)

## 프로젝트

### Smart Mirror

`2024년 1학기 · 3인 팀`

Raspberry Pi와 MagicMirror²를 이용해 거울 화면에서 시간, 일정, 뉴스, 날씨와 미세먼지 정보를 확인하고 음성으로 일부 기능을 제어하는 IoT 프로젝트입니다.

> **확인 범위** — 외부 API와 계정 기반 서비스는 2024년 당시의 설정·정책에 의존하므로, 현재 사용 가능 여부는 별도 확인이 필요합니다.

- Google Calendar, 날씨, 미세먼지 API 조사와 연동
- Google Assistant와 Spotify 연동에 필요한 API 설정 지원
- USB 마이크·스피커 인식 확인 및 ALSA 입출력 설정
- Raspberry Pi 4, 7인치 터치스크린, 하프 미러 필름과 프레임을 조합한 스마트 미러 제작 참여

[저장소 보기 →](https://github.com/JongSeoIm/Smart_Mirror)

---

### NUGUJU

`2024.08–2024.11`

시니어 사용자가 주문 과정을 쉽게 따라갈 수 있도록 화면과 선택 흐름을 단순화한 Android 키오스크 프로토타입입니다.

> **확인 범위** — 카드 결제 화면은 실제 결제 단말기나 결제 API와 연결하지 않은 UI 시뮬레이션입니다.

- PowerPoint로 31개 화면의 클릭형 UI 프로토타입 설계
- 메뉴 탐색, 옵션 선택, 장바구니, 결제, 주문 완료까지의 화면 흐름 구성
- Android XML로 키오스크 화면 구현
- Kotlin으로 옵션 선택, 장바구니 상태와 금액 계산 구현
- 주문 금액과 장바구니 상태에 대한 단위 테스트 13개 구성

[저장소 보기 →](https://github.com/JongSeoIm/DSC_NUGUJU)

---

### ClearTalk

`2024년 2학기 · 5인 팀 · QA`

기준 단어 듣기, Android 음성 인식, 반복 학습 기록을 연결한 발음 연습 애플리케이션입니다.

> **확인 범위** — 기준 단어와 음성 인식 결과의 문자열 유사도를 보여주며, 실제 발음 정확도나 치료 효과를 판단하는 앱은 아닙니다.

팀 프로젝트에서 QA를 담당했습니다.

- 요구사항 분석서와 요구사항 심사서 작성
- 위험관리 계획서와 품질관리 계획서 작성
- 단위시험과 통합시험 계획 수립
- 시험 결과와 완료 산출물 정리
- 팀 전체 구현 기능과 개인 QA 담당 범위를 분리해 문서화

[저장소 보기 →](https://github.com/JongSeoIm/ClearTalk)

---

### Skin Lesion Classification

`2025년 1학기 · 4인 팀 · MobileNet 학습·공개용 정리`

피부 병변 이미지를 입력받아 피부 여부를 먼저 확인하고, 피부로 판정된 이미지에는 7개 병변 범주 중 확률이 높은 3개 후보를 보여주는 브라우저 기반 분류 보조 웹 서비스입니다.

> **확인 범위** — 의료 진단이나 치료 판단을 위한 서비스가 아니며, 공개 저장소에는 모델 가중치와 원본 학습 로그가 없어 성능을 독립적으로 재현할 수 없습니다.

- HAM10000 기반 MobileNet 7개 병변 범주 분류 학습 코드 구성
- 피부 여부를 먼저 확인하는 이진 분류 필터 학습·평가 흐름 구성
- 클래스 가중치 적용, 검증 세트 평가, 혼동 행렬과 분류 리포트 코드 작성
- 공개용 포트폴리오 정리 과정에서 원본 병변 이미지, 학습 산출물과 Firebase 저장·조회 연결 분리
- 브라우저에서 Top-3 결과를 보여주는 TensorFlow.js 추론 흐름 확인

[저장소 보기 →](https://github.com/JongSeoIm/SkinCancer)

---

### HIPPIE Memora

`2025.09–2025.12 · 6인 팀 · ENG1`

MRI 영상에서 해마 영역을 분할하고, 좌·우 해마 부피와 정량 특징을 계산해 CN/AD 모델 출력을 Web 화면에서 확인하는 연구·교육용 프로토타입입니다.

MRI 입력은 NIfTI 또는 DICOM ZIP으로 받고, 변환·해마 분할·특징 계산·XGBoost 추론을 거쳐 결과를 저장하고 화면에 표시하도록 구성했습니다.

> **확인 범위** — 실제 의료 진단이나 치료 판단을 위한 시스템은 아니며, 공개 저장소에는 의료영상 원본·환자 정보·학습 데이터·평가 로그를 포함하지 않았습니다.

- HippMapp3r를 이용한 좌·우 해마 분할 흐름 구성
- 해마 부피, ICV, 비대칭 지수와 ICV 정규화 특징 계산
- 10개 입력 특징을 사용하는 XGBoost 학습·추론 코드 구성
- FastAPI에서 AI 처리 결과를 받아 MySQL과 Web Viewer에 연결
- MRI 원본, 해마 마스크, 정량 지표와 검사 이력을 화면에서 확인하는 흐름 통합

[저장소 보기 →](https://github.com/JongSeoIm/HIPPIE_Memora)

---

### ECG 기반 심장 지문 생성 및 개인 식별

`2026.03–2026.06 · 5인 팀 · ENG2`

Galaxy Watch에서 측정한 ECG를 전처리하고 딥러닝 임베딩으로 변환한 뒤, 등록 신호와 비교해 인증 결과를 보여주는 Wear OS·Web·AI 통합 인증 프로토타입입니다.

> **확인 범위** — 의료 진단이나 상용 인증을 목적으로 하지 않으며, 발표 성능은 ECG-ID Database의 closed-set 평가 기록입니다.

- ECG-ID Database 신호를 불러와 필터링하고 R-peak 기준으로 심박 구간 분할
- ResNet1D, Plain CNN1D, BiLSTM, CNN-BiLSTM의 학습·평가 흐름 구성
- 256차원 임베딩 추출, cosine similarity 비교, 임계값 보정 도구 구현
- Galaxy Watch ECG 수집·전송 앱, Flask API, SQLite 인증 기록과 Web 대시보드 연결
- 신호 품질, 심박수, RR 간격, HRV 보조 지표를 화면에 표시

최종 발표 자료에는 ECG-ID Database 90명, 약 310개 기록에서 추출한 약 7,430개 심박 구간으로 평가한 결과가 남아 있습니다. 네 모델 중 Plain CNN1D가 AUC `0.9928`, EER `0.0365`를 기록해 Web 인증 흐름의 임베딩 모델로 선택됐습니다. 원본 학습 로그와 모델 가중치는 공개 저장소에 포함되어 있지 않아 이 수치를 독립적으로 재현할 수는 없습니다.

[저장소 보기 →](https://github.com/JongSeoIm/26_Capstone)

---

## 개인 프로젝트

| 프로젝트 | 내용 |
| --- | --- |
| [React Stock](https://github.com/JongSeoIm/React_Stock) | Finnhub 데이터를 조회해 미국 주식의 시세, 기업 정보, 뉴스와 차트를 보여주는 Next.js 대시보드 |
| [WorkGrid](https://github.com/JongSeoIm/WorkGrid) | 일정, 프로젝트, 반복 일정과 월간 달력을 관리하는 SQLite 기반 로컬 우선 플래너 |

## 사용한 기술

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

**IoT**<br>
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
<img src="https://img.shields.io/badge/MagicMirror%C2%B2-000000?style=flat-square" alt="MagicMirror²">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Google_Assistant-4285F4?style=flat-square&logo=googleassistant&logoColor=white" alt="Google Assistant">
