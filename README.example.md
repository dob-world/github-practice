# dob heartbeat frontend
본 프로젝트는 dobstudio에 기존 기술을 누구나 쉽게 사용 할 수 있도록 어플리케이션으로 구현한 프로젝트입니다. 
또한 계속해서 개발 될 프로젝트들을 통합하는 역할도 맡습니다.

상세한 내용은 [dob-heartbeat-frontend document](#)에서 확인 할 수 있습니다.

# How to Start
- 본 프로젝트는 Node v14.18.0, NPM v6.14.15 버전에서 개발되었습니다.

**Clone Repo**

```
git clone https://github.com/dob-world/dob-heartbeat-frontend
```
**Node Package 설치**

Clone 된 프로젝트로 이동하여 아래의 명령을 실행합니다. 

node_modules가 생성되고 필요한 패키지를 설치합니다.
```
npm install
```

**Dev Server 실행**

개발 서버를 실행 할 수 있습니다. 함께 실행되는 Electron App을 사용하거나, 웹 브라우저의 `localhost:3000`으로 접속하여 구현된 내용을 확인 할 수 있습니다.
```
npm start
```
**Deploy**

(테스트 필요)
Webpack을 통해 작성된 javascript 파일과 패키지를 묶어 빌드합니다. 그리고 Electron으로 다시 빌드하여 실행 할 수 있는 어플리케이션으로 재구성합니다. 
```
npm build
```

빌드된 어플리케이션이 참조 할 수 있는 웹서버를 별도로 실행해야합니다. 아래의 명령을 통해 웹서버를 실행하고, 해당 주소를 어플리케이션이 참조합니다.

이에 관한 설정은 추후 추가 예정
```
npx serve -s build
```


# LICENSE
\-

# To do
- [ ] 개발, 배포 환경 API 구분 ( use Postman Mock Server )
- [ ] 테스트 케이스 작성
- [ ] 배포 자동화 환경 구성


# FAQ
프로젝트에 대해 궁금한 부분이나 지적 할 부분이 있다면 Isseu 탭에 작성해주세요!
