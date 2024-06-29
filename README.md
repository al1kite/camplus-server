# CAMPLUS 프로젝트  
## 개발 기간
#### 2022.12.28 ~ 2023.02.03
[Camsplus 사이트 바로가기](http://camsplus.site)
<br>  

## 팀원
* 고현림 - 프론트엔드
* 안은진 - 프론트엔드
* 정다연 - 백엔드
* 하민수 - 백엔드
* 이진혁 - 멘토
<br>

## 프로젝트 주제 선정 배경
* 대학 생활을 하면서 다양한 필요용품이 필요할 때가 있다. 하지만 이를 대처할만한 어플이 없다는 점에서 기획
* 기존 대학 생활 대표 어플리케이션(에브리타임)의 단점을 보안하여 필요 용품만을 대여하면서 오로지 필요 용품이 있을 때 유용하게 사용할 수 있는 맞춤형 서비스를 제공
<br>

## 프로젝트 소개
#### 회원가입 및 로그인  
<img width="412" alt="camplus-login" src="https://user-images.githubusercontent.com/105342203/220269545-d82819f7-e343-42ef-a8c1-95b36bf60a86.png"> <img width="412" alt="camplus-register" src="https://user-images.githubusercontent.com/105342203/220272479-8b828794-1b3d-4aed-ac16-527c8f0583c9.png">  

#### 게시글 및 댓글
<img width="412" alt="게시물" src="https://user-images.githubusercontent.com/105342203/220275099-c6f59fb4-7fbe-4bf4-b4ce-872241bda4d2.png"> <img width="412" alt="상세게시물" src="https://user-images.githubusercontent.com/105342203/220275365-c87b0560-b01d-4bde-9986-caa228415ee3.png">  

#### 게시글 작성 및 마이페이지
<img width="412" alt="작성" src="https://user-images.githubusercontent.com/105342203/220276459-bb8dbdf6-bae3-4808-9aa1-c43ff9c0c64f.png"> <img width="412" alt="마이페이지" src="https://user-images.githubusercontent.com/105342203/220275933-3131c36a-f48c-431c-a4ce-daec0839334f.png">    
<br>  

## CAMPLUS 홈페이지 이용법
* 회원가입 후 회원가입 시 입력한 학교 이메일로 이동하여 이메일 인증 완료하기
* 로그인해서 자유롭게 게시글, 댓글 작성하기   
<br>

## 핵심 기능
### 학교 이메일 인증
* 학교 생활 커뮤니티 홈페이지에 걸맞게 학교 이메일을 인증해야만 회원가입이 가능하도록 설정

### 필터링 
* 회원가입 시 학교 선택 및 학교 이메일 인증 완료 후 로그인 시 회원의 학교 Camplus 커뮤니티로 이동
* 카테고리 별 필터링
* 자신이 쓴 글만 볼 수 있는 마이페이지 기능 

### CRUD 기능
* 게시물 페이지에서 생성, 읽기, 수정, 삭제 가능
<br>  

## REST API
<img width="1280" alt="api" src="https://user-images.githubusercontent.com/105342203/220278454-9cab1afc-5355-4db2-ac59-25f0595d8faa.png">
<br>

## 기술 스택
### Frontend 
* React
* React-Router
* Redux
* Javascript
* Axiox
* Tailwind
* Deploy - Amazon EC2  

[Camplus Frontend Repository 바로가기](https://github.com/devRent-Camplus/camplus-FE)


### Backend  
* Django
* Django REST Framework
* DB - SQLite
* Deploy - Pythonanywhere
<br>  

## 향후 보완점 (BE 부분) 
* 학교 이메일 인증 전에는 유저정보가 데이터베이스에 들어가지 않도록 설정
* 서버측에서 학교 이메일 유효성 검사를 진행
* University 모델 추가 생성을 통해 User 모델과 분리
* DRF 에서 제공하는 TokenAuthentication 사용하여 단일 Token만으로 인증 -> AccessToken & RefreshToken 방식 변경

## 발표 자료
![슬라이드11](https://github.com/al1kite/camplus-BE/assets/102217402/f18c9bac-fc6e-4bcb-902d-978a1398d97a)
![슬라이드12](https://github.com/al1kite/camplus-BE/assets/102217402/7e85cbd3-97e7-4683-a499-81f0e47e3b2c)
![슬라이드13](https://github.com/al1kite/camplus-BE/assets/102217402/6b7eeee8-a85b-43ef-ba48-f244c417081d)
![슬라이드14](https://github.com/al1kite/camplus-BE/assets/102217402/9f4deccc-de26-46bb-8560-5f7ce3cf6400)
![슬라이드15](https://github.com/al1kite/camplus-BE/assets/102217402/e614cb03-7df8-47b0-b3c2-f6d420c2f25c)
![슬라이드16](https://github.com/al1kite/camplus-BE/assets/102217402/21758d96-b5a9-4f39-9713-e367eca4440c)
![슬라이드17](https://github.com/al1kite/camplus-BE/assets/102217402/bd901e00-94e7-4e7c-84a5-d1c47543cf60)
![슬라이드18](https://github.com/al1kite/camplus-BE/assets/102217402/764e4509-4288-4545-9abe-11267de90410)
![슬라이드19](https://github.com/al1kite/camplus-BE/assets/102217402/1147d45a-369b-4bf8-a5de-fca4f8995f98)
![슬라이드20](https://github.com/al1kite/camplus-BE/assets/102217402/203162c9-3eff-4200-8f20-d4e15410cc8b)
![슬라이드21](https://github.com/al1kite/camplus-BE/assets/102217402/e6d75d19-ab91-4883-8037-4bce93708258)
![슬라이드22](https://github.com/al1kite/camplus-BE/assets/102217402/1dc42279-896d-4ca0-8271-b7ef4c46793b)
![슬라이드23](https://github.com/al1kite/camplus-BE/assets/102217402/43814917-f278-43f1-93cc-351fcc25792f)
![슬라이드24](https://github.com/al1kite/camplus-BE/assets/102217402/ca4e7cae-7c81-4398-958b-a7a34210a4df)

