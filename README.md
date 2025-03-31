# Spring Boot Hello World

간단한 Spring Boot Hello World 프로젝트입니다.

## 프로젝트 구조

- Spring Boot 3.2.3
- Java 17
- Maven 프로젝트

## 실행 방법

```bash
./mvnw spring-boot:run
```

또는 Maven이 설치되어 있다면:

```bash
mvn spring-boot:run
```

## API 엔드포인트

- `GET /`: "Hello, World!" 메시지 반환
- `GET /greeting`: "Welcome to Spring Boot!" 메시지 반환

## 테스트

```bash
./mvnw test
```

또는

```bash
mvn test
```