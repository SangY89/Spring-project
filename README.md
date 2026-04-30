# 🤝 greetingSP

> Java Spring MVC 기반 구인구직 웹 플랫폼

---

## 📌 소개

기업과 구직자를 연결하는 채용 플랫폼입니다.  
기업은 채용 공고를 등록하고, 구직자는 이력서를 작성해 지원할 수 있습니다.

---

## ⚙️ 기술 스택

- **Backend** : Java 17, Spring MVC 5.2, MyBatis 3.4
- **Database** : Oracle, c3p0
- **View** : JSP, JSTL
- **Build** : Maven

---

## 🗂️ 주요 기능

- 회원 / 기업 회원가입 및 로그인
- 채용 공고 등록 · 수정 · 삭제 · 검색
- 이력서 작성 (학력, 경력, 기술, 포트폴리오)
- 이력서 지원 및 기업의 평가 기능

---

## 🚀 실행 방법

1. `src/main/java/model/setting.sql` 로 Oracle DB 테이블 생성
2. `mybatis-config.xml` 에서 DB 연결 정보 설정
3. Apache Tomcat에 배포 후 실행