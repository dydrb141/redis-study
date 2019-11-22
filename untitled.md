# Redis설치

## Mac에서 Redis 설

 mac에서 redis 띄우는법은 간단하다.

```
$ brew install redis
```

### Mac에서 서비스 실행, 중지, 재시작

```text
$ brew services start redis
$ brew services stop redis
$ brew services restart redis
```

 아래 명령어로 레디스 구동.

```text
$ redis-server
```

mac에서 설치하게 되면 Redis설정 파일은 아래 경로에 위치하게 된다.

```text
$ /usr/local/etc/redis.conf
```

cli로 커멘드에서 명령어를 실행해 볼수 있다.

```text
$ redis-cli
```

하나의 문자열 값을 가진 하나의 키를 생성 하려면 SET을 사용

```text
$ SET philosopher "socrates"
```

저장된 키 값을 읽기 위해 GET 커맨드를 사용

```text
$ GET philosopher
```

HELP 커맨드로 문법을 알 수 있음

```text
$ HEP SET
```

\`

