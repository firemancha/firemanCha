## 차윤성 · Frontend Developer

B2B HR SaaS와 반도체 사내 플랫폼에서 일한 프론트엔드 개발자입니다. PIMS는 MVP를 3개월간 함께 만들었고, Binder에서는 운영 중인 제품의 에디터와 공통 UI를 다시 만들었습니다. 세 제품에서 디자인 시스템을 만들었고, 그중 두 곳은 주도했습니다.

**주력** React · TypeScript · Next.js · TanStack Query · Tailwind CSS  
<sub>경력 3년 11개월 · 회사 프로젝트 코드는 비공개입니다</sub>

## 대표 프로젝트

### Binder <sub>(도티오)</sub>
<sub>2024.04 – 2026.05 · 프론트엔드 담당 (개발팀 2인) · B2B HR 온보딩 SaaS, 고객사 16곳</sub>

- **리치 텍스트 에디터 전환**: Quill 기반 에디터를 Tiptap으로 전면 재구축(**193개 파일**). 커스텀 Node 13종, Extension 5종 구현. 기존 Quill 문서는 변환 계층을 두어 그대로 열리게 하고, 에디터 진입점 6곳은 next/dynamic으로 초기 번들에서 분리
- **디자인 시스템 통합**: 화면마다 따로 만들어져 동작이 달랐던 드롭다운, 필터를 shadcn/ui(Radix) 기반 공통 컴포넌트로 통합. Select·DataTable·Command 등 **14개 계열(파일 49개)** 신규 구현, **구식 컴포넌트 17종** 제거, 앱 화면 78개 파일 이전
- **서베이 분석 대시보드**: 질문 유형 4가지에 맞춘 시각화 컴포넌트 **11종**을 차트 라이브러리 없이 구현. NPS 막대의 정수 % 라벨 합이 100%가 되도록 largest remainder 방식으로 보정. 응답 표에 다중 정렬, 기간 필터 연동
- **라이브러리 교체·도입**: Tiptap, TanStack Query v5, Recoil에서 Jotai, React 19 교체 4건과 shadcn/ui, next-intl 도입 2건. stacked PR로 나눠 staging에서 안정성을 확인한 뒤 단계별로 머지. 같은 기간 동료 PR **423건** 리뷰

### FMS Dashboard <sub>(파두)</sub>
<sub>2023.05 – 2023.10 · 저장소 커밋 76% · Flash Memory Summit 2023 부스 시연용 실시간 성능 대시보드</sub>

- Tauri 데스크톱 앱의 React 프론트엔드 주도, Rust 쪽과 IPC 연동. 그래프, 게이지, 관리 화면 3개 창 구성
- D3.js로 시계열 라인, 게이지, 속도계, 온도계 등 커스텀 차트 **5종** 구현
- WebGL 가속이 필요하다는 가설을 2주간 SVG와 나란히 돌려 검증. 1초 단위 시계열에서는 차이가 거의 없어 WebGL 코드를 걷어내고 SVG로 확정

### TMS · PIMS <sub>(파두)</sub>
<sub>2022.09 – 2024.03 · 사내 SSD 검증 운영 플랫폼, 반도체 생산관리 시스템</sub>

- 시료 개별·일괄 등록, 편집, 삭제와 엑셀 업로드를 화면부터 API까지 구현. 빈 파일 업로드 등 예외 처리 보완
- TMS 디자인 시스템 **공동 구축**(38종 중 **14종**, Story 15건). Chromatic 스냅샷을 리뷰가 필요한 화면에만 찍도록 정책 설계
- PIMS 공통 컴포넌트 38종 중 **33종** 설계·구현
- TanStack Query 데이터 훅 **37개** 담당, **28개 화면**에 캐시 무효화와 낙관적 갱신 적용

## 기술

<p><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat&logo=reactquery&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Jotai-000000?style=flat"/> <img src="https://img.shields.io/badge/Tiptap-000000?style=flat"/> <img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat&logo=d3&logoColor=white"/> <img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat&logo=tauri&logoColor=white"/> <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat&logo=storybook&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white"/></p>

<sub>AI 도구: Claude Code · Cursor Agent</sub>

## 경력

| 기간 | 회사 | 역할 |
|---|---|---|
| 2024.04 – 2026.05 | 도티오 (Binder) | Web Developer · 프론트엔드 담당 (개발팀 2인) |
| 2022.06 – 2024.03 | 파두 | Software Engineer · 프론트엔드 담당, 필요 시 백엔드 API 개발 |
| 2016.03 – 2022.02 | 국민대학교 | 컴퓨터공학부 학사 |

<details>
<summary><b>Before</b> · 학부 활동과 수상</summary>

- **볼트앤너트 현장실습** (2020.12 – 2021.02) React Native와 BLE로 블루투스 블라인드 리모컨 앱 MVP를 만들고, OpenCV로 아두이노 액추에이터를 제어하는 시제품을 개발했습니다.
- **Kobot 로봇 동아리** (2019.12 – 2021.01) 휴머노이드 로봇의 실시간 영상 처리와 모터·시리얼 통신 제어를 맡았습니다. 로봇융합페스티벌 금상(특허청), 임베디드 소프트웨어 경진대회 특선상.
- **캡스톤 디자인 HAI** (2021) 얼굴형 분석 헤어스타일 추천 웹 서비스의 React 프론트엔드와 배포. 캡스톤 경진대회 인기상.

</details>

## Contact

<a href="mailto:vaite714@gmail.com">vaite714@gmail.com</a>
