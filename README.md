# 🚀 react-redux-boilerplate
- 리액트 프로젝트를 쉽고 빠르게 시작하기 위한 밑바탕
- with [Create React App](https://github.com/facebook/create-react-app)

## 🔮 Dependencies
`react` `redux` `redux-saga` `axios` `styled-components`

dependency | version
--- | ---
react | ^17.0.1
react-dom | ^17.0.1
react-router-dom | ^5.2.0
react-redux | ^7.2.2
redux | ^4.0.5
redux-saga | ^1.1.3
redux-actions | ^2.6.5
axios | ^0.21.0
styled-components | ^5.2.1
prettier | ^2.1.2
redux-devtools-extension | ^2.13.8 

## 🤹‍♂️ Usage
```
git clone https://github.com/yj-oh/react-redux-boilerplate.git
yarn install
yarn start
```

## 🗂 Structure
```
🗂 project
|-- 📂 node_modules
|-- 📂 public
|-- 📂 src
|   |-- 📂 assets                        # assets
|   |-- 📂 components                    # redux에 연결되지 않는 단순 UI
|   |-- 📂 containers                    # redux에 연결되어 비즈니스 로직을 처리하는 presenter
|   |-- 📂 lib
|   |   |-- 📂 api                       # api 요청 모음
|   |   |   `-- 📋 api.js                # axios
|   |   `-- 📋 createRequestSaga.js      # saga 공통 함수 정의
|   |-- 📂 modules                       # reducer 모음
|   |   `-- 📋 index.js
|   |-- 📂 pages                         # 라우팅 페이지 모음
|   |-- 📂 utils                         # util 함수 모음
|   |-- 📋 App.js
|   |-- 📋 index.css
|   |-- 📋 index.js
|   `-- 📋 setupTests.js
|-- 📋 .gitignore
|-- 📋 .prettierrc
|-- 📋 package.json
|-- 📋 README.md
`-- 📋 yarn.lock
```

## 🧹 Prettier
#### .prettierrc
```prettier
{
  "arrowParens": "always",
  "bracketSpacing": true,
  "htmlWhitespaceSensitivity": "css",
  "insertPragma": false,
  "jsxBracketSameLine": false,
  "jsxSingleQuote": true,
  "printWidth": 80,
  "proseWrap": "preserve",
  "quoteProps": "as-needed",
  "semi": true,
  "singleQuote": true,
  "useTabs": true,
  "tabWidth": 4,
  "trailingComma": "all"
}
```
##### * References
- [Prettier docs](https://prettier.io/docs/en/options.html)
- [Prettier options 정리](https://github.com/yj-oh/til/blob/master/react/%5B20201110%5D_prettier_options.md)

## ⚙️ 기타 설정
- [Chrome 확장 프로그램 - Redux DevTools 설치](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=ko)
- [리덕스 개발자도구 적용하기](https://react.vlpt.us/redux/06-redux-devtools.html)
- [코드 스타일 통일을 위한 Prettier - IntelliJ 설정](https://github.com/yj-oh/til/blob/master/react/%5B20201104%5D_prettier_intellij_%EC%84%A4%EC%A0%95.md)

## 📜 License
[MIT License](https://github.com/yj-oh/react-redux-boilerplate/blob/master/LICENSE)
