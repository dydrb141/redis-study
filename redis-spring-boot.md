---
description: IntelliJ에서 Spring boot와 Redis를 연동해서 Hello World를 사용
---

# Redis Spring-boot 연동

## Intellij에서 스프링 부트 프로젝트 신규 세

1. 1.  File &gt; New &gt; Project 선택
2. Spring Initializr 선택
3. Group과 Name을 프로젝트에 맞게 설정
4. 추가할 Dependency 를 선택 해줌 

   1. srping-boot-starter-data-redis
   2. spring-boot-starter-web
   3. lombock
   4. spring-boot-starter-test

5. 프로젝트 생성

### Redis연동

{% code title="application.properties" %}
```text
spring.redis.host=127.0.0.1
spring.redis.password=
spring.redis.port=6379
```
{% endcode %}





