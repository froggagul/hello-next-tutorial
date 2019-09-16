### 호진 feedback

* package install 시
    * package.json에 설치해야 할 module이 모두 적혀있기에, 시작할 때 `npm install`이나 `yarn install`로 설치해주면 됨
    * 이 때 package-lock.json은 실제 배포할 때 각 package의 상세 version을 관리하는 tool, 개발할 때는 ignore해도 됨

* .gitignore 추가하였음
    * .gitignore에 작성된 파일들은 git의 commit에서 제외됨, 보통 package 설치나 build 부산물들을 .gitignore에 추가함

* components/Header가 누락되서 추가했음

* .babelrc, TypeScript setup 과정이 포함된 repository를 첨부합니다, 이번주 과제 이후 참고하도록 하세요
    * https://github.com/distrue/mobx_react_toy/commits/master
    * 3개의 커밋이 있는데, 가장 최상위 version의 commit이 typescript + NextJS의 기본 setup임
