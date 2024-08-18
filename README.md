# 우산 : 우리는 함께 산다 ☂️

### 클릭 시 이동 ↓↓
<a href="https://github.com/LuckyVickys/woosan-back">우산 프로젝트 BE Repository</a> <br>
<a href="https://github.com/LuckyVickys/woosan-front">우산 프로젝트 FE Repository</a> <br>
<a href="https://www.canva.com/design/DAGMSO8HY9M/OhlrF8D_8oi9edJX00W9mw/edit?utm_content=DAGMSO8HY9M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">우산 프로젝트 PPT</a>
<br><br>

## 1. 프로젝트 소개

### 1) 개발 기간 📆
2024.06.05 ~ 2024.07.29 (약 8주)

<br>

### 2) 사용 스택 🔨
|Front-End|<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white" /> <img src="https://img.shields.io/badge/Redux-764ABC?style=flat&logo=Redux&logoColor=white" /> <img src="https://img.shields.io/badge/Sass-CC6699?style=flat&logo=Sass&logoColor=white" /> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" /> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" /> <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=Axios&logoColor=white" /> |
|:---:|:---:|
|Back-End|<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=SpringBoot&logoColor=white" /> <img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat&logo=springsecurity&logoColor=white" /> <img src="https://img.shields.io/badge/JPA-6DB33F?style=flat&logo=JPA&logoColor=white" /> <img src="https://img.shields.io/badge/JWT-EF2D5E?style=flat&logo=JWT&logoColor=white" /> <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Conda-Forge&logoColor=white" /> <img src="https://img.shields.io/badge/ElasticSearch-005571?style=flat&logo=ElasticSearch&logoColor=white" /> <br> <img src="https://img.shields.io/badge/Logstash-005571?style=flat&logo=Logstash&logoColor=white" /> <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat&logo=Redis&logoColor=white" /> <img src="https://img.shields.io/badge/Lombok-D24939?style=flat&logo=Lombok&logoColor=white" /> |
|Tool|<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=Figma&logoColor=white" /> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat&logo=Jira&logoColor=white" /> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" /> <img src="https://img.shields.io/badge/VSCode-2496ED?style=flat&logo=VSCode&logoColor=white" /> <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat&logo=IntelliJ IDEA&logoColor=white" /> |
|DevOps|<img src="https://img.shields.io/badge/NaverCloud-03C75A?style=flat&logo=NaverCloud&logoColor=white" /> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=Jenkins&logoColor=white" /> <img src="https://img.shields.io/badge/NGINX-009639?style=flat&logo=NGINX&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white" /> |
|API|<img src="https://img.shields.io/badge/KakaoLogin-FFCD00?style=flat&logo=KakaoLogin&logoColor=white" /> <img src="https://img.shields.io/badge/KakaoMap-FFCD00?style=flat&logo=KakaoMap&logoColor=white" /> <img src="https://img.shields.io/badge/Papago-2496ED?style=flat&logo=Papago&logoColor=white" /> <img src="https://img.shields.io/badge/Clova-00BC8E?style=flat&logo=Clova&logoColor=white" /> |
<br>

