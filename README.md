## 핵심 역량

- ECG와 MRI 데이터를 처리해 모델 입력, 정량 특징과 서비스 결과로 연결
- 팀 프로젝트에서 ENG1·ENG2·QA 역할을 맡아 구현 범위와 공동 산출물을 구분
- 의료·생체정보 프로젝트의 재현 한계, 개인정보와 데이터·SDK 이용 조건을 문서화

## 대표 프로젝트

<table align="center">
  <thead>
    <tr>
      <th align="center">프로젝트</th>
      <th align="center">한 줄 요약</th>
      <th align="center">본인 기여</th>
      <th align="center">핵심 기술</th>
      <th align="center">검증 가능한 결과</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/HIPPIE_Memora"><strong>HIPPIE Memora</strong></a><br><sub>알츠하이머 MRI 분석 · 2025.09–2025.12 · ENG1</sub></td>
      <td>MRI 해마 분할과 정량 특징을 이용해 정상군(CN)·알츠하이머병(AD) 모델 출력을 확인하는 연구용 프로토타입</td>
      <td>해마 분할 흐름, 부피·비대칭·ICV 특징, XGBoost, FastAPI·Web 연결</td>
      <td>Python · HippMapp3r · XGBoost · FastAPI · MySQL</td>
      <td>10개 입력 특징 기반 추론과 MRI·마스크·정량 지표 조회 흐름 구현</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/26_Capstone"><strong>ECG 기반 심장 지문</strong></a><br><sub>2026.03–2026.06 · ENG2</sub></td>
      <td>Galaxy Watch ECG를 딥러닝 임베딩으로 변환해 등록 신호와 비교하는 인증 프로토타입</td>
      <td>ECG 전처리, 4개 모델 학습·평가, 256차원 임베딩, Wear OS–Flask–Web 통합</td>
      <td>Python · TensorFlow · Flask · Wear OS · SQLite</td>
      <td>발표 기록 기준 Plain CNN1D AUC <code>0.9928</code>, EER <code>0.0365</code></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/SkinCancer"><strong>Skin Lesion Classification</strong></a><br><sub>2025년 1학기</sub></td>
      <td>피부 여부를 확인한 뒤 7개 병변 범주의 Top-3 후보를 보여주는 분류 보조 Web 서비스</td>
      <td>MobileNet 학습 흐름, 클래스 가중치·평가 코드, 공개 저장소 정리</td>
      <td>TensorFlow · MobileNet · TensorFlow.js · Firebase</td>
      <td>이진 필터와 7개 범주 분류, 브라우저 Top-3 추론 흐름 확인</td>
    </tr>
  </tbody>
</table>

## 프로젝트 경험

<table align="center">
  <thead>
    <tr>
      <th align="center">프로젝트</th>
      <th align="center">한 줄 요약</th>
      <th align="center">본인 기여</th>
      <th align="center">기술·확인 결과</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/ClearTalk"><strong>ClearTalk</strong></a><br><sub>2024년 2학기 · QA</sub></td>
      <td>기준 단어 듣기, Android 음성 인식과 반복 학습 기록을 연결한 발음 연습 앱</td>
      <td>요구사항·위험·품질관리 문서와 단위·통합시험 계획 및 결과 정리</td>
      <td>Android · Java · Firebase<br>문자열 유사도 기반 학습 흐름</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/DSC_NUGUJU"><strong>NUGUJU</strong></a><br><sub>2024.08–2024.11</sub></td>
      <td>시니어 사용자를 위해 주문 단계를 단순화한 Android 키오스크 프로토타입</td>
      <td>31개 화면 프로토타입, Android XML 화면과 Kotlin 장바구니·금액 로직</td>
      <td>Android · Kotlin · XML<br>단위 테스트 13개 구성</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/Smart_Mirror"><strong>Smart Mirror</strong></a><br><sub>2024년 1학기</sub></td>
      <td>일정, 뉴스, 날씨와 음성 제어를 거울 화면에 결합한 IoT 프로젝트</td>
      <td>외부 API·음성 서비스 설정, 오디오 입출력 확인과 하드웨어 제작 참여</td>
      <td>Raspberry Pi · MagicMirror² · Node.js<br>API·장치 통합</td>
    </tr>
  </tbody>
</table>

> **확인 범위** — ClearTalk의 일치율은 음성 인식 문자열 비교값이며 발음 정확도나 치료 효과가 아닙니다. NUGUJU의 결제 화면은 실제 결제 연동이 아닌 UI 시뮬레이션입니다. Smart Mirror의 외부 API와 계정 서비스는 2024년 당시 설정에 의존하므로 현재 사용 가능 여부를 별도로 확인해야 합니다.

## 개인 프로젝트

<table align="center">
  <thead>
    <tr>
      <th align="center">프로젝트</th>
      <th align="center">한 줄 요약</th>
      <th align="center">핵심 기술</th>
      <th align="center">확인 가능한 구현</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/React_Stock"><strong>React Stock</strong></a></td>
      <td>미국 주식의 시세, 기업 정보, 뉴스와 차트를 조회하는 반응형 대시보드</td>
      <td>Next.js · React · Recharts · Zustand · Finnhub</td>
      <td>서버 API Route, 관심 종목 저장, 로딩·오류·반응형 상태 처리</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/JongSeoIm/WorkGrid"><strong>WorkGrid</strong></a></td>
      <td>일정, 프로젝트, 반복 일정과 월간 달력을 관리하는 로컬 우선 플래너</td>
      <td>Python · JavaScript · SQLite</td>
      <td>로컬 저장, 반복 일정 회차별 완료, 프로젝트·달력 통합 관리</td>
    </tr>
  </tbody>
</table>

React Stock은 종목 정보 확인용이며 투자 자문이나 수익을 보장하지 않습니다. WorkGrid의 실제 일정과 로컬 DB는 공개 저장소에 포함하지 않습니다.

## 기술 범위

- **AI · Data** — Python · TensorFlow · PyTorch · XGBoost · Jupyter
- **Backend · Database** — FastAPI · Flask · Firebase · MySQL · SQLite
- **Web · App · Device** — Next.js · React · JavaScript · Android · Java · Kotlin · Wear OS · Raspberry Pi

> 프로젝트별 상세 구현, 실행 방법, 데이터·라이선스 조건과 제한 사항은 연결된 저장소 README에서 확인할 수 있습니다.
