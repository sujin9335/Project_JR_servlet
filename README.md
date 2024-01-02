# :office: 자격증 정보 관리 시스템
....
# 1. 기획 의도
**정보 제공** : 자격증에 대한 종합정보(시험일, 시험과목, 응시료 등)을 제공합니다.<br>
**추천 서비스** : 직무에 따른 자격증 추천 서비스를 제공합니다<br>
**스터디** : 자격증 관련 질문 및 의견을 공유하며 서로의 지식과 경험을 소통 합니다.<br>
**기술** : Servlet+JSP 기반으로 Oracle로 데이터 관리를 하여 정보를 제공하는 프로젝트 입니다.

# 2. 🛠개발 환경
 
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/OracleDeveloper-007396?style=for-the-badge&logo=devlop&logoColor=white"> <img src="https://img.shields.io/badge/eXERD-C28F2C?style=for-the-badge&logo=exerd&logoColor=white"> <img src="https://img.shields.io/badge/window-0078D4?style=for-the-badge&logo=windows&logoColor=white"> <img src="https://img.shields.io/badge/mac-000000?style=for-the-badge&logo=macos&logoColor=white"><img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"><img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white">
<img src="https://img.shields.io/badge/Tomcat-333333?style=for-the-badge&logo=apachetomcat&logoColor=white">
<img src="https://img.shields.io/badge/HTML-1572B6?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-E34F26?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">

# 3. 👯‍♂️역할 분담
- 김수진 : My스터디, My교재학습, My자격증, 직업검색<br>
- 김혜민 : 사이드바, 헤더, 광고배너 디자인<br>
- 염현빈 : 회원가입, 로그인, 로그아웃, 아이디찾기, 비밀번호 재설정<br>
- 오승현 : 자유게시판, FAQ, QNA <br>
- 이도훈 : 자격증관리, 시험관리, 일정관리, FAQ관리, 금지어 관리<br>
- 이슬아 : 교재조회, My교재등록, 학원조회<br>
- 허수경 : 자격증조회, 자격증 스터디 신청, 자격증 후기, 자격증 일정, 자격증 추천<br>
- 황유진 : 메인화면, 관리자 메인화면, 학원관리<br>

# 4. 데이터 구조
## 1. 순서도
> ![sun1](./images/sun.png)

## 2. eXERD
> ![erd](./images/erd1.png)

# 5. 기능 구현
## 1. 초기 화면
> - main page <br>
> ![m](./images/main.png)
> - login page <br>
> ![log](./images/log.png)
> ![log](./images/join.png)

## 2. 기능 화면
> - 자격증 조회<br>
> ![ja1](./images/ja1.png)
> ![ja2](./images/ja2.png)
> - 자격증 추천<br>
> ![ja3](./images/ja3.png)
> - 교재 조회<br>
> ![book1](./images/book1.png)
> ![book2](./images/book2.png)
> - 학원 조회<br>
> ![aca](./images/aca1.png)
> - 직업 조회<br>
> ![job1](./images/job11.png)
> ![job2](./images/job22.png)
> - 자유 게시판 <br>
> ![board1](./images/board1.png)
> ![board2](./images/board2.png)
> - My페이지 스터디 <br>
> ![study1](./images/study11.png)
> ![study2](./images/study22.png)

# 6. 기능 분석
> <strong>MVC Model</strong><br>
>> - Model, View, Controller 세가지 구성 요소로 나누어 개발하는 방법
>> ![mvc](./images/mvc.png)

> <strong>Ajax</strong><br>
>> - 웹 페이지에서 비동기적으로 서버와 통신하는 기술
>> ![ajax](./images/ajax.png)

> <strong>Autocomplete</strong><br>
>> - 사용자가 입력한 내용에 따라 자동 완성 기능을 제공하는 기능
>> ![auto](./images/auto.png)

# 7. 📜세부 일정
> <strong>11월 13일 ~ 11월 20일</strong><br>
>> - 요구 분석
>> - 순서도
>> - 화면 설계도
>> - ERD<br>

> <strong>11월 21일 ~ 11월 23일</strong><br>
>> - 더미 데이터 
>> - 테이블 정의서 작성(DDL)
>> - 데이터 정의서 작성(DML)<br>

> <strong>11월 24일 ~ 11월 30일</strong><br>
>> - 개발진행
>> - 데이터 통합 및 디버깅
>> - PPT 작성<br>

> <strong>12월 1일</strong><br>
>> - 발표 <br>
  
  # 핵심 트러블 슈팅
<details>
<summary> <strong>1. BootStrap 사용법이 익숙치 않았다</strong> </summary>
  - 부트스트랩으로 짜여있는 템플릿을 사용했는데 익숙하지 않아 사용하고 가공 하는데 어려움이 있었다.<br>클래스명칭으로 css처리를 할 수 있고 다양한 템플릿을 제공하여 쉽고 빠르게 view를 만들 수 있었다.<br><br>
</details>
<details>
<summary> <strong>2. git 사용의 어려움이 있었다.</strong> </summary>
  - 개인 브랜치 생성 후 main에 merge하는 방식으로 진행 했는데 servlet Controller의 명칭이 겹치는 부분이있어 일일이 확인 후 merge를 진행 했다.<br><br>
</details>

# 그 외 이슈
<details>
<summary><strong>
  </strong> </summary>
 <br>
</details>
  
  

  
