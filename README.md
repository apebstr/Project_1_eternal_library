# Project_1_eternal_library
### 1. 프로젝트 제목/주제
#### 영원한 도서관
: 전자도서관 홈페이지 구축 / 대출도서기반 도서추천 기능 구현

### 2. 제작 기간 & 참여 인원
- 2023.02.27~2023.03.26 (28일)
- 6명 (프론트엔드 1명, DBA 1명, 백엔드 4명)

### 3. 사용한 기술
- HTML5, CSS3, Javascript, Java11, JSP
- Spring, MyBatis, Tiles 
- oracle sql developer
- 큐레이팅 : Python

### 4. ERD             
![image](https://github.com/apebstr/Project_1_eternal_library/assets/117328602/3f3c9574-b762-40d8-a17a-ef552fd2a595)
     
### 5. 담당 기능 (백엔드)
#### 1) 주요 담당 기능
- 데이터 수집 : DB에 사용할 소장도서 목록 수집 (도서관정보나루 API + 카카오 도서 API)
- 공지사항 게시판
- 신규도서 추가 기능 구현 (카카오 도서 API + 서지정보ISBN API)
- 대출도서기반 도서 큐레이팅 작업 (도서 줄거리 형태소 분석 및 코사인 유사도로 상관관계 분석하여 유저가 읽은 도서와 가장 유사한 도서 10개 추출, 유저가 읽었던 도서는 제외하는 쿼리를 이용해 최대 5권까지 추천) 
#### 2) 담당 페이지
① 유저페이지
- 공지사항 게시판 (목록, 게시글 검색, 첨부파일, 이미지첨부, 이전글/다음글)
- 도서 신청 (AJAX를 이용해 카카오도서API 검색내용 조회하여 도서신청서비스 구현)
- 맞춤 도서 추천(큐레이팅)

② 관리자페이지
- 공지사항관리(목록, 검색, 글쓰기, 수정, 삭제, 이미지,첨부파일 처리, 고정글)
- 도서관리(신규도서 추가, 상세, 도서검색)
- 도서신청관리(유저신청도서 처리)

### 6. 기능 상세보기
1) 담당기능 소개(PPT/31p) : https://docs.google.com/presentation/d/1x96lYjCvs3f4IdoX-33SRAdCKM8bAZms/edit?usp=sharing&ouid=114692742484831808194&rtpof=true&sd=true
2) 전체 프로젝트 소개(PPT/64p) : https://docs.google.com/presentation/d/1wqCvwK_Chx8V1zrl68ORWGjAQYmLu-pV/edit?usp=sharing&ouid=114692742484831808194&rtpof=true&sd=true
