# Firebase 설치
--
firebase PC에서 환경설정
1. node.js 설치 (npm 설치) - 1번만
2. 터미널에서 npm install -g firebase-tools 실행 - 1번만
3. 터미널에서 firebase login - 1번만
4. 폴더 생성하고, vscode 에서 폴더 열고, vscode 터미널을 켠다.
5. firebase 콘솔(웹)에서 프로젝트 생성
6. 예) D:\test\ --> firebase init 실행
7. 설치가 완료되면 firebase serve / firebase deploy



## Firebase 설치 과정
### nodejs 설치
~~~
node -v
~~~
---
### firebase cli 설치
~~~
npm install -g firebase-tools
~~~
---
### firebase Login
~~~
firebase login
firebase list
~~~
---
### firebase 프로젝트 만들기
개발폴더에 firebase 프로젝트폴더 생성후 (ex: firebasememo)
해당폴더로 이동후
~~~
firebase init
-> database선택
-> database.rule.json
-> public 폴더 사용
-> index.html 사용
~~~
---
### firebase 실행
~~~
firebase serve
~~~
---
### firebase 배포
~~~
firebase deploy
~~~
---


## 우리가 배운 개발 환경
```
html5/css3/Javascript ES5/jQuery + Ajax + Firebase
```
---
## 실무에서 마주하게 될 개발 환경

```
가. PHP/ASPX/JSP 개발환경 - 회사마다 즐겨 사용하는 Framework에서 작업 (80%~)
  예) codeIgniter(php), Yii(php) ...
나. FrontEnd 개발 환경 - node.js(npm)
  예) Webpack Babel/React/React Reduce/Angular/Vue/Ionic/....
```
---
