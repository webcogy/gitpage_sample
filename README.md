# git page 배포 테스트 샘플

- yarn 이나 npm 한가지만 써서 쭉 진행해야 합니다.

```
// 설치
npm install gh-pages --save-dev
yarn add gh-pages --save-dev
```




``` package.json ```
```json
"homepage": "http://webcogy.github.io/testapp
...

"scripts": {
  //...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

```


```
// 배포 실행
npm run deploy
yarn run deploy
```

github 상단의 Settings -> Options -> GitHub Pages 에서 확인

※ 배포 후 깃페이지에 적용되기까지 시간이 좀 걸리므로 참고

#### 깃페이지주소 https://webcogy.github.io/testapp/


#### 참고 https://velog.io/@byjihye/react-github-pages
