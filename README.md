<<<<<<< HEAD
- branch 테스트
3. dependency
    1. gradle project
    2. Spring web, lombok, Thymeleaf, Validation, Spring Data JPA, Mysql Driver ㄹㅁㅇㄴㄹ
4. 서버포트
    1. 8093
5. 기본기능
    1. 기본주소 요청하면 index.html 출력
    2. MainController에서 기본주소 요청 처리
6. index.html
    1. 글쓰기 페이지(/board/save), 목록페이지(/board/) 요청 링크 있음.
7. BoardController
    1. 글쓰기 페이지 요청이 오면 글쓰기 페이지 출력
    2. 글쓰기페이지 위치 ㅁㄴㅇㄹ
        1. templates/board/save.html
ㄹㄹ
    1. 글쓰기 항목
        1. 작성자, 비밀번호, 제목, 내용
    2. 글쓰기 한 내용은 BoardSaveDTO에 담아서 컨트롤러로 전송됨.
9. BoardEntity
    1. id
    2. boardWriter
    3. boardPassword
    4. boardTitle
    5. boardContents
    6. boardDate(java.time.LocalDateTime)
    7. toSaveEntity 메서드도 설계해볼 것

# 20220117

## 엔티티 설계
ㄹㄹ
1. MemberEntity
    1. id(long), email, password, name
2. 회원 : 게시글 = 1 :N 관계
3. 회원 : 댓글 = 1 : N 관계
4. 게시글 : 댓글 = 1 : N 괸계
=======
# 진행사항
## 게시판
- 회원과 게시글간 관계 참조 완료
- 게시글 관련 내용 전부 작성 완료
- 게시글 작성, 수정 & 삭제 페이지 프론트 작업 해야함.
- 그 외 자잘한 버그 찾아서 고치기
>>>>>>> ohohohoh
