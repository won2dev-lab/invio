## 서비스 구성

| 서비스                  | 포트   | 설명           |
|----------------------|------|--------------|
| api-gateway          | 8080 | API 게이트웨이    |
| user-service         | 8081 | 회원/인증        |
| trade-service        | 8082 | 매수/매도/체결     |
| stock-service        | 8083 | 실시간 시세/종목 조회 |
| portfolio-service    | 8084 | 포트폴리오        |
| notification-service | 8085 | 알림           |
| payment-service      | 8086 | 구독/결제        |
| ai-service           | 8087 | AI 분석/뉴스 요약  |

## 기술 스택

- Java 21
- Spring Boot 3.5.0
- Spring Cloud 2025.0.0
- Kubernetes
- Kafka
- Redis

