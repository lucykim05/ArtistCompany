

# 🎬 Artist Company Re-design

<img 
  src="https://raw.githubusercontent.com/lucykim05/ArtistCompany/develop/public/images/logo-crop.png"  />

## 🔧 Tech Stack

### FrontEnd

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-EF0178?style=for-the-badge&logo=framer&logoColor=white)
![Lucide React](https://img.shields.io/badge/Lucide_React-000000?style=for-the-badge&logo=lucide&logoColor=white)
![React Slick](https://img.shields.io/badge/React_Slick-005571?style=for-the-badge&logo=react&logoColor=white)
![React Calendar](https://img.shields.io/badge/React_Calendar-ff6f00?style=for-the-badge&logo=react&logoColor=white)

### Deploy & Infra

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://amplified-pot-cae.notion.site/ArtistCompany-1dd75c00010a800a9663eaefbaf45db8)

### Etc

![Day.js](https://img.shields.io/badge/Day.js-DD0031?style=for-the-badge&logo=javascript&logoColor=white)
![URL Metadata](https://img.shields.io/badge/url--metadata-808080?style=for-the-badge)

---

---

## 🧭 프로젝트 개요

**프로젝트명**: Artist Company Re-design

**프로젝트 소개**: 기존 Artist Company 웹사이트를 리디자인하여 사용자 경험을 향상시키는 프로젝트입니다.

**개발 기간**: 2025년 4월 11일 ~ 2025년 5월 22일

**참여 인원**: 1명 (개인 프로젝트)

---

## 🛠️ 시작 가이드

### ✅ 요구 사항

Node.js (v16 이상)
npm 또는 yarn

## 🚀 설치 및 실행

```bash
# 1. 레포지토리 클론
git clone https://github.com/lucykim05/ArtistCompany.git

# 2. 디렉토리 이동
cd ArtistCompany

# 3. 패키지 설치
npm install

# 4. 개발 서버 실행
npm run dev
```

---

## 🌟 주요 기능

🎨 **홈페이지 리디자인** — 현대적인 UI/UX로 개선 및 취약점 대응 방안 반영

🧑‍🎤 **배우 소개 페이지** — 프로필/생일/데뷔작/이미지 제공

📰 **뉴스 섹션** — 외부 뉴스 링크 메타데이터 카드 구성

📺 **유튜브 콘텐츠** — Supabase에 저장된 영상 메타로 썸네일 카드 제공

📱 **반응형 지원** — PC/Mobile에 따라 슬라이드 및 카드 최적화

<br>

## ✨ 변경 사항 하이라이트 (What’s Changed)

**[신규] Admin 콘솔**: 뉴스/스케줄을 웹에서 직접 등록·관리

**[신규] YouTube 동기화**: `/api/sync-youtube` 접속 시 최신 영상 메타 갱신

**[개선] 뉴스 카드**: 외부 기사 URL 메타데이터(제목/요약/작성일) 자동 수집

**[개선] 반응형 레이아웃**: PC/Mobile 전용 그리드 & 캐러셀 최적화

**[개선] 내비게이션**: Artist/Film 상세 간 좌우 이동 + 사이드 메뉴

**[안정성] 에러 페이지**: 커스텀 404/500으로 내부 정보 노출 최소화

**[정리] 라우트 표준화**: `shedule` → `schedule` 오타 수정

<br>

## 🔐 보안/운영 상의 결정(리디자인 반영)
> 공개적으로 확인 가능한 이슈를 **기획 관점**에서 대응. 침투/스캔 등은 수행하지 않음.

**관리자 경로 보호**: `/admin` 전 구간 미들웨어 인증

**비밀정보 외부화**: 관리자 비밀번호/서비스 키는 `.env.local`로만 관리(코드/문서 평문 노출 금지)

**오류 응답 최소화**: 커스텀 404/500 적용으로 내부 스택/구조 노출 방지

**인증 실패 메시지 통일**: 계정/비번 유추 방지(“인증 실패”로 단일화)


---

## 👩‍💻 개발자 정보

**이름**: 김희주 (Lucy Kim)

**GitHub**: [lucykim05](https://github.com/lucykim05)

**이메일**: effelt0522@naver.com

**Notion**: [프로젝트 노션 페이지](https://amplified-pot-cae.notion.site/ArtistCompany-1dd75c00010a800a9663eaefbaf45db8)

---

## 📄 문서 및 참고 자료

🔗 [Artist Company 공식 사이트](https://www.artistcompany.co.kr/)
🗂️ [프로젝트 기획 및 기록 (Notion)](https://amplified-pot-cae.notion.site/ArtistCompany-1dd75c00010a800a9663eaefbaf45db8)

---

