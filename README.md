# vue-app-template

Vue UI 작업용 Template

## 개요

- 주 사용자 : 웹 퍼블리셔  
- UI 작업을 빠르게 시작하기 위한 기본 프로젝트 세팅 

## 디렉토리  
```
/
node_modules/     // node 모듈
public/           // public
package.json
package-lock.json
vue.config.js     // vue 설정
└ src             // 작업 폴더
  └ assets        // 리소스
    └ fonts
    └ images
    └ scss
  └ componets     // 컴포넌트
    └ ...
  └ layout        // include 레이아웃
  └ router        // 라우터 설정
  └ views         // 페이지
    └ ...
  └ App.vue
  └ main.js
```

## 설치
```
node, git 설치 후
> npm install
> npm run serve 서버 가동
> npm run build 빌드
```

## 메모

- `vue-cli3`
- `style scoped` + `scss` 전역 변수는 assets/scss/ 에서 정의해서 사용
- `jQuery`: 필요 시 index.html 전역 jquery cdn 추가
- `Header` + `router-view` + `Footer` 기본 뼈대