# 모던 리액트 딥다이브 스터디 📚

## 참여자 🧑🏻‍💻
|   ![](https://github.com/sangbooom.png?size=100)    | ![](https://github.com/dongwonnn.png?size=100)  | ![](https://github.com/yujiseok.png?size=100) | 
|:------------------------------------------------:|:--------------------------------------------:|:---------------------------------------------:|
|         [박상범](https://github.com/sangbooom)         |       [김동원](https://github.com/dongwonnn)       |      [유지석](https://github.com/yujiseok)       |   

## 스터디 진행 방식 🔖
- 매주 수요일 6시까지 책을 읽고 정리한 내용을 해당 저장소에 올립니다.
- 수요일 6시까지 정리한 내용을 올리지 못한 사람은 벌금 5천원이 부여됩니다.
- 룰렛을 통해 진행자를 선정하고 정리한 내용을 기반으로 발표를 진행합니다.
- 발표는 자유방식이고 건강한 토론 방식을 지향합니다.



## 일정 
| 회차 | 일시                | 목차                | 참여자               | 발표자           | 비고                       |
| ---- |-------------------|-------------------|-------------------|---------------|--------------------------|
| 0    | 1월 17일 (수) 18:00  | 1장까지 (~114p)     | All                  |               |스터디 룰, 일정 정하기|
| 1    | 1월 24일 (수) 18:00  |        |                  |               ||




## 목차
<details><summary>펼치기 / 접기</summary> 

  
01장: 리액트 개발을 위해 꼭 알아야 할 자바스크립트   
1.1 자바스크립트의 동등 비교   
__1.1.1 자바스크립트의 데이터 타입   
__1.1.2 값을 저장하는 방식의 차이   
__1.1.3 자바스크립트의 또 다른 비교 공식, Object.is   
__1.1.4 리액트에서의 동등 비교   
__1.1.5 정리   
1.2 함수   
__1.2.1 함수란 무엇인가?   
__1.2.2 함수를 정의하는 4가지 방법   
__1.2.3 다양한 함수 살펴보기   
__1.2.4 함수를 만들 때 주의해야 할 사항   
__1.2.5 정리   
1.3 클래스   
__1.3.1 클래스란 무엇인가?   
__1.3.2 클래스와 함수의 관계   
__1.3.3 정리   
1.4 클로저   
__1.4.1 클로저의 정의   
__1.4.2 변수의 유효 범위, 스코프   
__1.4.3 클로저의 활용   
__1.4.4 주의할 점   
__1.4.5 정리   
1.5 이벤트 루프와 비동기 통신의 이해   
__1.5.1 싱글 스레드 자바스크립트   
__1.5.2 이벤트 루프란?   
__1.5.3 태스크 큐와 마이크로 태스크 큐   
__1.5.4 정리   
1.6 리액트에서 자주 사용하는 자바스크립트 문법   
__1.6.1 구조 분해 할당   
__1.6.2 전개 구문   
__1.6.3 객체 초기자   
__1.6.4 Array 프로토타입의 메서드: map, filter, reduce, forEach   
__1.6.5 삼항 조건 연산자   
__1.6.6 정리   
1.7 선택이 아닌 필수, 타입스크립트   
__1.7.1 타입스크립트란?   
__1.7.2 리액트 코드를 효과적으로 작성하기 위한 타입스크립트 활용법   
__1.7.3 타입스크립트 전환 가이드   
__1.7.4 정리   
    
▣ 02장: 리액트 핵심 요소 깊게 살펴보기   
2.1 JSX란?   
__2.1.1 JSX의 정의   
__2.1.2 JSX 예제   
__2.1.3 JSX는 어떻게 자바스크립트에서 변환될까?   
__2.1.4 정리   
2.2 가상 DOM과 리액트 파이버   
__2.2.1 DOM과 브라우저 렌더링 과정   
__2.2.2 가상 DOM의 탄생 배경   
__2.2.3 가상 DOM을 위한 아키텍처, 리액트 파이버   
__2.2.4 파이버와 가상 DOM   
__2.2.5 정리   
2.3 클래스형 컴포넌트와 함수형 컴포넌트   
__2.3.1 클래스형 컴포넌트   
__2.3.2 함수형 컴포넌트   
__2.3.3 함수형 컴포넌트 vs. 클래스형 컴포넌트   
__2.3.4 정리   
2.4 렌더링은 어떻게 일어나는가?   
__2.4.1 리액트의 렌더링이란?   
__2.4.2 리액트의 렌더링이 일어나는 이유   
__2.4.3 리액트의 렌더링 프로세스   
__2.4.4 렌더와 커밋   
__2.4.5 일반적인 렌더링 시나리오 살펴보기   
__2.4.6 정리   
2.5 컴포넌트와 함수의 무거운 연산을 기억해 두는 메모이제이션   
__2.5.1 주장 1: 섣부른 최적화는 독이다, 꼭 필요한 곳에만 메모이제이션을 추가하자   
__2.5.2 주장 2: 렌더링 과정의 비용은 비싸다, 모조리 메모이제이션해 버리자   
__2.5.3 결론 및 정리   
    
▣ 03장: 리액트 훅 깊게 살펴보기   
3.1 리액트의 모든 훅 파헤치기   
__3.1.1 useState   
__3.1.2 useEffect   
__3.1.3 useMemo   
__3.1.4 useCallback   
__3.1.5 useRef   
__3.1.6 useContext   
__3.1.7 useReducer   
__3.1.8 useImperativeHandle   
__3.1.9 useLayoutEffect   
__3.1.10 useDebugValue   
__3.1.11 훅의 규칙   
__3.1.12 정리   
3.2 사용자 정의 훅과 고차 컴포넌트 중 무엇을 써야 할까?   
__3.2.1 사용자 정의 훅   
__3.2.2 고차 컴포넌트   
__3.2.3 사용자 정의 훅과 고차 컴포넌트 중 무엇을 써야 할까?   
__3.2.4 정리   
    
▣ 04장: 서버 사이드 렌더링   
4.1 서버 사이드 렌더링이란?   
__4.1.1 싱글 페이지 애플리케이션의 세상   
__4.1.2 서버 사이드 렌더링이란?   
__4.1.3 SPA와 SSR을 모두 알아야 하는 이유   
__4.1.4 정리   
4.2 서버 사이드 렌더링을 위한 리액트 API 살펴보기   
__4.2.1 renderToString   
__4.2.2 renderToStaticMarkup   
__4.2.3 renderToNodeStream   
__4.2.4 renderToStaticNodeStream   
__4.2.5 hydrate   
__4.2.6 서버 사이드 렌더링 예제 프로젝트   
__4.2.7 정리   
4.3 Next.js 톺아보기   
__4.3.1 Next.js란?   
__4.3.2 Next.js 시작하기   
__4.3.3 Data Fetching   
__4.3.4 스타일 적용하기   
__4.3.5 _app.tsx 응용하기   
__4.3.6 next.config.js 살펴보기   
__4.3.7 정리   
    
▣ 05장: 리액트와 상태 관리 라이브러리   
5.1 상태 관리는 왜 필요한가?   
__5.1.1 리액트 상태 관리의 역사   
__5.1.2 정리   
5.2 리액트 훅으로 시작하는 상태 관리   
__5.2.1 가장 기본적인 방법: useState와 useReducer   
__5.2.2 지역 상태의 한계를 벗어나보자: useState의 상태를 바깥으로 분리하기   
__5.2.3 useState와 Context를 동시에 사용해 보기   
__5.2.4 상태 관리 라이브러리 Recoil, Jotai, Zustand 살펴보기   
__5.2.5 정리   
    
▣ 06장: 리액트 개발 도구로 디버깅하기   
6.1 리액트 개발 도구란?   
6.2 리액트 개발 도구 설치   
6.3 리액트 개발 도구 활용하기   
__6.3.1 컴포넌트   
__6.3.2 프로파일러   
6.4 정리   
    
▣ 07장: 크롬 개발자 도구를 활용한 애플리케이션 분석   
7.1 크롬 개발자 도구란?   
7.2 요소 탭   
__7.2.1 요소 화면   
__7.2.2 요소 정보   
7.3 소스 탭   
7.4 네트워크 탭   
7.5 메모리 탭   
__7.5.1 자바스크립트 인스턴스 VM 선택   
__7.5.2 힙 스냅샷   
__7.5.3 타임라인 할당 계측   
__7.5.4 할당 샘플링   
7.6 Next.js 환경 디버깅하기   
__7.6.1 Next.js 프로젝트를 디버그 모드로 실행하기   
__7.6.2 Next.js 서버에 트래픽 유입시키기   
__7.6.3 Next.js의 메모리 누수 지점 확인하기   
7.7 정리   
    
▣ 08장: 좋은 리액트 코드 작성을 위한 환경 구축하기   
8.1 ESLint를 활용한 정적 코드 분석   
__8.1.1 ESLint 살펴보기   
__8.1.2 eslint-plugin과 eslint-config   
__8.1.3 나만의 ESLint 규칙 만들기   
__8.1.4 주의할 점   
__8.1.5 정리   
8.2 리액트 팀이 권장하는 리액트 테스트 라이브러리   
__8.2.1 React Testing Library란?   
__8.2.2 자바스크립트 테스트의 기초   
__8.2.3 리액트 컴포넌트 테스트 코드 작성하기   
__8.2.4 사용자 정의 훅 테스트하기   
__8.2.5 테스트를 작성하기에 앞서 고려해야 할 점   
__8.2.6 그 밖에 해볼 만한 여러 가지 테스트   
__8.2.7 정리   
    
▣ 09장: 모던 리액트 개발 도구로 개발 및 배포 환경 구축하기   
9.1 Next.js로 리액트 개발 환경 구축하기   
__9.1.1 create-next-app 없이 하나씩 구축하기   
__9.1.2 tsconfig.json 작성하기   
__9.1.3 next.config.js 작성하기   
__9.1.4 ESLint와 Prettier 설정하기   
__9.1.5 스타일 설정하기   
__9.1.6 애플리케이션 코드 작성   
__9.1.7 정리   
9.2 깃허브 100% 활용하기   
__9.2.1 깃허브 액션으로 CI 환경 구축하기   
__9.2.2 직접 작성하지 않고 유용한 액션과 깃허브 앱 가져다 쓰기   
__9.2.3 깃허브 Dependabot으로 보안 취약점 해결하기   
__9.2.4 정리   
9.3 리액트 애플리케이션 배포하기   
__9.3.1 Netlify   
__9.3.2 Vercel   
__9.3.3 DigitalOcean   
__9.3.4 정리   
9.4 리액트 애플리케이션 도커라이즈하기   
__9.4.1 리액트 앱을 도커라이즈하는 방법   
__9.4.2 도커로 만든 이미지 배포하기   
__9.4.3 정리   
    
▣ 10장: 리액트 17과 18의 변경 사항 살펴보기   
10.1 리액트 17 버전 살펴보기   
__10.1.1 리액트의 점진적인 업그레이드   
__10.1.2 이벤트 위임 방식의 변경   
__10.1.3 import React from ‘reac’가 더 이상 필요 없다: 새로운 JSX transform   
__10.1.4 그 밖의 주요 변경 사항   
__10.1.5 정리   
10.2 리액트 18 버전 살펴보기   
__10.2.1 새로 추가된 훅 살펴보기   
__10.2.2 react-dom/client   
__10.2.3 react-dom/server   
__10.2.4 자동 배치(Automatic Batching)   
__10.2.5 더욱 엄격해진 엄격 모드   
__10.2.6 Suspense 기능 강화   
__10.2.7 인터넷 익스플로러 지원 중단에 따른 추가 폴리필 필요   
__10.2.8 그 밖에 알아두면 좋은 변경사항   
__10.2.9 정리   
    
▣ 11장: Next.js 13과 리액트 18   
11.1 app 디렉터리의 등장   
__11.1.1 라우팅   
11.2 리액트 서버 컴포넌트   
__11.2.1 기존 리액트 컴포넌트와 서버 사이드 렌더링의 한계   
__11.2.2 서버 컴포넌트란?   
__11.2.3 서버 사이드 렌더링과 서버 컴포넌트의 차이   
__11.2.4 서버 컴포넌트는 어떻게 작동하는가?   
11.3 Next.js에서의 리액트 서버 컴포넌트   
__11.3.1 새로운 fetch 도입과 getServerSideProps, getStaticProps, getInitial Props의 삭제   
__11.3.2 정적 렌더링과 동적 렌더링   
__11.3.3 캐시와 mutating, 그리고 revalidating   
__11.3.4 스트리밍을 활용한 점진적인 페이지 불러오기   
11.4 웹팩의 대항마, 터보팩의 등장(beta)   
11.5 서버 액션(alpha)   
__11.5.1 form의 action   
__11.5.2 input의 submit과 image의 formAction   
__11.5.3 startTransition과의 연동   
__11.5.4 server mutation이 없는 작업   
__11.5.5 서버 액션 사용 시 주의할 점   
11.6 그 밖의 변화   
11.7 Next.js 13 코드 맛보기   
__11.7.1 getServerSideProps와 비슷한 서버 사이드 렌더링 구현해 보기   
__11.7.2 getStaticProps와 비슷한 정적인 페이지 렌더링 구현해 보기   
__11.7.3 로딩, 스트리밍, 서스펜스   
11.8 정리 및 주의사항   
    
▣ 12장: 모든 웹 개발자가 관심을 가져야 할 핵심 웹 지표   
12.1 웹사이트와 성능   
12.2 핵심 웹 지표란?   
12.3 최대 콘텐츠풀 페인트(LCP)   
__12.3.1 정의   
__12.3.2 의미   
__12.3.3 예제   
__12.3.4 기준 점수   
__12.3.5 개선 방안   
12.4 최초 입력 지연(FID)   
__12.4.1 정의   
__12.4.2 의미   
__12.4.3 예제   
__12.4.4 기준 점수   
__12.4.5 개선 방안   
12.5 누적 레이아웃 이동(CLS)   
__12.5.1 정의   
__12.5.2 의미   
__12.5.3 예제   
__12.5.4 기준 점수   
__12.5.5 개선 방안   
__12.5.6 핵심 웹 지표는 아니지만 성능 확인에 중요한 지표들   
12.6 정리   
    
▣ 13장: 웹페이지의 성능을 측정하는 다양한 방법   
13.1 애플리케이션에서 확인하기   
__13.1.1 create-react-app   
__13.1.2 create-next-app   
13.2 구글 라이트하우스   
__13.2.1 구글 라이트하우스 - 탐색 모드   
__13.2.2 구글 라이트하우스 - 기간 모드   
__13.2.3 구글 라이트하우스 – 스냅샷   
13.3 WebPageTest   
__13.3.1 Performance Summary   
__13.3.2 Opportunities & Experiments   
__13.3.3 Filmstrip   
__13.3.4 Details   
__13.3.5 Web Vitals   
__13.3.6 Optimizations   
__13.3.7 Content   
__13.3.8 Domains   
__13.3.9 Console Log   
__13.3.10 Detected Technologies   
__13.3.11 Main-thread Processing   
__13.3.12 Lighthouse Report   
__13.3.13 기타   
13.4 크롬 개발자 도구   
__13.4.1 성능 통계   
__13.4.2 성능   
13.5 정리   
    
▣ 14장: 웹사이트 보안을 위한 리액트와 웹페이지 보안 이슈   
14.1 리액트에서 발생하는 크로스 사이트 스크립팅(XSS)   
__14.1.1 dangerouslySetInnerHTML prop   
__14.1.2 useRef를 활용한 직접 삽입   
__14.1.3 리액트에서 XSS 문제를 피하는 방법   
14.2 getServerSideProps와 서버 컴포넌트를 주의하자   
14.3 태그의 값에 적절한 제한을 둬야 한다   
14.4 HTTP 보안 헤더 설정하기   
__14.4.1 Strict-Transport-Security   
__14.4.2 X-XSS-Protection   
__14.4.3 X-Frame-Options   
__14.4.4 Permissions-Policy   
__14.4.5 X-Content-Type-Options   
__14.4.6 Referrer-Policy   
__14.4.7 Content-Security-Policy   
__14.4.8 보안 헤더 설정하기   
__14.4.9 보안 헤더 확인하기   
14.5 취약점이 있는 패키지의 사용을 피하자   
14.6 OWASP Top 10   
14.7 정리   
    
▣ 15장: 마치며   
15.1 리액트 프로젝트를 시작할 때 고려해야 할 사항   
__15.1.1 유지보수 중인 서비스라면 리액트 버전을 최소 16.8.6에서 최대 17.0.2로 올려두자   
__15.1.2 인터넷 익스플로러 11 지원을 목표한다면 각별히 더 주의를 기한다   
__15.1.3 서버 사이드 렌더링 애플리케이션을 우선적으로 고려한다   
__15.1.4 상태 관리 라이브러리는 꼭 필요할 때만 사용한다   
__15.1.5 리액트 의존성 라이브러리 설치를 조심한다   
15.2 언젠가 사라질 수도 있는 리액트   
__15.2.1 리액트는 그래서 정말 완벽한 라이브러리인가?   
__15.2.2 오픈소스 생태계의 명과 암   
__15.2.3 제이쿼리, AngularJS, 리액트, 그리고 다음은 무엇인가?   
__15.2.4 웹 개발자로서 가져야 할 유연한 자세   





</details>
