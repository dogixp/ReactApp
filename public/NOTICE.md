# React PORT 변경 방법

- 1) PORT=3001 npm start (* 명령어를 통해 구동 시 한 번만 적용)
- 2) package.json 파일에 scripts -> start  
- set PORT=3001 && react-scripts start (윈도우기준)
- export PORT=3001 && react-scripts start (맥 기준)

# React 프로젝트 생성 (node.js 설치 필수 )

- npx create-react-app {app 이름 소문자로만} [npx가 있는 경우]
- 
- npm install -g create-react-app [npx가 없는 경우]


# React Hook vs Class Component


# react-router-dom && react-router 설치 
- npm install --save react-router-dom
- npm install --save react-router


# React-bootstrap 설치

- npm install react-bootstrap bootstrap
- ex) 사용예제
- import 'bootstrap/dist/css/bootstrap.min.css';
- import Button from 'react-bootstrap/Button'; // 꼭 import를 해야한다
<Button as="input" type="button" value="Input" />

-- 참고사이트 :  https://react-bootstrap.github.io/getting-started/introduction/