### 3) 프로젝트 인원, 역할과 개발 내용
Full stack 4명, FE 1명 총 5명
|<b>이름</b>|<b>역할</b>|<b>BE</b>|<b>FE</b>
|:---:|:---:|:---:|:---:
|서혜리|PM|- SpringBoot, Spring Security, JWT, Redis 설정 <br> - 회원가입, 일반/소셜 로그인, 회원 탈퇴 <br> - Spring Security + JWT <br> - 회원가입 인증코드 및 refreshToken Redis에 저장 <br> - 이메일, 닉네임 중복확인 <br> - 임시 비밀번호 메일 전송 <br> - 비밀번호 수정 <br> - 로그인한 회원 정보 조회 <br> - 쪽지 전송, 삭제, 조회 <br> - clova summary(세 줄 요약 기능)|- Redux, Cookie를 활용한 회원 정보 관리(로그인, 로그아웃, 회원 탈퇴) <br> - 소셜 로그인 <br> - 헤더, 프로필 드롭다운 <br> - 마이페이지 및 관리자 페이지 쪽지함 <br> - 쪽지함 라우팅 <br> - clova summary <br> - 쪽지 전송, 삭제, 페이지네이션, 상세페이지 조회
|김동우|팀원|- 게시물 작성, 수정, 삭제, 페이지네이션 <br> - 게시글 댓글 작성, 삭제 <br> - 게시글 및 댓글 추천(베스트 게시글, 베스트 댓글 포함) <br> - ElasticSearch 기본 검색, 유의 검색, 일별 검색어 순위 <br> - Logstash 설정|- 프론트 서버 CI/CD <br> - 게시물 작성, 수정, 삭제, 페이지네이션 <br> - 게시글 댓글 작성, 삭제 <br> - 마이페이지 게시글 및 댓글 목록
|김재호|팀원|- 클라우드 인프라 설계 <br> - 백엔드 서버 CI/CD <br> - Papago Translate(한영 번역) <br> - 사진 파일 업로드 및 출력(Object Storage) <br> - MySQL, Search Engine Service 동기화 <br> - ElasticSearch 초성 검색, 검색어 자동완성|- 이미지 등록, 수정, 삭제, 조회 <br> - 게시물 상세페이지 조회 <br> - 댓글 페이지네이션 퍼블리싱
|유지오|팀원|X|- 반응형 <br> - 라이트/다크 모드 <br> - 메인 페이지 <br> - 헤더, 푸터, Nav, SideBar, 검색창 <br> - 게시글 및 댓글 드롭다운 <br> - 라우팅 <br> - 이메일 닉네임 중복확인, 회원가입 <br> - 파파고 및 클로바 버튼 퍼블리싱 <br> - 신고 모달 퍼블리싱 <br> - 신고 등록, 쪽지 전송 <br> - 마이페이지 회원 정보 수정 <br> - 마이페이지 쪽지함 퍼블리싱 <br> - 관리자페이지 배너 관리 퍼블리싱 <br> - 관리자페이지 신고 관리, 공지사항 관리
|이덕현|팀원|- 모임 생성, 수정, 삭제, 조회 <br> - 모임 댓글 작성, 수정, 삭제 <br> - 태그를 이용한 필터링 <br> - 모임원: 모임 신청, 취소, 탈퇴 <br> - 모임장: 모임원 조회, 승인, 거절, 강퇴|- 모임생성, 수정, 삭제, 조회 <br> - 모임 댓글 작성, 수정, 삭제 <br> - 태그를 이용한 필터링 <br> - 모임원: 모임 신청, 취소, 탈퇴 <br> - 모임장: 모임원 조회, 승인, 거절, 강퇴 <br> - 카카오맵 API
<br>

## 2. <a href="https://docs.google.com/spreadsheets/d/19taF1XyT4yUDGoeNRijiSMMParugKapNYVWsBwyKFtA/edit?usp=sharing">기획</a>

### 1) 기획 의도
'나 혼자 산다'라는 TV 프로그램, 본 적 있으신가요? <br>
1인 가정이 늘어나는 세태를 반영해 혼자 사는 유명인들의 일상을 관찰 카메라 형태로 담은 다큐멘터리 형식의 예능 프로그램입니다. <br>
이러한 예능 프로그램이 흥행하고, 전체 가구의 40%가 넘는 비율을 차지할 정도로 1인 가구의 규모는 점점 증가하고 있습니다.<br>
<br>
또한 10대부터 40대까지 매주 온라인 커뮤니티를 이용하는 비율이 50% 이상에 달하고, <br>
10명 중 9명 정도가 숏폼 영상 플랫폼을 이용하고 있습니다. <br>
<br>
따라서 정보 공유 게시판과 쪽지, 모임을 통해 다양한 사용자 간 활발한 소통을 촉진하고, <br>
번역과 요약 기능을 곁들여 효율적인 소통이 가능한 1인 가구 웹 커뮤니티를 만들고자 하였습니다.

