## XMLHttpRequest

- 메서드 open()은 새로 생성된 요청을 초기화하거나 기존 요청을 다시 초기화

1. 형식

   open(method,url)

   open(method, url, async) 

   open(method, url, async, user)

   open(method, url, async, user, password)

   

2. url 

   요청을 보낼 URL을 나타내는 문자열

3. async 선택과목

   true작업을 비동기식으로 수행할지 여부를 나타내는 선택적 부울 매개변수(기본값은 )입니다. 이 값이 false이면 send()응답을 받을 때까지 메서드가 반환되지 않습니다. 인 경우 true이벤트 리스너를 사용하여 완료된 트랜잭션에 대한 알림이 제공됩니다. 속성이 이면 true여야하며 그렇지 않으면 예외가 발생합니다

4. user 선택 과목

   인증 목적으로 사용할 선택적 사용자 이름입니다. 기본적으로 이것이 null값입니다

5. password 선택 과목

   인증 목적으로 사용할 선택적 비밀번호입니다. 기본적으로 이것이 null값입니다.



​      https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/open



