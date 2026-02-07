<p align="center">
  <img src="https://github.com/dinah05/email-template/blob/main/assets/travlocks_logo.png?raw=true" alt="Travlocks Logo" width="220" />
</p>

# ✈️ Travlocks

UMC 9th Project  
여행 일정을 **빠르게, 재미있게, 직관적으로** 만드는 블록형 여행 일정 웹 서비스

---

## ✨ Travlocks는 이런 서비스예요

Travlocks는  
**AI를 활용해 여행 일정을 빠르고 직관적으로 설계할 수 있도록 돕는 블록형 여행 일정 웹 서비스**입니다.
- 텍스트 입력이나 복잡한 리스트 작성이 아닌,
- 블록을 쌓듯 직관적으로 여행 일정을 구성해
- 여행 설계의 **인지적 부담**을 줄이는 것에 집중합니다.

> “여행을 ‘짜는’ 게 아닌 ‘쌓는’ 즐거움을 유저에게”

---

## 🚀 MVP 핵심 기능

### 1️⃣ 블록 기반 여행 일정 설계

- 호텔, 관광지, 카페 등 여행 요소를 **블록 단위 UI**로 표현
- Drag & Drop 방식으로 블록을 조합하며 일정 구성
- 타임라인 / 지도 경로 기반으로 완성된 여행 코스 시각화
- 각 블록에 메모 및 주소 첨부 가능
- **카카오 지도 검색 API**를 활용한 장소 탐색

---

### 2️⃣ 시각적 피드백 & 인터랙션

- 블록 추가·이동 시 색감, 애니메이션 피드백 제공
- 사용자의 행동에 즉각 반응하는 UI로 여행 설계 과정의 몰입감 강화

---

### 3️⃣ AI 여행 동선 추천

- 사용자가 쌓은 블록의 **위치·맥락·선택 패턴**을 기반으로  
  → “이 다음엔 이런 블록은 어때요?” 형태의 AI 블록 추천
- 이동 거리, 시간 최적화를 위한 AI 스마트 정렬

---

### 4️⃣ 일정 공유 & 재사용

- 완성된 여행 블록 조합을 **템플릿 형태로 저장**
- 다른 사용자가 해당 템플릿을 **리믹스(수정·확장)** 하여 재사용 가능

---

## 🧩 프로젝트 구성

| 영역 | 저장소 |
|---|---|
| Frontend (Web) | Travlocks Web |
| Backend (SpringBoot) | Travlocks Server |

- 프론트엔드와 백엔드는 **각각 독립된 저장소**로 관리됩니다.
- 기술 스택, 프로젝트 구조, 세부 규칙은 각 저장소의 README를 따릅니다.

---

---

## 👥 팀 소개

### 🙋🏻‍♀️ PM / PD

| <a href="https://github.com/dinah05"><img src="https://github.com/dinah05.png" width="120px" /></a> | <a href="https://github.com/yeyimee"><img src="https://github.com/yeyimee.png" width="120px" /></a> |
| :---: | :---: |
| **윤다인**<br/>PM · Team Lead | **권예림**<br/>PD |

---

### 🙋🏻‍♀️ Frontend Developers

| <a href="https://github.com/jinhyo0"><img src="https://github.com/jinhyo0.png" width="120px" /></a> | <a href="https://github.com/seongmin36"><img src="https://github.com/seongmin36.png" width="120px" /></a> | <a href="https://github.com/onebone"><img src="https://github.com/onebone.png" width="120px" /></a> | <a href="https://github.com/codmoni"><img src="https://github.com/codmoni.png" width="120px" /></a> |
| :---: | :---: | :---: | :---: |
| **김진효**<br/>FE Lead | 조성민 | 정윤철 | 황무원 |

---

### 🙋🏻‍♀️ Backend Developers

| <a href="https://github.com/hyomee2"><img src="https://github.com/hyomee2.png" width="120px" /></a> | <a href="https://github.com/dh2e"><img src="https://github.com/dh2e.png" width="120px" /></a> | <a href="https://github.com/kdhdd"><img src="https://github.com/kdhdd.png" width="120px" /></a> | <a href="https://github.com/dppfls"><img src="https://github.com/dppfls.png" width="120px" /></a> | <a href="https://github.com/Suhyeon7"><img src="https://github.com/Suhyeon7.png" width="120px" /></a> | <a href="https://github.com/jeondain"><img src="https://github.com/jeondain.png" width="120px" /></a> |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **권형미**<br/>BE Lead | 권도희 | 김도현 | 김예린 | 장수현 | 전다인 |

---

---

## 🔧 협업 방식

### 📌 Git Flow (공통)

- `main` : 배포 / 운영 브랜치  
- `develop` : 개발 브랜치  
- `feature` : 기능 단위 작업 브랜치  

### ✨ 작업 흐름

1. 이슈 생성
2. 이슈 번호 기준 브랜치 생성
3. 작업 후 커밋 컨벤션에 맞게 커밋
4. Pull Request 생성
5. 코드 리뷰 후 develop 브랜치로 병합

> 승인 인원 및 세부 규칙은 FE / BE 저장소의 README를 기준으로 합니다.

---

## 📄 문서 & 규칙

- 커밋 컨벤션 / 브랜치 전략 / 프로젝트 구조 / 이슈 / PR 템플릿
  → 각 저장소의 README 참고

---

## 🚀 Project Status

- 현재 상태: **Web 서비스 개발 진행 중**
- 데모데이를 목표로 MVP 기능 구현에 집중하고 있으며,  
  프로젝트 구조 및 문서는 지속적으로 업데이트될 예정입니다.
