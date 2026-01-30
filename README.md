<!-- 헤더 인사 -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
      srcset="https://capsule-render.vercel.app/api?type=rect&color=0D1117&text=👋%20안녕하세요%20👋&fontSize=50&fontColor=FFFFFF" />
    <img
      src="https://capsule-render.vercel.app/api?type=rect&color=FFFFFF&text=👋%20안녕하세요%20👋&fontSize=50&fontColor=000000"
      alt="👋 안녕하세요 👋" />
  </picture>
</p>
<h3 align="center">﻿빠르게 변화하는 기술 환경 속에서 끊임없이 배우고 성장하는 웹개발자입니다.</h3>

---

### 👩‍💻 About Me

- 🎓 전공: **소프트웨어학과 전공** / 빅데이터분석 융합학과 부전공
- 🌱 최근 공부 중: **Spring Boot, JPA, React**  
- 💡 관심 분야: **JAVA 웹 서비스 개발**
- 📫 연락: **romeo309@naver.com**

---

### 🔧 Tech Stack

#### ⚙️ Tools
<div>
  <img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=Android&logoColor=white"/>
  <img src="https://img.shields.io/badge/eclipseide-2C2255?style=flat&logo=eclipseide&logoColor=white"/>
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white"/>
</div>

#### 👩‍💻 Language
<div>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</div>

#### 🧩 Backend
<div>
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
</div>

#### 🎨 Frontend
<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white" />
</div>

#### 🗄 Database & Data
<div>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
</div>

---

### 📌 Projects

#### 🛒 다시마켓 (중고거래 & 자체 굿즈 & 커뮤니티 플랫폼)
- 역할: **Frontend(관리자페이지, 채팅 UI/UX), Backend(채팅, 알림, 헤더 통합 검색, 관리자 회원/상품/배송 전체조회)**
- 기술: Spring Boot, MyBatis, Oracle, WebSocket, Thymeleaf
- 한 줄 요약: **실시간 채팅과 알림이 있는 중고거래 커뮤니티 웹 서비스**
- 문제해결
  : 채팅방 나가기 후 UI가 남는 문제 → 전역 상태/화면 상태가 유지됨 → 상태 초기화 + 채팅 목록 비동기 재조회 + 단방향 렌더링으로 정리 → UI/서버 데이터 정합성 확보

> 👉 레포 링크: [다시마켓 프로젝트 바로가기](https://github.com/Team-Nuguri/dashimarket)

#### 🎬📖 부기무비 (도서 & 영화 플랫폼)
- 역할: **Frontend(영화 페이지, 회원가입 UI/UX), Backend(영화CRUD, 회원가입/로그인)**
- 기술: Spring Boot, JPA, Oracle, Thymeleaf, css, javascript, Elasticsearch
- 한 줄 요약: **도서와 영화를 하나의 플랫폼으로 통합한 웹 서비스**
- 문제해결
  : 로그인 후 세션 ID가 유지되어 Session Fixation 위험 → 인증 성공 시 세션 재발급이 필요 → 로그인 성공 시 request.changeSessionId() 적용 + Security 표준 흐름으로 정비 → 세션 고정 공격 가능성 감소, 인증/세션 관리 일관성 확보

> 👉 레포 링크: [부기무비 프로젝트 바로가기](https://github.com/Team-Oceans/BOOGiMOVIE_ver2.0)

#### 🚨 안심이음 (실시간 안전 플랫폼)
- 역할: **Frontend(전체 UI/UX), Backend(국민행동요령 API 연동)**
- 기술: Firebase, android studio
- 한 줄 요약: **실시간 지역기반 안전 알림 모바일 서비스**
- 문제해결
  : Android 13+에서 알림이 “안 오는 것처럼” 보임 → 런타임 알림 권한/채널 설정 이슈 → POST_NOTIFICATIONS 권한 요청 + 상태별 처리 분리 + 채널 중요도 재정비 → OS 버전 변화에도 일관된 알림 노출

> 👉 레포 링크: [안심이음 프로젝트 바로가기](https://github.com/every3322-hash/ansim-ieum)

#### 🛍️ 온라인 쇼핑 저매출 지역 마케팅 전략(데이터 분석)
- 역할: **데이터 분석 및 시각화**
- 기술: Python, seabon, matplotlib
- 한 줄 요약: **미국 소비자들의 쇼핑 행동 패턴 중심으로 저매출 지역 데이터 분석 후 마케팅 전략 제안**
- 문제해결
  : 히트맵으로는 색상·리뷰(범주형) 인사이트가 약함 → 범주형 분포 비교에 부적합 → 색상 재그룹화 + 카테고리 4→7 세분화 후 바이올린플롯 분석 → 저매출 지역 타깃 마케팅 인사이트 도출

> 👉 레포 링크: [온라인 쇼핑 마케팅 전략 프로젝트 바로가기](https://github.com/jr-2-team/shopping-data-analysis)
---

<!-- ### 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&theme=default" alt="GitHub stats" />
</p> 

--- -->

### ✨ More About Me

- 팀 프로젝트에서 **소통**과 **협업**을 중요하게 생각해요  
- 문제 생기면 `원인 → 재현 → 로그/코드 분석 → 해결` 순서로 정리하는 습관을 들이는 중입니다 😎


<!--
**every3322-hash/every3322-hash** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
