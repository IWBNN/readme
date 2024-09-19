<p align="middle" >
  <img width="200px;" src="https://firebasestorage.googleapis.com/v0/b/fir-readme-storage.appspot.com/o/logo.jpg?alt=media&token=46aada62-533c-4ee0-8b0a-c454d033733f"/>
</p>
<h1 align="middle">LiveScore</h1>
<h3 align="middle">체육대회 실시간 스트리밍 서비스</h3>

<br/>

## 📝 작품소개

본 서비스는 알기 어려운 체육대회 일정과 결과들을 일목요연하게 정리하고 체육대회를 하는 장소 에 있지 않더라도 체육대회 현황을 실시간으로 확인할 수 있는 대진표와 실시간으로 소통할 수 있는 라이브 채팅, 댓글 기능, 그리고 현재 진행중인 대회와 과거에 한 대회를 스트리밍 하는 서비스를 제공합니다.

<br/>

## 🌁 프로젝트 배경

학교 체육대회는 참가자나 관람객들이 모든 정보를 실시간으로 파악하기 어려운 경우가 많습니다. 특히 대회 현장에서 경기를 직접 관람하지 않는 경우, 경기 진행 상황을 정확히 확인하기 힘들고, 대진표나 결과를 확인하기 위해 별도의 자료를 찾아야 하는 불편함이 존재합니다. 이러한 문제를 해결하기 위해 본 서비스는 체육대회의 일정과 결과를 효율적으로 관리하고, 실시간 대진표 및 경기 상황을 손쉽게 확인할 수 있도록 합니다. 이를 통해 사용자들은 현장에 있지 않아도 모든 경기를 실시간으로 스트리밍으로 즐길 수 있으며, 과거에 진행된 경기 역시 손쉽게 다시 볼 수 있습니다.

따라서 이 프로젝트는 체육대회의 정보를 실시간으로 제공하고, 사용자의 편리성을 높여 체육대회를 더 쉽게 접근하고 즐길 수 있도록 하는 것을 목표로 합니다.

<br/>

## 🎞 Demo
[리드미 시연영상보기](https://www.youtube.com/watch?v=X-rooURijag)

<br/>

## ⭐ 주요 기능
- **mainPage** : 과거-현재-미래에 진행할 대진표 종목별, 일별로 제공

![메인페이지](https://github.com/user-attachments/assets/f914ebb1-08d4-46a9-8552-f8b801945baf)

- **bracketPage** : 리그, 토너먼트 형식의 대진표 제공

![대진표페이지](https://github.com/user-attachments/assets/91753022-7b71-413a-9936-fd6e957a1c2b)

- **myPage** : 내 정보 조회 및 닉네임, 비밀번호, 로그아웃 기능 제공

![마이페이지](https://github.com/user-attachments/assets/a7207648-2c4d-47f1-86c3-2a2fbf40c0f6)

- **LiveStreamingPage** : 실시간 비디오 스트리밍 및 채팅 기능 제공 

![라이브스트리밍페이지](https://github.com/user-attachments/assets/1bf27684-507c-482b-8327-788bcc985b12)

- **로그인/회원가입** : MFA를 활용한 이메일 인증 방식으로 회원가입, 로그인 관리

![로그인](https://github.com/user-attachments/assets/b215ff6f-2180-4b79-ab13-eaada62056b4)
![회원가입](https://github.com/user-attachments/assets/e830b2ff-d869-4ece-ad8f-c6215069e15b)


## 🔨 프로젝트 구조
![frontend](https://github.com/user-attachments/assets/3eb7fd09-39c6-4c72-8cc1-56a36020f852)
![backend-서버](https://github.com/user-attachments/assets/81174db2-63bc-4198-8d5f-f97e69762db5)
![backend-db](https://github.com/user-attachments/assets/6f784e1d-2705-41f6-be5b-79871c4b2d5b)
![전체 흐름도](https://github.com/user-attachments/assets/a538f9ee-7732-442d-8599-212e1c43cd76)
![스크린샷 2024-08-28 100106](https://github.com/user-attachments/assets/03189143-5555-4a0a-b8ed-b82f2c0b4edc)



<br/>

## 🔧 Stack

**Frontend(Web)**
- **Language** : JavaScript, TypeScript
- **Library & Framework** : React, Styled-Components, Axios
- **Deploy**: AWS(S3+CloudFront)
<br />

**Backend**
- **Language** : Java 
- **Library & Framework** : Spring Boot, WebSocket, rtmp-hls
- **Database** : MySQLDB
- **ORM** : JPA
- **Deploy**: AWS(EC2, RDS)

<br/>

## 👍 활용분야

**편의성**: 학생과 취업준비생이 문서 형식에 구애받지 않고 손쉽게 포트폴리오 제작이 가능하다.

**확장성**: 학생과 취업준비생 뿐만 아니라 기업 등의 고유 양식으로도 제공하여 다양한 분야에 활용할 수 있다.

**수익성**: 사용자가 자신의 디자인을 판매해 수익을 창출할 수 있고 운영자는 판매 수수료를 통하여 수익 창출이 가능하다.

**획일화된 양식**: 제출물을 하나의 디자인 양식으로 관리하여 자료를 분류 및 보관하는데 용이하다.

<br/>

## 🙋‍♂️ Developer

|                                          Backend                                           |                                         Frontend                                          |                                         Frontend                                          |                                         Frontend                                         |             
| :----------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | 
|  |  |  |  | 
|                            [박정근](https://github.com/JGeun)                            |                           [유준호](https://github.com/yjh-1008)                           |                          [이재영](https://github.com/2jaebbang)                          |                         [이찬우](https://github.com/tigerlcw)                          |                     
