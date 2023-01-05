![elice logo](https://user-images.githubusercontent.com/54767632/191028322-e9d1986e-0d98-412b-9e10-4cc4fcd1e8bf.png)

> Elice 2차 웹 서비스 프로젝트

## 📅 2차 프로젝트 일정

-   프로젝트 개발 : 12/12(월) ~ 12/30(금)
-   최종 발표 : 12/30(금) 오후 1시

<img width="449" alt="1주차 스터디 일정" src="https://user-images.githubusercontent.com/54767632/210540284-ad50a031-20c9-431e-a70b-346b9577ba25.png">

<br>

## 🖥&nbsp;&nbsp;참여자

| 레이서(이름)              | 담당 업무 |
| ----------------------- | --------- |
| :rocket: 익수              | BE (팀장)|
| :turtle: 재훈              | BE      |
| :dolphin: 동한             | FE      |
| :sunglasses: 상현          | FE      |
| :crystal_ball: 충우        | FE      |
| :hatched_chick: 채현       | FE      |                                               

<br>

## <a href="https://www.notion.so/Photo-log-4d4e74884d1540d4ae0dd9583830c275" target="_blank">📒 Notion</a>
## <a href="https://www.figma.com/file/hQnZSMnU3pxsdqGzWhg5Pw/team_7?node-id=62%3A494&t=ki7uxgEOkcSXfjJ9-1" target="_blank">📒 Figma</a>


<br>

## 📍 Code Convention

- Commit Convention 규약 (VSCode Git Emoji)

  + ✨ feat : 새로운 기능 추가  

  + 🔥 remove  : 기능 삭제  

  + 📝 docs : 문서 수정

  + 🐛 fix: 수정사항 발생시, 버그픽스

  + 🎨 style:  코드 포매팅, 세미콜론 누락 등 코드 변경이 없는 경우. 

  + ♻ refactor: 리팩토링. 

  + 🎉 init: 프로젝트 초기설정.  

  + 🚀 deploy: 배포관련 커밋. 

- Eslint, Prettier 적용

<br>

## 📚 Collaboration Tools

- Discord : 스크림장소 및 env 및 세팅법 빠르게 공유하는 용도
- Notion : 스크럼 일지기록, 이슈 발생 기록
- ErdCloud : ERD 공유 및 typeorm Entity 변환
- JIRA : Issue Tracking
- Figma : 디자인 시안 공유
- Swagger : API 문서 공유

<br>

## 🪧&nbsp;&nbsp;소개

![스크린샷 2022-12-30 오전 1 34 28](https://user-images.githubusercontent.com/59651691/209982466-94f975b7-2c34-47ad-aac6-c185535a49e8.png)

<br>

## ⚙️&nbsp;&nbsp;아키텍처

![stack](https://user-images.githubusercontent.com/59651691/209982205-54b5b26c-bf26-4ec9-a753-2fcd6fcace25.png)

<br>

## 기능

- 마이페이지 자신의 사진 게시물보기
- 위도 경도 기반 사진 게시판 검색
- hashtag 기반 검색
- CloudFront+AWS lambda 이미지 최적화
- nodemailer 임시 비밀번호 전송

<br>

## 🔍&nbsp;&nbsp;데모영상
<details>
<summary>로그인 디자인</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/54767632/209975619-8b6fa303-4e39-4131-9b03-c096e46ad3c1.gif" >
</details>

<details>
<summary>로그인 폼</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/54767632/209975626-684a1ac2-eb98-49c2-87be-e7e9df56ddf9.gif" >
</details>

<details>
<summary>인트로 페이지(인터랙션)</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/59651691/210131630-6d50021e-764d-46eb-b3ee-6bab952307fc.gif" >
</details>

<details>
<summary>지도 사진게시판</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/59651691/210131218-c90c1f98-310e-4da8-add9-024f9e7d2b21.gif" >
</details>

<details>
<summary>무한스크롤 사진 게시판</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/59651691/210131167-11ab68c7-4157-453b-97db-793ff5938421.gif" >
</details>

<details>
<summary>마이 페이지 내 게시글 조회</summary>
<img style="max-width: 100%; height: auto;" src="https://user-images.githubusercontent.com/59651691/210131349-0f3c3e21-71e8-4352-9d05-0b13118a25b4.gif" >
</details>


<br>


## 배포전략

- t2 micro(프리티어, 메모리 부족현상 swap설정으로 완화)
- elastic 고정ip(1개 사용시 프리티어, 단 연결된 인스턴스 중지중이면 안됨)
- rds(mysql 프리티어)

http://ec2-54-180-51-116.ap-northeast-2.compute.amazonaws.com






