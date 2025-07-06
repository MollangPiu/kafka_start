### :program: 실행 명령어 ( main 서버 )

```bash
nohup java -jar kafka_main.jar --server.port=8081 > kafka_main.log 2>&1 &
```

### :program: 실행 명령어 ( sub 1 )

```bash
nohup java -jar kafka_sub1.jar --server.port=8082 > kafka_sub1.log 2>&1 &
```

### :program: 로그 확인하기

```bash
tail -f logs/kafka_sub1.log
```
