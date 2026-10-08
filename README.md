# 장정현 · Jang JungHyeon

**아이디어를 웹과 모바일 서비스로 만들고, 인증·데이터·배포까지 연결합니다.**

동국대학교 컴퓨터AI학부 · Farm System 5기 보안/웹 활동

[개인 소개](https://introduce-junghyeon.netlify.app/) · [사주잘봄](https://sajujalbom.netlify.app/) · [타임캡슐](https://capsule-me-jang.vercel.app/) · [한소리 위키](https://hansoriwiki.pages.dev/)

## 어떤 일을 할 수 있나요?

- **웹 서비스 구현** — React와 Next.js로 화면, 입력 폼, 상태 관리, 로그인 흐름을 구현합니다.
- **인증과 데이터 연결** — Supabase Auth·PostgreSQL·Storage, Firebase Auth를 프로젝트에 연동합니다.
- **AI와 외부 API 연동** — Claude 해석 API, 서울시 버스 데이터, Kakao Maps를 서비스 기능으로 연결합니다.
- **모바일 앱 개발** — Expo와 React Native로 위치 기록, 지도 재생, 사진 업로드, Android·Web 화면을 구현합니다.
- **배포와 협업** — Vercel·Netlify·Cloudflare에 배포하고 GitHub 이슈, 기능 브랜치, PR로 작업을 공유합니다.

## 대표 프로젝트

| 프로젝트 | 무엇을 만들었나요? | 사용 기술 | 바로 보기 |
| --- | --- | --- | --- |
| **사주잘봄** | AI 사주·타로 해석, Google 로그인, 결과 저장·공유를 연결한 개인 웹 서비스 | React, Vite, Supabase, Claude API, Netlify | [코드](https://github.com/JungHyeon-archplot/sajujalbom) · [서비스](https://sajujalbom.netlify.app/) |
| **타임캡슐** | 편지와 사진을 저장하고 열람일·카운트다운으로 보여 주는 개인 웹 프로젝트 | Next.js, TypeScript, Tailwind CSS, Firebase Auth, Supabase, Vercel | [코드](https://github.com/JungHyeon-archplot/capsule-me-jang) · [데모](https://capsule-me-jang.vercel.app/) |
| **버스 노선 시뮬레이터** | 충무로·동국대 주변 노선 데이터로 버스 도착과 정차면 배치를 비교하는 팀 프로젝트 | JavaScript, Node.js, Kakao Maps, 서울시 API, Cloudflare Workers·D1 | [저장소](https://github.com/JungHyeon-archplot/Bus-Route-Optimization) · [구현 PR](https://github.com/JungHyeon-archplot/Bus-Route-Optimization/pull/15) |
| **개인 소개 웹사이트** | 반응형 자기소개 페이지, 연락처 모달, 웹앱 매니페스트와 검색·공유 메타데이터 | HTML, CSS, JavaScript, Netlify | [코드](https://github.com/JungHyeon-archplot/vibe_me_archplot) · [사이트](https://introduce-junghyeon.netlify.app/) |

버스 프로젝트의 지도 시뮬레이터 구현은 현재 PR에서 리뷰 중입니다. 시뮬레이션 결과와 실측 자료를 구분해 기록합니다. 타임캡슐의 구현 범위와 데이터 접근 제한은 해당 README에서 확인할 수 있습니다.

## 진행 프로젝트와 협업 경험

### 한소리 위키 · 개발·운영 중

동국대학교 풍물소모임 한소리의 문서와 활동을 기록하는 위키를 개발하고 있습니다. Google 로그인과 가입 승인, 역할별 접근 권한, Markdown 편집, 문서 이력, 사진·영상, 운영 관리와 백업 기능을 구현했습니다.

`React` `Vite` `Supabase` `PostgreSQL / RLS` `Cloudflare Pages / Workers` `GitHub Actions`

[서비스](https://hansoriwiki.pages.dev/) · [프로젝트 소개](projects/hansoriwiki.md)

### GeoLog / 갤로그 · Android·Web 앱 구현

팀 프로젝트에서 Expo·React Native 앱 구현에 참여했습니다. GPS 경로 기록과 지도 재생, 사진 연결, 계정·프로필, 친구·그룹, Supabase 동기화를 구현했습니다. 기존 iOS 앱은 참고 소스로 활용했습니다.

`TypeScript` `React Native` `Expo` `Supabase` `위치 기록 / 지도`

[프로젝트 소개와 참여 범위](projects/geolog.md)

### Farm System 5기 · 보안/웹 여름 워크숍

Fullstack2 팀의 공동 자기소개 페이지에 개인 섹션을 구현했습니다. CSS·JavaScript 파일을 팀원별로 나누고 개인 영역 아래로 스타일 범위를 제한해 협업 시 충돌을 줄이는 구조를 제안했습니다.

[팀 저장소](https://github.com/DguFarmSystem/5th-security-summer-fullstack2) · [병합된 기여 PR](https://github.com/DguFarmSystem/5th-security-summer-fullstack2/pull/3)

## 기술 스택

| 분야 | 프로젝트에서 사용한 기술 |
| --- | --- |
| 언어 | JavaScript, TypeScript, HTML, CSS, SQL |
| 웹 | React, Next.js App Router, Vite, Tailwind CSS |
| 모바일 | React Native, Expo, Expo Router, 위치·미디어 API |
| 인증·데이터 | Supabase Auth, PostgreSQL, RLS, Storage, Firebase Auth |
| 외부 서비스 | Claude API, Kakao Maps, 서울시 버스 API, Google Analytics |
| 배포·운영 | Vercel, Netlify, Cloudflare Pages·Workers·D1, GitHub Actions |
| 협업 | Git, GitHub Issues, 기능 브랜치, Pull Requests |

프로젝트에서 실제 사용한 기술을 정리했습니다. 각 프로젝트의 현재 구현 범위는 연결된 코드와 문서에서 확인할 수 있습니다.

## 연락

- [GitHub](https://github.com/JungHyeon-archplot)
- [개인 소개 웹사이트](https://introduce-junghyeon.netlify.app/)

<sub>프로젝트 소개 업데이트: 2026-10-08</sub>
