<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14B8A6,100:0F766E&height=230&section=header&text=GajaGO&fontSize=72&fontColor=FFFFFF&fontAlign=50&fontAlignY=38&desc=AI%20Travel%20Assistant%20for%20Korea&descSize=22&descAlign=50&descAlignY=60" alt="GajaGO Capsule Header" />
</p>

<h2 align="center">가자GO</h2>

<p align="center">외국인 여행자를 위한 한국 여행 도우미 앱 (행사·길찾기·음식 알레르기·편의시설·일정·가계부)</p>

<p align="center">
  <img src="https://img.shields.io/badge/React%20Native-Expo%2054-61DAFB?style=for-the-badge&logo=react&logoColor=111827" alt="React Native" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS EC2" />
  <img src="https://img.shields.io/badge/Gemini%20%2B%20TMAP-AI%20Route-14B8A6?style=for-the-badge" alt="Gemini TMAP" />
</p>

---

## 📦 Repositories

| 레포 | 설명 | 기술 |
| --- | --- | --- |
| [**gajaGO-web**](https://github.com/Dankook-gajaGO/gajaGO-web) | 모바일 앱 (Android APK · Web) | React Native, Expo, TypeScript |
| [**gajaGo-server**](https://github.com/Dankook-gajaGO/gajaGo-server) | 메인 API · AI 교통 챗봇 · 축제 수집기 | Spring Boot, FastAPI, MySQL, Docker |

---

## 📱 시연 화면

<table>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/home.png" width="190" alt="홈" /><br /><b>홈</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/event.png" width="190" alt="행사 상세" /><br /><b>행사 상세</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/route.png" width="190" alt="교통 챗봇 경로" /><br /><b>교통 챗봇 경로</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/food.png" width="190" alt="음식 알레르기" /><br /><b>음식 알레르기</b></td>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/facilities.png" width="190" alt="주변 편의시설" /><br /><b>주변 편의시설</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/expense.png" width="190" alt="여행 가계부" /><br /><b>여행 가계부</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/schedule.png" width="190" alt="내 일정" /><br /><b>내 일정</b></td>
    <td align="center"><img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/screens/calendar.png" width="190" alt="캘린더" /><br /><b>캘린더</b></td>
  </tr>
</table>

---

## ✨ 주요 기능

| 영역 | 핵심 기능 | 비회원 | 회원 |
| --- | --- | :---: | :---: |
| 🎉 행사·축제 | 최근·곧 열리는 행사 추천, 상세, 지도(구글·카카오), 행사장으로 바로 길찾기 | ✅ | ✅ |
| 🚇 교통 챗봇 | 자연어 길찾기, 현재 위치 출발, TMAP(실패 시 카카오) 경로 3개와 Gemini 추천 순위 | ✅ | ✅ |
| 🍜 음식 알레르기 | 알레르기 11종 + 식단·취향 필터 (안 매운·채식·돼지고기·술 없음) | ✅ | ✅ |
| 🪪 보여주기 카드 | 알레르기·도움 요청을 한국어 카드로 제시 | ✅ | ✅ |
| 🏧 편의시설 | 은행·ATM·편의점·화장실·약국·지하철역·환전소 | ✅ | ✅ |
| 💰 여행 가계부 | 10개 외화 환산, 여행별 집계, N빵, 영수증 이미지 공유 | ✅ (앱을 끄면 삭제) | ✅ (서버 저장) |
| 📅 일정·캘린더 | 행사·경로·메모 저장, 여행 N일차, 이날 가계부, 선택형 알림 | - | ✅ |
| 🆘 긴급 | 112·119·1330 원터치 전화, 도움 요청 카드 | ✅ | ✅ |

---

## 🏗 시스템 아키텍처

<p align="center">
  <img src="https://raw.githubusercontent.com/Dankook-gajaGO/.github/main/profile/images/architecture.webp" alt="가자GO 시스템 아키텍처" width="100%" />
</p>

---

## 🛠 기술 스택

| 영역 | 기술 |
| --- | --- |
| Mobile | React Native, Expo, TypeScript, React Navigation, AsyncStorage, Expo Location, Expo Notifications |
| Backend | Java 17, Spring Boot, Spring Security (JWT · BCrypt), Spring Data JPA, MySQL |
| AI / Transport | FastAPI, Gemini API, TMAP POI · Transit API, Kakao 대중교통 경로(예비) |
| Data | 한국관광공사 TourAPI, 환율 API |
| Infra | Docker Compose, AWS EC2, EAS Build |

---

## 🛣 로드맵

- [x] AI 교통 챗봇 · 현재 위치 출발 · 행사장 바로 길찾기
- [x] 알레르기 프로필 저장 · 식단 필터 · 보여주기 카드
- [x] 여행 가계부 · 환율 환산 · 영수증 공유
- [x] TourAPI 행사 자동 수집
- [x] AWS EC2 상시 배포
- [ ] 🌏 영어 · 중국어 · 일본어 다국어 지원
- [ ] 📷 메뉴판 OCR + Gemini 재료 추론
- [ ] 🗺 앱 내부 지도 마커 · 경로 시각화
- [ ] 🔒 HTTPS · 도메인 연결 · 모니터링

---

<p align="center"><b>Team 가자GO</b> · 단국대학교</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,100:14B8A6&height=120&section=footer" alt="GajaGO Capsule Footer" />
</p>
