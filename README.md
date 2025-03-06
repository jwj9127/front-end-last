## 📛프로젝트명 - 콘테스트메이트(CONTESTMATE)

#### Ai를 활용한 공모전 팀 추천 서비스

<br/>

## 🚧프로젝트 소개

콘테스트 메이트(Contest Mate)는 인공지능을 활용하여 공모전에 참여하려는 사용자에게 최적의 팀원을 추천하는 웹 애플리케이션이다. 

공모전 정보를 제공하며, AI 모델로 사용자 프로필을 분석하여 공모전을 함께할 팀원을 추천한다.

이 플랫폼의 주요 기능은 팀원 추천 , 공모전 정보 제공 , 채팅 기능을 지원하며, 맞춤형 팀원을 추천하여 공모전 참여율과 결과물의 질을 높인다. 자세한 설명은 [여기](file:///C:/Users/jwj/Downloads/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8.pdf)를 참고하세요!

## 👩🏻‍💻 프로젝트 참여 인원

#### Frontend - 1명

#### Backend - 4명

## ✨ 기술 스택

- 기획디자인 : <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
- 프론트엔드 : <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=html5&logoColor=white">

- 백엔드 : <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=JPA&logoColor=white"/> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src = "https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">

- ETC : <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">

## 💡 서비스 핵심 기능

**`공모전 관리 - 메인 페이지`**

<br/>

  - 웹 크롤링을 통해 외부 사이트에서 공모전 데이터를 긁어 온다.
  - 해당 공모전 데이터를 가공하여 현재 날짜를 기준으로 분류하여 사용자에게 보여준다.

<br/>

**`공모전 대기열 참여 - 공모전 상세 페이지`**

<br/>

  - 공모전 정보를 상세하게 볼 수 있다.
  - 참여하기를 통해 공모전 팀원을 찾을 수 있다.
  - 참여하기는 공고 마감 전, 프로필 등록을 완성해야 할 수 있다.

<br/>

**`공모전 팀원 구하기 - 추천 메이트 컴포넌트`**

<br/>

  - 공모전을 원하는 팀원들을 추천받아 그룹을 만들 수 있다.
  - AI에게 추천받아 그룹을 만들 수 있다.
  - 그룹이 있다면 추가 선택 후 그룹에 초대할 수 있다.

<br/>

**`공모전 채팅방 - 공모전 확정 컴포넌트`**

<br/>

  - 공모전 팀원과 소통할 수 있다.
  - 서로 프로젝트를 진행해도 괜찮다고 느끼면 팀 확정으로 공모전을 확정지을 수 있다.

<br/>

**`마이페이지`**

<br/>

  - 회원 정보 수정, 회원 탈퇴가 가능하다.
  - 프로필을 등록,수정 할 수 있다.

## 🖼️ 디자인

- 메인화면
<center><img src="https://github.com/user-attachments/assets/fd914351-37e5-4996-a6ba-a6fcbdbac8be" width="300"></center>

- 공모전 상세 화면
<center><img src="https://github.com/user-attachments/assets/35087675-4532-48ef-86f8-4a0347bf389d" width="300"></center>

- 공모전 팀원 구하기 화면
<center><img src="https://github.com/user-attachments/assets/b12f6646-5fb3-4938-a287-d7f136fba30e" width="300"></center>

- 공모전 채팅방 화면
<center><img src="https://github.com/user-attachments/assets/32283b04-077b-4b3d-b071-7209d771c092" width="300">
<br/>
<img src="https://github.com/user-attachments/assets/39196edb-ee68-46aa-a7a1-dec8e9ea093c" width="300">
</center>

- 마이페이지 화면
<center>
<img src="https://github.com/user-attachments/assets/2329aa85-e0f3-4cff-85e7-341149d65e1e" width="300">
</center>

## 🍆 본인이 구현한 기능

- 메인, 공모전, 회원 등 모든 페이지 퍼플리싱

- Modal , Swal , DaumPostcode , Slider - 리액트 라이브러리들을 구글링하여 프로젝트에 맞게 CSS와 JS 커스터마이징

- WebSocket을 이용한 양방향 통신 - 웹소켓 객체를 만들고 onopen, onmessage 메서드들을 사용하여 서버와 양방향 통신을 이루어냄

## 🚩 트러블 슈팅

### 1. 문제 - 라이브러리 사용 미숙
#### 상황
- Modal , Swal 등 여러가지 라이브러리를 커스터마이징해야하는데 구글링을 해도 안 나오는 문제 발생

#### 해결 방법
- 개발자 도구를 열어 직접 하나하나 클래스명을 확인하여 커스터마이징 성공

#### 배운 점 
- 관련 자료가 없더라도 때로는 개발자 도구에서 문제를 해결할 수 있다는 걸 알게 되었다.

### 2. 문제 - 웹소켓 통신 오류
#### 상황
- 웹소켓 통신 중 message의 type이 맞지 않고 response 데이터 형식을 알지 못하는 문제 상황 발생

#### 해결 방법
- 직접 백엔드 코드를 확인하여 데이터 형식을 확인하여 해결

#### 배운 점 
- 양방향 통신에 대해서 잘 이해가 되지 않던 부분들을 이번 웹소켓 프로젝트를 통하여 조금은 이해가 되었다.
