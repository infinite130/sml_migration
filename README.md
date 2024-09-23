# SML Migration Project

## 프로젝트 소개
이 프로젝트는 기존의 **Spring MVC + MyBatis + JSP + Oracle** 환경에서 **Spring Boot + JPA + React + MySQL** 환경으로 마이그레이션하는 작업을 진행합니다. 새로운 기술 공부 및 적용과, JPA 데이터 생성 및 활용 위주로 진행되었습니다.

## 기술 스택
- **Backend:**
  - Java 17
  - Spring Boot
  - Spring Data JPA
- **Frontend:**
  - React
- **Database:**
  - MySQL
- **Build Tools:**
  - Gradle
- **Security:**
  - Spring Security
  - JWT (JSON Web Token)

## 마이그레이션 작업
1. **Spring MVC에서 Spring Boot로 마이그레이션**
   - XML 기반 설정을 Java 기반 설정으로 변경.
   - 기존 MyBatis를 JPA로 전환.

2. **MyBatis에서 JPA로 전환**
   - VO 및 Mapper 파일을 JPA `Entity`와 `Repository`로 변환.

3. **JSP에서 React로 마이그레이션**
   - JSP 기반의 UI를 React로 전환하고, REST API를 통해 백엔드와 통신.

4. **Maven에서 Gradle로 마이그레이션**
   - `pom.xml`을 `build.gradle`로 전환.
   - Gradle의 의존성 관리 및 빌드 설정 최적화.
