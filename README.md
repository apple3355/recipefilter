# 이 건 못 먹 지🥗
---

# 1. 프로젝트 개요

## 1) 프로젝트 주제

채식주의자 🥦, 육식주의자 🍖 다 모이세요! 
본인 취향이나 체질에 맞지않는 식재료를 제외하고 거기에 따른 레시피를 얻어가실수 있습니다.
정보가 무궁무진한 21세기에는 온라인 상에서 음식과 레시피에 대한 정보를 쉽게 찾을 수 있습니다.
사람들이 음식에 대한 정확한 정보를 많이 접할 수 있기때문에 본인의 개성으로 먹지 않거나 못 먹는 음식에 대해 구분하곤 하는데요. 그에 따른 특정 성분 혹은 식품군 섭취를 원하지 않는 사용자들의 니즈를 충족시켜주기 위한 서비스입니다.


## 2) 팀원소개🧙‍♂️

3인 1조 팀프로젝트

🧑🏻‍💻 고성범: 메인페이지 CSS,  레시피 웹크롤링 및 레시피 조회 기능,  레시피 필터링 및 검색 기능

🧑🏻‍💻 배은지: 메인페이지/회원가입/로그인 페이지 CSS,  회원가입/로그인/개인정보수정 CRU

🧑🏻‍💻 이도연: 개인정보수정/찜목록 페이지 CSS, 찜목록 CRD 기능 구현


## 3) 스케줄링📆

2021년 11월 1일 ~ 2021년 11월 5일

- 11월 1일: 프로젝트 주제선정 및 와이드프레임 작성
- 11월 2일: 페이지 구현, 만개의 레시피 웹크롤링
- 11월 3일: 레시피 조회(메인페이지) 기능구현, 로그인&회원가입, 찜목록 등록,삭제 기능구현
- 11월 4일: User에 따른 커스텀 레시피 필터 및 Button에 따른 레시피 필터 기능구현, 재료검색 기능구현, 개인정보수정 기능구현, 버그 테스트(일부) 및 수정
- 11월 5일: 전반적인 css 정리 및 배포

---

# 2. 개발환경

## 1) FRONT-END
<img src="https://img.shields.io/badge/HTML 5-E34F26?style=flat&logo=HTML5&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=CSS3&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Ajax-3766AB?style=flat&logo=Ajax&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/jinja 2-B41717?style=flat&logo=Jinja&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Bulma-00D1B2?style=flat&logo=Bulma&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;


## 2) BACK-END
<img src="https://img.shields.io/badge/Python 3-3766AB?style=flat&logo=Python&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/mongoDB-47A248?style=flat&logo=MongoDB&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=Flask&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;


## 3) DEPLOY
<img src="https://img.shields.io/badge/AWS EC2 (Ubuntu 18.04 LTS)-232F3E?style=flat&logo=Amazon AWS&logoColor=white"/></a>&nbsp;&nbsp;&nbsp;

---

# 3. 핵심기능

## 1) 회원가입/로그인/개인정보수정

- JWT 인증 방식으로 로그인 구현
- ID 중복확인, 각 필드별 유효성체크
- ID를 제외한 개인정보 수정 기능

## 2) 레시피/레시피 필터, 검색

- 크롤링된 data를 각 user에 따른 커스텀(유저가 지정한 재료가 포함된 레시피에는 '이건못먹지' 이미지 띄워줌)하여 보여줌
- 메인페이지 중앙의 검색창에 재료 검색 후 검색 버튼 클릭 시, 해당 검색어(재료)가 포함된 레시피만 필터해서 조회
- 메인페이지 중앙의 재료버튼 클릭 시 해당 재료가 들어간 레시피 구분(필터된 레시피에는 '이건못먹지' 이미지 띄워줌)

## 3) 찜 💘목록(찜하기, 찜삭제)

- 메인페이지의 레시피에서 '찜하기' 버튼을 클릭할 경우 찜목록에 추가
- 중복된 레시피가 있을 경우 alert('이미 찜목록에 추가되어 있습니다.')
- 찜목록 페이지에서 '찜삭제' 버튼을 클릭할 경우 삭제

---

# 4. 데모영상

- 📺  **Our Youtube link ->**  [![Youtube Badge](https://img.shields.io/badge/Youtube-ff0000?style=flat&logo=youtube&link=https://youtu.be/2tgA8FhfZqY)](https://youtu.be/2tgA8FhfZqY)    

---

# 5. Blog 

<img src="https://img.shields.io/badge/고성범-3766AB?style=flat"/></a> 🎈**Blog link ->**  https://velog.io/@sbko <br>
<img src="https://img.shields.io/badge/배은지-47A248?style=flat"/></a> 🎈**Blog link ->**  https://create-something-from-nothing.tistory.com/ <br> 
<img src="https://img.shields.io/badge/이도연-7952B3?style=flat"/></a> 🎈**Blog link ->**  https://velog.io/@doyeon11 <br>
