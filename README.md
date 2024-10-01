# 게시판 프로젝트


## 주요 기능
- Auth
  - 회원가입
  - 로그인
  - 로그아웃
  - 회원탈퇴
- 게시판
  - 게시판 등록/수정/삭제
  - 태그 등록/수정/삭제
  - 댓글, 대댓글 등록/수정/삭제

## DB 설계
<img width="1020" alt="image" src="https://github.com/user-attachments/assets/1f6b3bfb-baae-40d9-a105-4b46b478e7b4">

- 1:N 관계
  - category - post
  - post - comment
- N:M 관계
  - post - post_tag
  - tag - post_tag