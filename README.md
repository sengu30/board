# board

## 대표기능
- 회원 가입, 로그인
- 글 작성, 수정, 삭제
- 연관 게시물
## 사용기술
#### Language & Framework
- JAVA
- SPRING
- MyBatis
- HTML
- Javascript
#### DB & Server
- Oracle
- Apache Tomecat
#### API & Library
- Fetch
- Komoran
- Bootstrap

## 기능 설명
#### 연관게시물
- 게시글을 등록할때 형태소 분석을 통해 대명사, 고유명사, 외국어 분류
- 게시글 id, 분류된 단어, 해당 글에 나온 횟수가 DB에 저장
- 게시글 조회 시 연관 게시물 검색
- 전체 게시글 중 해당 단어가 사용된 글이 40% 이하일 때, 연관 게시물을 파악하는 단어로 사용
- 연관단어가 2개 이상 나타난 글이 연관 게시글로 검색
- 연관단어가 많을수록, 자주 언급될 수록 연관도가 높은 글로 평가

