1. 301, 303 요청을 하였을때, 왜 httpstat.us 페이지의 메인으로 redirect될까?    
자동 리다이렉트 및 GET으로 변함, GET과 새로운 url로 다시 요청, 이때 메세지를 제거하고 새로운 페이지 응답하기 때문
2. 401 요청을 하였을 때, 네트워크 탭의 상태를 보고 어떻게 인증해야 하는지 www-Authenticate 헤더를 기반으로 설명해보자.    
인증: 로그인    
인가: 권한부여(인증이 있어야 인가가 있음)
3. Google에 “Hello”를 입력하여 결과물을 보고, 네트워크 요청 탭에서 캐시 관련 정보가 어디에 저장되어 있는지 분석하여 보자.     
헤더 섹션에서 캐시 메커니즘, 유효 기간, 고유 식별자, 수정 시간 등을 확인할 수 있다.
4. 더 알고 싶은 상태코드를 직접 체험해보고, 해당 상태코드에서 진행한 요청 헤더, 응답 헤더를 직접 정리하여 분석해보자.    
요청:    
https://httpstat.us/404    
요청 메서드:
GET    
상태 코드:
404 Not Found    
원격 주소:
20.40.202.3:443    

응답:     
Content-Length:
13    
Content-Type:
text/plain    
Date:
Tue, 04 Jun 2024 13:23:29 GMT    
Request-Context:
appId=cid-v1:3548b0f5-7f75-492f-82bb-b6eb0e864e53    
Server:
Kestrel     
Strict-Transport-Security:
max-age=2592000    
