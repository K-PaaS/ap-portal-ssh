# ap-portal-ssh
## 버전 정보
CF Container App SSH 접속을 제공하는 서비스

## Portal SSH
Portal SSH 란? CF Container App SSH 접속을 제공하는 서비스이다.

## 유의사항
개발 정보
- node v14.14.0 (v14.x.x)
- nodejs buildpack v1.7.34 (사용중인 node 의 버전에 맞는 빌드팩을 생성 해줘야 한다.)<br>
  (https://github.com/cloudfoundry/nodejs-buildpack/releases)
- ssh2 module 미 출시 버전<br>
  (https://github.com/mscdex/ssh2#readme)
- git clone<br>
  cd ap-portal-ssh<br>
  npm install --production (처음 clone 후 1회 실행)<br>
  npm install (개발 진행시 실행.)
- 최초 실행시 ssh2 모듈이 미 출시 버전 혹은 사용자 모듈 사용으로 오류가 발생 할 수 있다.<br>
  오류 무시하고 npm install 명령어를 실행시 오류 없이 정상 설치 완료 됨.