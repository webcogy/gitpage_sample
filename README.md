# git page 배포 테스트 샘플

```
// 설치
npm install gh-pages --save-dev
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
```

github 상단의 Settings -> Options -> GitHub Pages 에서 확인


#### 깃페이지주소 https://webcogy.github.io/testapp/


#### 참고 https://velog.io/@byjihye/react-github-pages