### 2) 일정 관리
Slack과 Jira를 통하여 일정 관리를 했습니다.
![image](https://github.com/user-attachments/assets/053dbe13-10d1-4ce9-a950-f2a9b45f7ef7)

### 3) <a href="https://docs.google.com/spreadsheets/d/19taF1XyT4yUDGoeNRijiSMMParugKapNYVWsBwyKFtA/edit?usp=sharing">사용자 요구사항</a>

### 4) 회원 및 포인트 정책
비회원과 회원, 그리고 등급에 따라 이용할 수 있는 정책을 분류하였습니다.
![image](https://github.com/user-attachments/assets/4bb18790-4af0-44ce-9cee-73d3020c56f8)

### 5) <a href="https://docs.google.com/document/d/1MKFOMg7aaxHg-g86xs-NmV8JBOb4Y6jsVTfmT90pQ5w/edit?usp=sharing">화면 정의 및 기능 명세서</a>

### 6) <a href="https://docs.google.com/spreadsheets/d/19taF1XyT4yUDGoeNRijiSMMParugKapNYVWsBwyKFtA/edit?usp=sharing">테스트 케이스</a>

### 8) <a href="https://docs.google.com/spreadsheets/d/19taF1XyT4yUDGoeNRijiSMMParugKapNYVWsBwyKFtA/edit?usp=sharing">API 명세서</a>

## 3. 설계

### 1) ER Diagram
![Woosan3 +](https://github.com/user-attachments/assets/7c9efe0b-3942-4776-9132-b059cb1eaf12)

### 2) Cloud Architecture
![cloudAC](https://github.com/user-attachments/assets/2c9f91b1-b8b0-4d25-9dca-f0a453e627b9)

### 3) Usecase Diagram
 - 비회원
   ![normal_uc](https://github.com/user-attachments/assets/30f5f305-d15c-4c44-b297-beb71e0ffb9b)
 - 회원
   ![member_uc](https://github.com/user-attachments/assets/41a859c7-2f3c-4b22-9537-252f33c7ab0c)
 - 관리자
   ![admin_uc](https://github.com/user-attachments/assets/fcc93698-0aa9-4518-b8fc-447ad117c5df)

### 4) Class Diaram
- Member
![image](https://github.com/user-attachments/assets/03761d40-3da6-415e-9197-8037ffba9a9c)
- Board
![image](https://github.com/user-attachments/assets/743c8e12-53d7-48c8-a6c4-0be48484a3cf)
- Like, Report
![image](https://github.com/user-attachments/assets/6879b8d1-c887-408e-9f89-94c928af4ab2)
- Message
  ![message_cd](https://github.com/user-attachments/assets/42301222-c0c8-437b-82b0-0803062d3cf6)
- Matching
  ![memberMatching_cd](https://github.com/user-attachments/assets/b968590b-a9fe-435f-82b0-f3f50c762d9f)
  ![matchingboar_cd](https://github.com/user-attachments/assets/81d6c6ac-ac4d-4e17-a23a-504a9357bc00)
  ![MatchingBoardReply_cd](https://github.com/user-attachments/assets/5ca04eab-7e56-4c63-9565-04f55cf6136d)
- Admin
![image](https://github.com/user-attachments/assets/31ec8b14-b765-4570-9722-8a5fbd57f76d)

## 4. 기능

### 1) <a href="https://github.com/LuckyVickys/woosan-front/blob/main/Readme.assets/front.md">화면</a>
- 반응형 웹
- 라이트모드 및 다크모드

### 2) 회원 기능
<a href="https://github.com/LuckyVickys/woosan-back/tree/main/Readme.assets/member">💾BE</a> <a href="https://github.com/LuckyVickys/woosan-front/tree/main/Readme.assets/member">🖥️FE</a>
- 회원 가입
- 일반 로그인
- 카카오 로그인
- 프로필 드롭다운 (회원 정보 조회)
- 비밀번호 찾기
- 로그아웃
- 회원 탈퇴
- 쪽지 전송
- 마이페이지
  - 회원 정보 수정
  - 작성한 게시글 조회
  - 추천 게시글 조회
  - 모임 조회
  - 보낸 쪽지함
  - 받은 쪽지함

### 3) 쪽지 기능
<a href="https://github.com/LuckyVickys/woosan-back/tree/main/Readme.assets/message">💾BE</a> <a href="https://github.com/LuckyVickys/woosan-front/tree/main/Readme.assets/message">🖥️FE</a>
- 쪽지 전송

### 4) 게시판 기능
<a href="https://github.com/LuckyVickys/woosan-back/tree/main/Readme.assets/board">💾BE</a> <a href="https://github.com/LuckyVickys/woosan-front/tree/main/Readme.assets/board">🖥️FE</a>
- 게시글 작성
- 게시글 조회
- 게시글 수정
- 게시글 삭제
- 댓글 작성
- 댓글 조회
- 댓글 작성
- 게시글 추천
- 댓글 추천
- 작성자 신고

### 5) 모임 기능
<a href="https://github.com/LuckyVickys/woosan-back/tree/main/Readme.assets/matching">💾BE</a> <a href="https://github.com/LuckyVickys/woosan-front/tree/main/Readme.assets/matching">🖥️FE</a>
- 정기모임, 번개, 셀프 소개팅 생성, 수정, 삭제
- 모임 조회
- 가입신청, 취소, 탈퇴
- 가입신청, 모임원 조회
- 가입신청 승인, 거절, 모임원 강퇴
- 모임 댓글과 답글 작성, 조회, 삭제 

### 6) 관리자 기능
💾BE <a href="https://github.com/LuckyVickys/woosan-front/tree/main/Readme.assets/admin">🖥️FE</a>
- 메인 페이지 배너 관리
- 신고 관리
- 공지사항 관리
- 보낸 쪽지함
- 받은 쪽지함
