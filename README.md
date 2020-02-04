# 딥러닝 인 더 브라우저(Deep learning in the browser)

<p align="center">
<img src="cover.jpg?raw=true" width="33%"/>
</p>

제이펍에서 출판한 <딥러닝 인 더 브라우저(2020)>의 공식 저장소 입니다. 책 내 소스 코드를 확인할 수 있습니다.

## 책 소개
이 책은 딥러닝과 웹 개발의 교차점에 있습니다. 두 기술 모두 성숙 단계에 접어들었고, 이들이 만난다면 누구도 상상하지 못한 환상적인 애플리케이션을 만들 수 있습니다.

이 책은 기본적인 웹 프로그래밍과 더불어 WebGL 등을 사용한 자바스크립트 딥러닝 프레임워크 사용법을 설명합니다. 브라우저와 딥러닝의 만남은 아직 걸음마 수준에 불과하지만, 하루가 다르게 눈부시게 발전하고 있습니다. 지금이야말로 시작하기 가장 좋을 때입니다. 이 책과 함께 놀라운 딥러닝의 세계를 느껴보기를 바랍니다. 자, 새로운 여행을 떠나 볼까요?

### 목차
* [Chapter 1: 딥러닝 소개 - 활성화 함수 그래프](/chapter1)
* [Chapter 3: 자바스크립트 딥러닝 프레임워크](/chapter3)
* [chapter 5: WebGL을 이용한 GPU 가속화](/chapter5)
* [chapter 6: 웹 브라우저에서의 데이터 추출](/chapter6)
* [chapter 7: 고급 데이터 조작을 위한 레시피](/chapter7)
* [chapter 8:  TensorFlow.js 애플리케이션 개발](/chapter8)

### 데모
* [가위바위보 게임](https://reiinakano.com/tfjs-rock-paper-scissors/)
* [텍스트 생성 모델](https://reiinakano.com/tfjs-lstm-text-generation/)
  
### 설치 방법

git 명령어로 저장소를 다운받은 후 서브모듈을 업데이트 합니다.

```sh
$ git clone git@github.com:backstopmedia/deep-learning-browser.git
$ cd deep-learning-browser
$ git submodule update --init --recursive
```

웹 서버로 각 챕터의 디렉터리를 실행할 수 있습니다. http-server를 전역으로 설치한 다음 해당 챕터를 실행합니다.

```sh
$ npm install http-server -g
$ http-server chapter6 --cors -p 8081
```

[localhost:8081](http://localhost:8081)을 열어 해당 하위 디렉터리를 이동해 확인할 수 있습니다.

## 라이센스 

본 저장소는 원작 <Deep learning in the browser>의 [공식 깃허브 저장소](https://github.com/backstopmedia/deep-learning-browser)에 따라 MIT 라이센스를 준수합니다. [/LICENSE.txt](/LICENSE.txt) 에서 상세한 내용을 확인할 수 있습니다. 단, `/lib` 와 `/data`는 디렉터리는 예외입니다.