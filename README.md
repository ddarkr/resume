👤 정도현 (aka. `도다`)
  - 생년월일: 2003.11.03.
  - E-Mail: [me@doda.dev](mailto:me@doda.dev)
  - GitHub: <https://github.com/ddarkr>
  - Blog: <https://doda.dev>

## 🔖 philosophy

- **사용자의 경험을 생각하는 개발**
  - 서비스를 사용하는 사용자의 기준에서 생각해보고 개선점이 있을까 찾아봅니다. 사용자의 사소한 경험까지도 신경 쓰고 싶습니다.
  - [애자일 소프트웨어 개발 선언](https://agilemanifesto.org/iso/ko/manifesto.html)의 내용을 좋아하며, 실천하려 노력합니다.
- **목적에 맞는 개발**
  - 이상적인 기술 스택만 추구하는 것을 좋아하지 않습니다. 현실적인 여건에 맞는 기술 스택과 구현을 선호합니다.
- **다양한 기술을 빠르게**
  - 새로운 기술이나 서비스, 개발 방법론을 관심 있게 찾아보며 프로젝트에 적용을 생각해봅니다.

## 🏒 skills

> ✅ 프로젝트에 사용해 본 것들만 기재했습니다.

> 🧐 **강조된** 기술은 현재에도 많이 사용하는 기술입니다.

- JavaScript
  - **TypeScript**
  - **React**
  - **Next.js**
  - Express
  - **Nest.js**
- PHP
  - **Laravel**
- Database
  - MySQL (**MariaDB**)
- DevOps
  - **GitHub**, GitLab
  - **Vercel**
  - **GitHub Actions**
  - **ESLint, Prettier**

## 👨‍💻 experiences

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/mywallets_v1.png" width="600px" />

**마이월렛**
> Apple Wallet에 '패스'를 간단하게 추가할 수 있도록 도와주는 서비스입니다.
- [🌐 website](https://mywallets.xyz)
- 📅 기간: 2020.12 - 현재
- 간단한 MVVM 패턴을 적용하여 비즈니스 로직과 뷰를 분리하여 추후의 유지 보수가 간편하게 설계되었습니다.
- Fuzzy 검색을 이용할 수 있게 해주는 fuse.js 라이브러리를 사용하여 간단한 멤버십 검색을 구현하였습니다.
- [본인이 쓴 프론트엔드 개발기](https://velog.io/@team_croco/mywallets-frontend-story)
- 🛠 skills: `React`, `Next.js`, `TypeScript`, `Emotion (styled)` 

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/doda-dev.png" width="600px" />

**개인 블로그**
> 개인 블로그로, Notion Database를 기반으로 글 데이터를 받아 표시하는 블로그입니다. Notion에서 모든 글 관리가 가능하도록 한 것이 특징입니다.
- [🌐 website](https://doda.dev)
- 📅 기간: 2020.10 - 현재
- Next.js의 SSG, ISR을 이용하여 Notion의 글 데이터가 변경되었을 경우 바로 렌더링해줄 수 있도록 구현하였습니다.
- 메인의 파도 애니메이션은 CSS와 SVG만을 이용하여 제작하였으며, 다크 모드에서는 다른 SVG를 사용하도록 대응하였습니다.
- 모바일 글 본문에 있는 목차(TOC)가 필요 없으므로, Dynamic Import를 활용하여 필요한 기기 넓이에서만 불러오도록 구현하였습니다.
- Next.js의 Image 컴포넌트를 이용하여 이미지가 최적화되어 표시되게 구현하였습니다.
- 🛠 skills: `React`, `Next.js`, `TypeScript`, `Emotion (styled)` 

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/coronas.info.png" width="600px" />

**코로나인포**
> 국내 코로나-19 초기에 제작한 정보를 제공하는 서비스입니다. 마스크 재고 현황이나 확진자의 이동 동선등을 제공하였습니다.
- 📅 기간: 2020.02 - 2020.04
- 데스크탑 레이아웃과 모바일 레이아웃이 달라, 각 상황에 맞는 레이아웃 컴포넌트를 Dynamic Import로 불러와 맞는 상황에만 번들 파일을 가져올 수 있도록 하였습니다.
- 네이버 지도 API를 이용하여 Polygon과 Line을 사용해, 확진자들의 동선을 제공하였습니다.
- SVG 기반의 확진자 지도를 간단하게 제작해, 마우스를 hover 하면 확진자가 표시되게 구현하였습니다.
- 공적 마스크 공공 API를 이용하여 공적 마스크 재고 현황을 제공하였습니다.
- [본인이 작성한 프론트엔드 개발기](https://velog.io/@team_croco/making-coronas-info-frontend)
- 🛠 skills: `React`, `Next.js`, `TypeScript`, `Scss`, `Emotion (styled)`

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/ddark.kr.png" width="600px" />

**개인 홈페이지**
> React + Next.js 연습용으로 간단하게 만든 자기 소개 페이지입니다. 
- 📅 기간: 2019.12 - 2021.2
- Recoil을 사용하여 간단한 다크 모드를 구현하였습니다.
- 용량이 큰 기술 카드 영역을 Dynamic Import를 사용하여 별개의 번들 파일로 분리하여, 빠른 페이지 로딩이 가능하도록 구현하였습니다.
- 다크 모드에서는 각 기술들의 메인 컬러를 자동으로 어둡게 만들어주도록 제작하였습니다.
- 🛠 skills: `React`, `Next.js`, `TypeScript`, `Emotion (styled)`, `Recoil`

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/splitzConsole.png" width="600px" />

**Splitz Console (스플릿즈 콘솔)**
> 클라우드 서비스들의 사용자 패널 서비스입니다. 외주 형태로 개발하였습니다.
- 📅 기간: 2019.08 - 2020.02
- JWT 기반으로 사용자 인증을 하였으며, Nuxt.js + Express를 사용하여 세션 기반으로 사용자 인증을 하는 API를 구현하였습니다. Vuex에서 사용자 데이터를 관리하였습니다.
- 🛠 skills: `Nuxt.js`, `Vue.js`, `Vuex`, `Pug`, `Scss`, `PHP`, `Laravel`, `Express`

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/muzip.png" width="600px" />

**뮤집**
> 음악 가사와 노래방 번호를 제공해주는 음악 정보 사이트입니다. 가입형 위키위키 방식을 추구하며, 간단한 버전 시스템을 도입하여 수정 기록을 관리할 수 있도록 하였습니다.
- [🌐 website](https://muzip.xyz)
- 📅 기간: 2018 - 현재
- JWT 기반의 인증을 도입하여, Vuex Store에서 관리하도록 구현하였습니다. 또한 JWT를 localStorage에 저장하여 로그인 세션이 유지되도록 하였습니다.
- Algolia 기반의 검색을 제공하며, 백엔드 서버에서 데이터가 변경될 때마다 Algolia의 내용이 업데이트되도록 구현하였습니다.
- 컨텐츠 데이터를 제공하는 비공개 RESTful API의 인증 토큰을 구현하여 API의 보안을 신경 써서 구현하였습니다.
- 🛠 skills: `Vue.js`, `Vuex`, `Pug`, `Scss`, `PHP`, `Laravel`

----

<img src="https://raw.githubusercontent.com/ddarkr/RESUME/master/assets/images/cielMusic_v1.png" width="600px" />

**Ciel Music**
> 유튜브 영상 기반의 음악 스트리밍 서비스입니다. 여러 서비스의 API를 한 곳에 모아 편하게 음악을 청취할 수 있도록 기획한 서비스입니다.
- 📅 기간: 2017.03 - 2018.04
- ajax + history.pushState를 이용한 음악이 끊기지 않게 서비스를 제공하였습니다.
- 다음 접속에도 동일한 재생목록을 표시하기 위하여 재생목록이 변경될 때마다 JSON 기반으로 localStorage에 저장하도록 구현하였습니다.
- 재생목록을 서버에 JSON 기반으로 저장하는 기능을 구현하였습니다. 또한 저장된 재생목록을 언제든지 교체할 수 있는 페이지를 제작하였습니다.
- last.fm API를 통해 곡 검색을 구현하였습니다. 받아온 데이터를 걸러 음악 재생에 활용하도록 하였습니다.
- 🛠 skills: `Bootstrap 3`, `jQuery`, `CodeIgniter`

## 📚 education

- 인창고등학교 (2019.03 - 2022.01) (재학중)

