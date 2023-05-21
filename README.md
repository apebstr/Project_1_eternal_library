# Project_1_eternal_library
### 1. 프로젝트 제목/주제
#### 영원한 도서관
: 전자도서관 홈페이지 구축 / 대출도서기반 도서추천 기능 구현

### 2. 제작 기간 & 참여 인원
- 2023.02.27~2023.03.26 (28일)
- 6명 (프론트엔드 1명, DBA 1명, 백엔드 4명)

### 3. 사용한 기술
- HTML5, CSS3, Javascript, Java, JSP
- Spring, MyBatis, Tiles 
- oracle sql developer
- 큐레이팅 : Python

### 4. ERD             
![image](https://github.com/apebstr/Project_1_eternal_library/assets/117328602/3f3c9574-b762-40d8-a17a-ef552fd2a595)
     
### 7. 담당 기능 (백엔드)
#### 백엔드 기능구현
1) DB에 사용할 도서데이터(소장도서목록) 수집 (도서관정보나루 API + 카카오 도서 API)
2) 페이지네이션 기능 구현
3) 공지사항 게시판 (목록, 게시글작성, 수정, 삭제, 첨부파일, 이미지첨부기능 구현)
4) 카카오 도서 API와 서지정보ISBN API를 이용한 신규도서 추가 기능 구현
- (admin) - 도서관리(신규도서 추가), 도서신청관리(유저신청도서 처리)
- (user) - 도서신청
5) 대출도서기반 도서 큐레이팅 작업 (도서 줄거리 형태소 분석 및 코사인 유사도로 상관관계 분석하여 유저가 읽은 도서와 가장 유사한 도서 10개 추출, 유저가 읽었던 도서는 제외하는 쿼리를 이용해 최대 5권까지 추천) 

### 8. 상세보기
1) 발표자료(PPT) : https://docs.google.com/presentation/d/1wqCvwK_Chx8V1zrl68ORWGjAQYmLu-pV/edit?usp=sharing&ouid=114692742484831808194&rtpof=true&sd=true


