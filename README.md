# My_Community

## 요약
- **일반적인 커뮤니티에 요구되는 API들을 구현**

<br>

## 목표
- **Clean Architecture** - 의존성 관리와 추상화, 세부사항 분리
- **Clean Code** - 공통 기능 분리를 통한 중복 최소화, 하나의 함수에 하나의 기능
- **TDD**
- **에러 처리**  

<br>

## 구현 기능
- **Default**
    - **Auth**
        - 회원가입/로그인
        - 소셜로그인
        - 휴대폰, 이메일 인증
    - **관리자 페이지**
    - **Security**
        - JWT
        - 접근 제한
- **Community**
    - 팔로우
    - 알림
    - 댓글
    - 대댓글
    - 좋아요
- **Common**
    - 파일 업로드
    - 게시판

<br>

## 규칙
- **코딩 규칙**
    - 모든 변수명, 메서드명은 Camel Case
    - 클래스명은 Pascal Case
    - DB 테이블명과 컬럼명은 Snake Case
    - 모든 PK는 `${table_name}_id`
- **Git 규칙**
  - commit은 목적 하나에 하나씩
  - 개발은 develop 브랜치에서 진행
  - commit 메시지는 feat, ref, fix와 함께 내용 요약해서 작성

