# Redis설치

## Mac에서 Redis 설

 mac에서 redis 띄우는법은 간단하다 

```
$ brew install redis
```

### Mac에서 서비스 실행, 중지, 재시작

```text
$ brew services start redis
$ brew services stop redis
$ brew services restart redis
```

위 redis를 start한 후  아래 명령어를  실행해야 레디스가 구동 됨.

```text
$ redis-server
```



