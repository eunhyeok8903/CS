## 클라우드란
* 물리적인 서버가 없어도 인터넷 접속을 통해서 외부의 다양한 자원을 사용할수 있게하는 컴퓨터 리소스(자원)의 형태

## 물리 서버와 클라우드 서버의 특징 및 차이점
* 소유자가 다르다는 가장큰 차이점이 있다.
* 물리서버의 경우 일반적으로 기업이 서버를 소유하고 있다.
* 반면에 클라우드 서버의 경우 AWS의 경우 Amazon이 리소스를 모두 관리하고 해당 리소스를 서비스형태로 만들고 제공하는것이다.

## 렌탈 서버의 3가지 형태
* 공용서버 : 1개의 물리 서버를 분할한 형태, 다른 사용자의 영향을 받을 수 있음
* 전용서버 : 1대의 물리 서버를 점유하는 형태, 다른 사용자의 영향을 받지 않으니 비쌈
* 가상전용서버 : 1대의 물리서버 위에 있는 가상서버를 점유

## 렌탈서버와 AWS의 차이
* AWS는 가상전용서버와 비슷한 형태를 갖고 있다. 하지만 AWS에서는 디스크 동적추가, Insatance type변경, 가상머신 생성 및 백업,복제 등 다양한 기능 제공

## Public Cloud와 Private Cloud의 차이
* 누구에게 서비스를 제공하느냐 차이가 있다.
* public은 불특정 다수에게 제공하며, private은 특정기업에 제공하는 형태입니다.
* 이외에도 public과 private을 조합한 하이브리드클라우드, 특정 업종의 기업들이 함께 운영하는 커뮤니티클라우드가 있다.

## AWS에서의 private cloud의 의미
* vpc를 이용하여 논리적으로 분리된 가상의 네트워크를 생성하는것, 기존 물리서버와(on-premise) 동일한 네트워크 구성이 가능하다.