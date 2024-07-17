### 레이아웃과 템플릿의 차이
* 페이지가 넘나들때 리렌더링이 안되게 하고 싶으면 레이아웃
* 페이지가 넘나들때 리렌더링이 되게 하고 싶으면 템플릿
=> 레이아웃과 템플릿은 공존하면 안됨

### next 에서는 a 태그 대신에 link 태그 사용
* 링크에 특수한 기능이 있어서 a 태그를 대체해서 사용
* a 태그를 쓰면 페이지가 새로 고침되면서 넘어간다.
* 리액트나 넥스트에서는 페이지가 새로 고침되는 행동을 하면 안됨

### default.tsx
* 페러렐 라우트가 보통 필요 없을 때 또는 페러렐 라우트에 대한 기본 값
// 주소가 localhost:3000 일 때는 children -> page.tsx, modal -> @modal/default.tsx
// 주소가 localhost:3000/i/flow/login 일 때는 children -> i/flow/login/page.tsx, modal -> @modal/i/flow/login/page.tsx