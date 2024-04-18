# Project Weatherable ver 1.0
개발기간: 3월 2일 ~ 4월 2일 (4주)

<img src="https://github.com/dydgjs200/Weatherable_backend/assets/146299597/a8aeda62-c8ed-4dca-863d-8c89c9426c8b" widht="400" height="350" />


## 배포 주소
*비용 문제로 서버 닫음

https://weatherable.store


**Manual**
* sign up can be possible
* When you go to login page, test id and password already be put.

|type|id|pw|
|----|--|------|
|guest|test|111111|

## 서비스 아키텍처
![weatherable_architecture drawio](https://github.com/JHSasdf/Project4_weatherable_backend/assets/146299597/d5982012-ce01-414e-8c04-366ed9b9b5ee)


## DB 구조도
![image](https://github.com/dydgjs200/Weatherable_backend/assets/146299597/8d24a967-e09e-433c-b147-30ad8e89537f)


## API Address
https://www.notion.so/Weatherable-API-Reference-307d36f1808b4b8daffab7d4a4ae4b71


## 개발팀 소개
|이름|담당|역할|
|------|-----|--------|
|김재현|프론트엔드| 마이페이지, 로그인, 회원가입 구현|
|윤정훈|프론트엔드| 코디 페이지 구현 |
|최진|프론트엔드| 옷장 페이지 구현 |
|최용헌|백엔드,조장| teacherble machine, openAI API 구현, 배포  |
|최예지|백엔드| 크롤링 데이터 저장, SPRING BOOT MONGODB 관련 로직, SPRING BOOT AWS S3 관련 로직 구현|
|선지훈|백엔드| SPRING BOOT 백엔드 로직 구현|


## 프로젝트 소개
This project is REST API for weatherable Front-end.
It response when front-end (client) request something. Signup or Login or etc...

mainly it has 3 features
1. closet feature
2. codi and community feature
3. cloth recommend feature


## 시작 가이드
**REQUIREMENTS**
For building and running the application you need:
* Spring Boot 3.24 or higher

* **Installation**
```
$ git clone https://github.com/dydgjs200/Weatherable_backend.git
gradle build
Execute Weatherable Application
```

## Stacks
**Python BACKEND**
https://github.com/JHSasdf/Project4_weatherable_front

**Python BACKEND**
https://github.com/JHSasdf/Project4_weatherable_python

***SPRING***

**Environment** 

<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Git Hub-181717?style=for-the-badge&logo=GitHub&logoColor=white">

**Communication**

<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> 


**BACKEND**

<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JWT&logoColor=white">
<img src="https://img.shields.io/badge/Bcrypt-000000?style=for-the-badge&logo=Bcrypt&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/Cors-000000?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">


## 화면 구성
메인페이지|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/614427bd-0fd8-464d-9822-f684ccfa8e63"/>|

<br>

옷장페이지|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/f4ea06d0-3d06-49f1-83e6-d8465d923cb5"/>|

<br>

코디페이지|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/eb56b197-9a24-4c90-a57a-f7b8a9f6f640"/>|

<br>

마이페이지||수정페이지|
---|---|---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/3ce20671-427b-4c3d-95b0-ad14d1649c0f"/>|<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/de742d58-9b18-4972-a0b2-f407a6018b38"/>|<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/0c893c9e-bd65-4486-a170-ed1cb2139868"/>|

<br>

사이즈 기록 페이지|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/dc071e70-0494-4d28-84b8-d14d4cb25a76"/>|

<br>
<br>

## 주요 기능
AI 스타일 자동 제공 기능|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/386c6288-a578-49e3-90ff-81d21df431f6"/>|

* When a user uploads an image file of clothing, the system retrieves the image address from Amazon S3.
* Then, the image is read and analyzed by a trained model using Teachable Machine to automatically classify the style of the clothing.
  This allows the user to immediately obtain information about the style of the clothing.

<br>

기상 데이터를 기반으로 한 AI 패션 추천 기능|
---|
<img src="https://github.com/dydgjs200/Weatherable_front/assets/121750853/2122ec2e-b35c-4eab-94a3-76a46db07421"/>|

* Based on real-time GPS location, weather temperature data, and information about all items in the user's wardrobe, the system sends this data to GPT.
  GPT then generates responses based on its implemented logic.
* These text responses are processed to suggest outfits by applying them to the items in the wardrobe and randomly selecting items that meet the specified conditions, providing outfit recommendations tailored to the current weather.

