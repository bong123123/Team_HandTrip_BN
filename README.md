
# [HandTrip](https://github.com/SeoKai/HandTrip_BN)

### 개요
처음 사용하는 사람도 제공되는 서비스를 이용하여 여행 계획을 편리하게 세울 수 있다.

### 개발기간 : 2024.12 ~ 2025.01

### [프로젝트 상세 정보](https://github.com/SeoKai/HandTrip_BN)

---
### 담당 역할
### 기획 단계

- 시장 조사 : 유사 사이트 조사 ( [상세](https://seong-kai.notion.site/14dfcab0377c80baad01c2f7a5901ccb) )
- ERD : 리뷰, 리뷰이미지, 태그, 즐겨찾기, 사용자, 사용자 프로필 테이블 및 관계 설계
- 기능 기획 : 기능별 우선순위 정리 및 상세 구현 계획 ( [상세](https://seong-kai.notion.site/4c8cd6966f054a5d827b1437a2e56a78?pvs=74) ) , 엔드포인트 정리 ( [상세](https://seong-kai.notion.site/154fcab0377c803b83b2e7b159524940?pvs=74) )


### 개발 단계 

사용자도메인
-	사용자 프로필 : 아이디 찾기, 비밀번호 찾기 및 변경, 인증메일 및 문자 발송, 프로필 이미지 업로드, 닉네임 변경 등
-	사용자 활동 : 리뷰 수정, 삭제, 여행지 즐겨찾기 삭제

<p align="center">
  <img src="https://github.com/user-attachments/assets/4a18b669-1b16-44f8-8bf7-d9b994a032a4">
</p>

리뷰도메인 
-	리뷰 하나당 최대 3장의 이미지 업로드, 리뷰 내용 작성, 다른 사용자의 리뷰 조회
-	리뷰 이미지를 수정 시, 수정 전 이미지는 서버에서 삭제 함으로써 서버의 용량부담 최소화
<p align="center">
  <img src="https://github.com/user-attachments/assets/01cad4e4-68d7-4a07-b9f7-ef68b9d5c48a">
</p>



여행지도메인 
-	여행지 검색 : 카테고리 별 검색, 검색어를 통한 검색, 도시별 검색 및 최신순, 별점순 정렬, 여행지 즐겨찾기 추가
-	여행지 상세 : 여행지 상세 정보, 여행지 관련 리뷰, 가까운 거리의 다른 여행지 탐색
-	권환 관리 : 비회원 상태에서는 일부 서비스 이용 제한
여행지 즐겨찾기 및 조회
<p align="center">
  <img src="https://github.com/user-attachments/assets/92baaef9-1fff-4505-ae7b-a1ed9c83a1d9">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4e3ef583-353b-483a-92a1-7a95019057f5">
</p>

---

### 기술 스택

**백엔드-**
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"><br>

**프론트엔드-**
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"><br>

**데이터베이스-**
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"><br>

**테스트서버-**
<img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white"><br>
