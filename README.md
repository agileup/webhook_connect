# WebHookTest

1. 인증을 통해 access_token 획득
2. 해당 토큰으로 특정 repository에 webhook 생성
3. webhook callback api server 개발
4. payload 데이터 가공
5. enqueue
6. dequeue worker 개발
7. 가공된 payload 재조립
8. 테스트