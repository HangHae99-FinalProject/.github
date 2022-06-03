<img src="https://velog.velcdn.com/images/tty5799/post/3a6328e7-fdb6-4e46-a0a2-834d1edde501/image.png" width="80%">


# 📝모험:모두의 경험 Introduce

### 같이 모험을 떠나볼까요?

- [모험:모두의 경험]은 **대학생 재능나눔을 위한 팀업 서비스**입니다. 

- 전공 카테고리 중 협업을 함께하고 싶은 전공을 선택해 서로의 재능을 나눔으로써 실무와 유사한 경험을 쌓아나갈 수 있습니다.

🚢 **[모험 서비스 바로가기](https://www.everymohum.com/)**

🎬 **[서비스 시연 영상](https://youtu.be/flzwczkmAlQ)**


<br />

## ❓ 기획의도
`"👩 졸업작품을 만드려면 다른 전공생이 필요한데 구하기가 힘들어요."`

`"👩‍🦱 지인에게 물어보거나 다른곳 에서 구할때 신뢰를 하기 어려워요!"`

`"👱‍♂ 모든게 처음인데 비용을 들여 전문가와 함께하기는 부담스러워요"`

`"👧 "경력 있는 신입"을 원한다는데 실무 때처럼 유사한 협업 경험을 쌓고 싶어요!"`

**모험은 이런 불편함을 해소하기 위해 만들어진 팀업 서비스입니다**

<br />

## ✨ 주요 기능
<details> 
  <summary><strong> 🔍 카테고리 조회 & 검색</strong></summary>
  <br/>
  <ul>
    <li> QueryDSL을 이용한 동적 쿼리 작성으로 [전공/지역] 별 조회 기능과 [제목/닉네임/내용] 별 검색 기능을 조합해서 사용할 수 있도록 했습니다. </li>
   <br>
    <img src="https://velog.velcdn.com/images/tty5799/post/f23ab9a3-b126-40b9-b7ba-20b386f3e665/image.png" width="500">
  </ul>
</details>

<details> 
  <summary><strong> 🗨️ 실시간 1:1 채팅</strong></summary>
  <br/>
  <ul>
    <li> [WebSocket / Stomp pub/sub] 을 활용한 실시간 데이터 전송으로 유저간 1: 1 채팅 기능을 구현했습니다. </li>
   <br>
    <img src="https://velog.velcdn.com/images/tty5799/post/6d8c53af-300f-4aeb-bbac-655b90f74cb5/image.png" width="500">
  </ul>
</details>

<details> 
  <summary><strong> 💡 실시간 알람</strong></summary>
  <br/>
  <ul>
    <li> 사이트를 이용 중인 유저에게 SSE(Server Sent Event)를 이용하여 실시간 알람을 기능 제공하고 있습니다. </li>
    <li> 알람을 통해 해당글에 들어가지 않고도 발생한 이벤트(신청/수락/거절/댓글/채팅)를 확인할 수 있습니다. </li>
   <br>
    <img src="https://velog.velcdn.com/images/tty5799/post/5b5ef201-313d-47aa-a17f-50530ba6b6bb/image.png" width="500">
  </ul>
</details>

<details> 
  <summary><strong> 📩 알림 메일 전송</strong></summary>
  <br/>
  <ul>
    <li> 웹 사이트의 한계를 벗어나기 위해 JavaMailSender를 이용하여 이메일 알림 기능을 구현했습니다.
 </li>
    <li> 마이 페이지의 <알림 받기>를 통해 이메일 인증을 한 유저에 한해 신청/수락/거절/하차/채팅과 관련된 이벤트 알림 메일이 전송됩니다. </li>
   <br>
    <img src="https://velog.velcdn.com/images/tty5799/post/01396e0b-f1e4-496f-b405-b051e95a540c/image.png" width="500">
  </ul>
</details>




|메인 페이지|카테고리 조회|검색|
|:-:|:-:|:-:|
|<img src=https://user-images.githubusercontent.com/98294357/171847531-8b19a385-4a6d-4167-9ca3-6d3e43e3fdb1.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858176-119786e5-6cf0-40a0-9ff4-6d647a430f6e.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858248-76bf8378-11cd-4b81-931d-5c5d1384a2de.gif>|
|<b>글쓰기</b>|<b>모집글 보기</b>|<b>댓글</b>|
|<img src=https://user-images.githubusercontent.com/98294357/171858440-587bcf41-0816-4ae1-9f0b-a95e745de2bb.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858520-d7b69e0f-bd0e-425e-9bce-c7fa4a24741b.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858586-9c21d43a-f4ba-4c7d-a4ea-be66735f5f3f.gif>|
|<b>튜토리얼 모달</b>|<b>신청/취소하기/b>|<b>수락/거절하기</b>|
|<img src=https://user-images.githubusercontent.com/98294357/171858810-20e307fd-2e3b-4e17-81a6-043ef61dce7c.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858865-87c062cf-098c-4e75-a8bf-7fd8e02cd0e1.gif>|<img src=https://user-images.githubusercontent.com/98294357/171858903-1fbdb248-bf84-4814-9659-c76831c8bb12.gif>|
|<b>채팅</b>|<b>실시간 알람/b>|<b>알림 메일</b>|
|<img src=https://user-images.githubusercontent.com/98294357/171859207-65ec01e9-000d-47e5-9f17-ac30d3243912.gif>|<img src=https://user-images.githubusercontent.com/98294357/171859460-8f71da99-2837-4f74-9afa-b26a81fc7d17.gif>|<img src=https://user-images.githubusercontent.com/98294357/171859506-a8615757-2160-405a-8448-ceb94dbfa001.gif>|
|<b>마이 페이지</b>|
|<img src=https://user-images.githubusercontent.com/98294357/171859072-608bfd84-8738-4bbc-9588-7bc1ef78b18e.gif>|
 
 <br />

## 👥 팀 소개

#### `Frontend`
 <a href="https://github.com/tty5799" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=React&message=윤성용 (팀장) &color=61dafb&style=for-the-badge&>"/></a>
 <a href="https://github.com/losajjang" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=React&message=박재민 &color=61dafb&style=for-the-badge&>"/></a>

#### `Backend`
<a href="https://github.com/kwongyumin" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=Spring&message=권규민 (부팀장) &color=08CE5D&style=for-the-badge&>"/></a>
<a href="https://github.com/hyemco" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=Spring&message=유혜민 &color=08CE5D&style=for-the-badge&>"/></a>


#### `Designer`
 <img height="40"  src="https://img.shields.io/static/v1?label=Design&message=김정선 &color=FF7F50&style=for-the-badge&>"/></a>
 <img height="40"  src="https://img.shields.io/static/v1?label=Design&message=마은민 &color=FF7F50&style=for-the-badge&>"/></a>

<br />


## 🗓 프로젝트 기간
* 2022년 4월 22일 ~ 2022년 6월 3일   
* 배포 : 2022년 5월 31일

<br />

## 📜 아키텍쳐
<img src="https://velog.velcdn.com/images/tty5799/post/444e86d8-5aa0-40d9-8926-731cf50f4b7b/image.png">   


## 🎈 LINK  
📔  **[노션 링크]( https://maroon-borogovia-266.notion.site/55e2db12612549328acae676de9c9a60)**

<br />

## 🛠 Tech Stack
### Frontend Tech Stack 
<p align="center">
 <img src="https://user-images.githubusercontent.com/97425158/161745107-cc062718-9c52-4446-8f14-9faba0b9dea7.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745127-a3fa5ed0-ceb6-427a-94d1-834d762fd3b4.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745161-566f015b-0ec2-4bba-82aa-f3bb7498bdd7.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745198-92ff3896-7ce0-4946-a8b4-e6d23223eb3b.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745222-ea0ba9bf-86e4-48cb-8a44-f8d8bfec2d02.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745239-453b4075-7bd0-4c63-9c5a-5c1d76021b8d.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745269-27a8a71d-788d-4bdf-97e8-f86c97b224a9.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161745404-114d6c7d-c720-4370-b0dd-4aea4893bb1d.svg">
 <img src="https://user-images.githubusercontent.com/97425158/161744999-3ae8a4d1-48d8-41fc-af06-c601f6e1fc4d.svg">
</p>
<br>

### Backend Tech Stack
<p align="center">
<!-- spring -->
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
<img src="https://img.shields.io/badge/Springboot-6DB33F?style=for-the-badge&logo=Springboot&logoColor=white">
<img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<br>
  
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white"> 
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> 
<br>

<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white"> 
<img src="https://img.shields.io/badge/codedeploy-6DB33F?style=for-the-badge&logo=codedeploy&logoColor=white">
<img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/stomp-000000?style=for-the-badge&logo=stomp&logoColor=white">
<img src="https://img.shields.io/badge/SockJS-7D929E?style=for-the-badge&logo=sockJS&logoColor=white">
<img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white">
<img src="https://img.shields.io/badge/Apache JMeter-D22128?style=for-the-badge&logo=Apache JMeter&logoColor=white">
<img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"></
