2022-12-20-tue
1. 코테<br>
BFS 응용문제 잘 못풀길래.. <br>
BFS를 연습했다.
나 일단 이번주 BFS뿌시기 간다..<br>
2. SW아카데미<br>
 그리고 WAS, RMI, SpringBean, kafka.. 접했다. kafka가 좀 어려웠다. 오와 그래도 'kafka를 사용하는 이유'에 초점 맞춰서 잘 공부하면 중요한 개념들을 얻을 수 있을 것 같다. <br>
RMI랑 SpringBean도 몇번 다시 읽어보면서 내가 설명할 수 있을 정도로 공부하면 좋겠다.<br>
Web Server랑 WAS 차이도 공부했다.<br> 사실 예전에 봤던 것들인데, 혼자 공부할 때는 그냥 아그렇구나용용 하면서 넘어간 부분인데, 강사님께서 강조를 많이 하셔서 다시 찾아가며 공부했다. 역시 구멍난 부분이 많았다..<br>

<br>
<br>
2022-12-21-wed

1. 코테<br>
오늘도 BFS!!<br>
좀 기억해야 할 것... 처리대상 노드는 일단 q에 넣는 거라서 첫시작도 q에 넣고가자는 생각을 합시다 & q size를 현시점에 고정시켴서 일단 쭉 처리하고, 다시 size checking해서 또 q size만큼 쭉 돌고.. 이렇게 끊어서 생각할 줄 알기!<br>
2. Figma<br>
오늘 figma를 처음 써봤다! 우리 팀 프로토타입을 figma로 만들어야 한다. 너무 좋은 툴 알게되어서 신난다. 일찍 알았음 좋았을텐데! 아무튼 기분좋음! 난 marker 부분을 만들어야 한다.<br>
우리 팀 파이팅!!<br>
3. OS<br>
OS가 프로세스 관리하는 거랑 쓰레드.. 공부했다. 지난학기에 OS수업 들었던 게 새록새록.. 많은 CS분야 중 OS는 정말 다시 꼼꼼히 공부하고싶다. 간단히라도 정리해서 이번주 안에 TIL 하나 올려야겠다.<br>

<br>
<br>
2022-12-22-thu

1. OS의 Memory Management간단히 TIL함! (정리 미완료)

    [**링크 : Memory ManageMent**](https://github.com/yyhh314/TIL/blob/main/OS/memory_management.md)
2. Docker실습 하면서 내가 네트워크 지식이 많이 모자라구나 느꼈다. 하긴!! 각잡고 배운 적이 없으니까.. 아무튼 Docker라는 것을 접해봤는데, 중요하다니까 잘 다뤄보고싶다.

<br>
<br>
2022-12-23-fri

*컴포넌트*<br>
>모든 것이 오픈소스는 아니라서 코드재사용한다는 것은 은근 제약이다. 그래서 컴포넌트에 대한 이해가 필요 : 코드없이도 상속, 재활용이 가능하다는 idea<br>
소스코드없이 컴파일된 결과물을 기반으로 재활용이 가능하다는 것!<br>
Spring은 컴포넌트 기술 집약체다.<br>

*분산컴포넌트*<br>
>그런 재사용을 하려면 원격 호출이 필요 (+ 네트워크 개념)<br>
(백엔드에서 제일 머리아픈) 분산컴포넌트 기술 등장! '분산'이 들어가면 네트워크 개념이 들어간 것이다. 코드를 원격호출해서 결과를 받아와야 한다든지 그런 개념 등장한 것이다. <br>
분산컴포넌트를 구현한 것이 MS에서는 DCOM이고 Java에는 EJB 등등.. 근데EJB 다음단계로 Spring Bean으로 분산컴포넌트 기술이 정리됨!<br>
cf. Spring은 이런 분산컴포넌트 기술에 묘하게 DI를 끌고 들어와서, DI를 반드시 하게 된다. DI는 결국 OOP가 발달한 것이다. 즉 DI는 객체지향.. <br>
이런 거! 배웠다. 따로 정리하자.

*기타등등..*
>결국 궁극적인 스프링 삼각형을 이루려면 POJO가 된다. 스프링은 약간 유사종교성을 가지고 있는데 (<-강사님 말) 궁극적인 열반.. 해탈.. 이것이 POJO인 것임. 참고로 이 수업은 DI까지만 함<br>
완벽한 객체지향을 위해 DI, AOP로 코드를 짜고, 그렇게 안한(못하는) 것들은 DI로 포장을 하면 된다(=> PSA). 우리가 집중할 80%는 DI다.<br>

<br>
<br>
2022-12-26-mon

*Spring 관련 내용을 학습함*
>5달 전쯤에 인프런(김영한선생님) 강의에서 공부했는데, 다시 유사한 내용을 들으니까 더욱 정리가 잘 되어서 좋았다. 핵심부분 정리해서 업로드 완료!<br>
그나저나 좀 밀렸다. 이거 하루종일 해야 진도 커버 되겠는데..<br>
SW아카데미에서 살아남으려면 좀 더 부지런해야겠다..!<br>

*네트워크*
>오늘부터 네트워크 수업을 듣는다. 학부에서 아직 안 들은 과목이 네트워크, 데이터통신이라 더 궁금하고 배우고싶다.<br>
[**정리 : OSI 7 layer**](https://github.com/yyhh314/TIL/blob/main/Network/OSI_7_layer.md)



<br>
<br>
2022-12-27-tue

그동안 Spring 프로젝트의 속성정의파일 application.properties는 그냥 생각없이 쓸거있음 쓰면서 사용하고 있었는데, 오늘 좀 자세히 알게되었다. 

그리고 application context에서 제공하는 주요기능 중 하나인 Environment를 통해 속성관리를 할 수 있음을 알았다. 또한 스프링 환경은 profile과 property를 통해 바뀐다. 그렇다 오늘은 profile과 property 관련 실습을 진행했다.

*스프링 속성을 정의하는 파일*

* .yaml <- 요거 가끔 보고 궁금했는데 오늘다뤄봄!
* .properties

여기에 정의된 속성값들을 꺼내볼 수 있다는 걸 알았다. @Value 를 통해 주입시켜보기도 했다. @Value로 환경변수도 꺼내볼 수 있다는 걸 알고 신기했다!

또.. Springboot만 지원하는 그런 기능들이 있는데, 기본적으로 실습프로젝트는 Spring 프로젝트다. @Enable어쩌구 이런걸로 Enable시켜서 사용해보기도 했다. 굉장히 다양한 실습을 했고.. 이런게 있구나를 알게되어서 좋다.


<br>
<br>
2022-12-28-wed

>오늘 하루종일 ObjectInputStream 관련된 부분 문제해결했다.<br>
**블로그에 정리 : [링크](https://splendidlolli.tistory.com/549)**<br>



<br>
<br>
2022-12-29-thu

*네트워크 실습 : HTTP srever using TCP socket*
> 간단히 같은 팀원이 띄워둔 서버로 접속해보고, 내 서버로 접속하는 패킷을 캡쳐도 해봤다.

*Spring logging 실습*
> 와 log file을 이렇게 만들어서 관리할 수 있구나!<br> 나는 다른 개발자분들이 막 운영서버 로그확인해보니까 뭐가 찍혀있다 어떡하냐 이런 말씀 들을때마다 우와 나는 로그확인이라는 걸 언제 해보게 될까? 싶었는데..<br> 개발/운영하면서 이렇게 file로 맘껏 관리할 수 있다는 걸 알고 log랑 좀 친해진 느낌이 든다.

*Selenium 사용해봄*
> 진짜 신기했다. 누가 Selenuim 쓰시다가 문제생긴다고 질문하셔서 해결하느라 처음 사용해봤는데, 재밌더라!!<br>
뿌듯한 건 문제 해결도 완전히 해드렸다는 거 ~ㅅ~..<br>
나중에 직접 써보고 싶다.


<br>
<br>
2022-12-30-fri

*Socket 실습 & TCP/IP*

>지난 학기에 컴프2 들으면서 socket통신을 통한 실시간 채팅 android app 구현 과제를 했던 기억이 났다. 이번에도 그런 실습을 했다. python으로 간단하게! gui 추가하는 부분도 있는데, 일단 하지 않았다. 주말에 후순위로 시간나면 해야지!<br>
개인적인 목표 : Socket통신 프로그램을 다른거 몇개 더 만들어보고, 능숙하게 설명할 줄 알자.<br>
추후 꼭 완성작 올리겠음!<br>
**정리 : [HTTP 통신과 Socket 통신](https://github.com/yyhh314/TIL/blob/main/Network/HTTP_and_Socket.md)**

*[DB] Transaction, ACID*
> 야호~~
[**정리 : Transaction_ACID**](https://github.com/yyhh314/TIL/blob/main/DB/Transaction_ACID.md)

<br>
<br>
2022-12-31-sat

2023-01-01-sun

2023-01-02-mon

2023-01-03-tue

2023-01-04-wed

2023-01-05-thu

2023-01-06-fri

2023-01-07-sat

2023-01-08-sun

2023-01-09-mon



<br>
<br>
2023-01-10-tue

spring jdbc 실습

반성 : 지난주는 너무 정신없이 지나갔다. 이번주는 다시 원래 텐션 되찾기로 하겠다. 


<br>
<br>
2023-01-11-wed

[**블로그에 정리1 : mysql 서버 상태 확인하기(show status) | db connection 전후 Threads 관련 상태변수 확인**](https://splendidlolli.tistory.com/560)

[**블로그에 정리2 : \[JDBC\] DB Connection 얻어 query 실행 | DriverManager과 DataSource를 통하여 (+ Connection Pool 개념)**](https://splendidlolli.tistory.com/561)

▶ JDBC와 JDBC driver?

- JDBC는 DB를 사용가능케 하는 java의 api이며

- JDBC driver는 JDBC api가 특정 DBSM에 연결할 수 있게 하는 driver임!

    DBSM에 따라 적절한 driver를 설치해 사용!

   

▶ DB 연결한다는 것은 Connection 객체를 얻는 것임

- Connection 객체를 얻는 방법으로 DriverManager, DataSource를 공부!

- 이때 Connection Pool 개념을 학습하게 됨!

 

▶ Connection을 받아온 뒤 query를 날리는 과정을 공부함

- connection을 통해 statement를 만들고, statement를 필요에 따라 잘 세팅한 뒤 query를 시행할 수 있음!

[**블로그에 정리3 : JdbcTemplate | 왜 Jdbc 'Template'인가? 어떤 동작을 하는가?**](https://splendidlolli.tistory.com/563)

▶ JdbcTemplate을 간단히 관찰해보았다.


<br>
<br>
2023-01-12-thu

NamedParameterJdbcTemplate 실습
> 쿼리에 값을 전달할 때 ?로 표기되는 placeholder를 사용하지 않고 이름 기반으로 파라미터를 전달할 수 있게 기존 코드를 변경해봄

> 순서 말고 키로 매핑되므로 index 실수를 줄일 수 있다. 이때 매핑을 위해 파라미터 Map을 함께 전달했다. 

> 실습때 RowMapper도 처음 사용해봄. 말그대로 Row Mapper인 것 같다. ResultSet이랑 index가 들어오면 거기 해당하는 객체 반환해주는 Row Mapper! findAll처럼 조회하는 query()에 sql문과 RowMapper를 전달했었음!

Spring AOP
> 이 실습은 여러번 보고 익숙해져야겠다. 덜 소화했다.


<br>
<br>
2023-01-13-fri

오늘은 역량평가를 봤는데.. 공부 열심히 해야겠네 김옌...


<br>
<br>
2023-01-14-sat


<br>
<br>
2023-01-15-son

히루종일 팀개발만 함!

[**블로그에 간단히 글도 하나 씀 : docker에 띄운 mysql 접속**](https://splendidlolli.tistory.com/565)

<br>
<br>
2023-01-16-mon

오늘도 팀프로젝트에 집중하면서 여러가지를 고민해볼 수 있었음

- 특정 도메인과 관련된 여러 Dto를 깔끔하기 관리하기 위해 static 중첩 클래스 구조를 두는 방식
- Dto에 Getter를 둬야지 Json으로 변환될 수 있다는 것 : ResponsEntity가 매핑해주는 과정을 공부하면 된다! [**기록**](https://splendidlolli.tistory.com/566)
- 논리적인 상속 구조를 join 전략으로 DB에 나타냈었는데, 그래서인지 개발하면서도 계속 DB 설계 관련된 걸 찾아보게되었다. 김영한선생님의 "자바 ORM 표준 JPA 프로그래밍" 이거 공부하고 싶어졌다. 여기 고급 매핑 정보들이 나오는데, 내가 참고한 포스팅들이 다 이걸 기반으로 한 글이더라고..


Spring AOP좀 공부+정리해뒀다

[**블로그 글 : Spring AOP 쉽게 이해하기 | 그리고 간단한 예제코드**](https://splendidlolli.tistory.com/567)


<br>
<br>
2023-01-17-tue

transaction 실습



<br>
<br>
2023-01-18-wed

web 구조 오버뷰


<br>
<br>
2023-01-19-thu

> 우리가 Springboot를 쓰면 Dispatcher Serlvet, HandlerMapping, HandlerAdapter, ViewResolver 이런 거 다 셋업할 필요가 없다. 그냥 Controller만 작성하면 원하는 결과가 나오기 때문이다. 하지만 너무 자주 사용하고 있는 Controller의 http 요청 처리 흐름을 알고 쓰는 것이 적절한 태도이기 때문에 포스팅해보았다.

[**블로그 : Spring MVC | Controller는 어떻게 요청을 처리하는 걸까? | Controller와 Servlet**](https://splendidlolli.tistory.com/570)


<br>
<br>
2023-01-20-fri

WebApplicatoinContext
- ApplicatonContext 관련된 새로운 개념 인지 : servlet application context & root applicatoin context
- 여러 개념이 확실히 정돈되지 않음 <br>=> 시간 내서 다시 정리해야겠다. 꽤 복잡하게 느껴졌다. 

REST API
- 중요한 것은 "균일한 인터페이스" : URI로 지정한 리소스에 대한 조작을, 통일되고 한정적인 인터페이스로 수행하는 아키텍처 스타일을 말한다. 이 아키텍처 스타일이라는 것을 이해하기 어려우니까 "얘가 rest인지 아닌지 말해주는 모델"을 richardson님께서 만드심! maturity model로 설명되었음. 

REST API를 정말 겉핥기로만 알고 있었는데.. 좀 더 알게된 날이다.
- 평소에 그냥 Controller 리턴값으로 List\<Customer\> 이런식으로 편하게 사용을 했었다. 그럴 수 있었던 이유가 MessageConverter가 잘 처리해주기 때문이란 걸 알게 됨! 

SPA(Single Page Application)
- URL 변경시 특정영역만 렌더링된다. DOM 조작을 통한 렌더링이 이루어진다. 단일페이지가 아닌 일반 웹 애플리케이션은 URL 변경시 모든 페이지가 다시 렌더링된다. js, css, layout 등을 다시 서버로 요청하게 된다. (참고: layout 요청시 템플릿엔진을 통함! 아하 그랬던거구나)
- SPA 기반 세션관리 <br>└>  확실히는 모르겠음! 공부 필요하다. 아주 대충 말하자면 : <br>사용자 데이터 모델을 저기 프론트쪽에서 일부 다뤄줄 수 있게 된다. 매번 세션에 정보를 (메뉴정보 등) 넣어주면 세션이 점점 커지는데, 그 사용자데이터모델 일부를 브라우저의 메모리가 들고 있게 하는 것임. 그래서 요청을 할 때마다 모델일부에 정보가 담겨있어서, 필요할 때 요청하면 그 메모리에 있는걸 이용해서 처리 가능 (서버에 요청 안하고!) 이렇게 하면 url은 안바뀜. 그래서 html5의 히스토리 api라는 걸 사용하면 url을 바꾸면서 url의 히스토리를 관리할 수 있음! 아무튼 브라우저에서 뷰를 렌더링하는 개념으로 이어짐.
- jsp나 타임리프로 보았던 것과는 다르게, 서버에서 처리하지 않고 다이나믹한 렌더링을 처리.. 오키오키.. 

CORS

- 이건.. 살짝 감을 못 잡았다! 나중에 필요할 때 공부하기로!

<br>
<br>
2023-01-21-sat || 설연휴

2023-01-22-sun || 설연휴

2023-01-23-mon || 설연휴

<br>
<br>
2023-01-24-tue

영속성 컨텍스트

- 1차 캐시
- 처리 지연

> 단일 트랜잭션 실습 중 로그를 확인하다가 의문이 생겼고, 결국 영속성 컨텍스트의 '1차캐시' 개념을 이해하게 됨! '처리 지연' 특징까지!

> [**블로그에 정리 : [JPA] Entity는 영속성 컨텍스트에 저장/조회한다!**](https://splendidlolli.tistory.com/573)


<br>
<br>
2023-01-25-wed

**1. H2 db를 사용하며**

JPA 실습하면서 H2 db를 사용했는데 아직도 이해가지 않는 문제를 만났다.
- 인메모리니까 스키마 자체가 날아가야 하는 거 아냐?
- 그리고 crate-drop 설정 했는데 왜 drop이 안돼?

[**블로그 링크 : [H2] Column이 drop 되지 않음 | 왜 create-drop이 안돼?**](https://splendidlolli.tistory.com/576)

문제 해결은 못했고 임시방편으로 그냥 넘어갔다. 

<br>

**2. 팀프로젝트 : nginx 이미지 서버 구축 관련 공부**

아까 2시간정도.. 1팀 모여서 공부했다. 감은 오는데 자세히는 또 모르겠고, 테스트해보려는데 사소한 부분에서 막히고 그랬다. 내일은 더 제대로 공부해보는 걸로 하자. 


<br>
<br>
2023-01-26-thu

어제 create-drop 설정 안 먹는 문제 해결했다 (바로 다음강의에서 정정해주셨다는...)

> 테스트에서 JpaProperties를 통해 jpa properties 설정을 가져왔었다. 그런데 잘못된 설정에서는 jpa의 바로 아래에 ddl-auto: create-drop 설정을 두었기 때문에 설정을 가져오지 못했던 것이다. JpaProperties를 통해 가져오려면 jpa: 아래에 properties: 아래에 두어야 가능했음!



<br>
<br>
2023-01-27-fri

1. 팀프로젝트 - 이미지서버 구축을 위한 nginx 사용법 고민 
2. [**Join 테이블 전략 (상속관계매핑) 상태에서 부모테이블 truncate하기**](https://splendidlolli.tistory.com/578)

<br>
<br>
2023-01-28-sat
<br>
2023-01-29-sun
<br>
2023-01-30-mon


<br>
<br>
2023-01-31-tue

> jpa transaction에 대한 이해


<br>
<br>
2023-02-01-wed


> jpa 학습 찔끔



<br>
<br>
2023-02-02-thu

1. 졸프 - 교수님과 첫미팅 - [참고](https://splendidlolli.tistory.com/580)

2. Spring security 개요
3. 졸프 노션 구축해둠



<br>
<br>
2023-02-03-fri

1. 팀프로젝트 - marker DTO 수정
3. express.js를 처음 사용해봄..!


    [**webserver | express.js를 경험해보았다 | 이미지 서버 구축하기**](https://splendidlolli.tistory.com/584)

4. 인텔리제이 재부팅에 대한 인식.. (환경변수 reload 때문)

     [Intellij 터미널에서 명령어가 안 먹히는 이유](https://splendidlolli.tistory.com/582)


<br>
<br>
2023-02-04-sat

대단한 현진이의 도움을 참 많이 받은 날.. 

1. 졸프 관련 정리 (일정 정리 +a)<br> 초반 계획에 대해서 친구가 많은 아이디어를 줬다.<br>
2. 친구가 https://excalidraw.com/ 추천해줘서 써봤는데..<br> 너무 좋았다! 갑자기 내 그림 퀄리티 급상승했다. <br> 감사! 그림판 빠이..ㅎㅎ
3. 친구가 면접대비 글 정리 같이하자고 제안해주었다.<br> https://github.com/back-to-the-basic/interview<br>
카페에서 방법 안내받았다. 신기했다. 정리 잘 해둬야지!




<br>
<br>
2023-02-05-son

    java.util.Properties 클래스 기능에 대한 인식


<br>
<br>
2023-02-06-mon

    - Tiled라는 프로그램을 알게 되었고, 우리 학교를 픽셀로 찍기 시작! (우리 팀 프로젝트에 필요한 이미지다) 
      재미있었다.

    - 네이버 클라우드 특강
    클라우드 산업 현황 인식
    네이버 클라우드 플랫폼 구경



<br>
<br>
2023-02-07-tue

─ 네이버 클라우드 특강

    [사용한 상품]
    ♡ Compute 상품군 (서버 생성 실습)
      - Server
    ♡ Networking 상품군 (네트워크 생성 실습)
      - VPC

    > 네이버 클라우드 플랫폼에는 다양한 상품이 있음을 인지했다.

    [실습 순서]
    VPC 생성, 서브넷생성 -> 기본적인 네트워크망 구성
    -> 서버생성 & 접속 -> 디스크 증설해보기 -> 스냅샷 기능 사용해보기

    [웹콘솔!] 
    https://www.ncloud.com/에서 서브계정으로 로그인하고 웹콘솔에 접속하여 실습을 진행했다. 
    서버 운영 방법은 크게 3가지가 있는데, 그중 내가 실습한 웹콘솔로 운영이 가장 권장된다(기능 100% 활용 가능) 
    (그밖에 CLI, API를 통해서도 운영 가능)

    [서버 생성+운영 실습]
    by 웹콘솔 / ServerImage / 유사서버
    ㄴ> 세가지 방식의 차이점도 직접 보았다. 
    * 유사서버 : 실제 서버에 있는 데이터를 가져오는 것이 아니라, 서버의 인프라 부분만 복제한다고 생각하기
    * 서버이미지로 생성한 서버 : 위 설명과 반대다! vpc, 서브넷, 서버타입.. 다르게 설정 가능!

    [디스크장착(storage) 실습]
    운영중 서버의 storage를 확인해보았다. df -h
    storage 이름 뒤에 1, 2 숫자가 붙은 것은, 파티션이다. 
    디스크는 /dev/xvda1과 /dev/xvda2가 있었다.
    xvda 디스크의 1번은 boot파티션이었고, 2번은 현재 리눅스의 메인루트볼륨이었다.
    이렇게 서버에 장착된 storage(disk)들의 상태를 보기 위해 fdisk -l 명령을 입력했다. 리스트를 확인했다. storage 추가를 더 한다면 현재 있는 xvda에 이어서, xvdb, xvdc.. 이런 네이밍이 될 거라 하셨다.
    추가로 storage를 등록했다. 파티션은 자동으로 등록되어지는 것이 아니라 직접 등록해 주어야 한다. 또한 기본적으로 storage를 사용하려면 파티션을 설정해주어야 한다. 파티션을 추가해보았다. xvdb에 파티션 추가는 다음 명령 순서대로 가능했다 fdisk /dev/xvdb -> n -> 파티션타입 고르기 -> 파티션넘버 고르기 -> first sector 설정 -> last sector 설정 -> 세팅완료! 저장(w)
    그리고 fdisk -l로 확인해보면, 추가된 파티션을 확인 가능하다. 
    storage를 처음 만들면 포맷을 해야 한다. ext4라는 파일시스템으로 포맷을 진행했다. mkfs.ext4 /dev/xvdb1 를 통하여 파티션 포맷 완료! 이제 서비스에서 이용이 가능해졌다. 
    파티션을 실제 폴더로 마운트해보자. data라는 폴더를 만들었고, 마운트하는 순간, data 폴더는 storage가 된다. data로 우리가 만든 storage를 마운트하는 것이다!
    mount /dev/xvdb1 data
    이렇게 디스크장착 실습 완료!

    > [오토스케일링] : 클라우드의 가장 큰 장점인 유연한 인프라 구축을 가능케 한다는 것을 이해!




<br>
<br>
2023-02-08-wed

─ 네이버 클라우드 특강

    [사용한 상품]
    ♡ Database 상품군 (DB서버 생성 실습)
      - Cloud DB for MySQL
    ♡ AI api 상품군
      - nShortURL
    ♡ Application Services 상품군
      - Cloud Outbound Mailer

    [현황]
    클라우드 DB로 전환되는 시장에 있다!
    하이브리드 클라우드! 별도 보관이 필요한 데이터만 private cloud에 저장, 나머지는 public cloud에 저장!
    대기업은 90%, 중견기업은 76% 이상이 이러한 멀티클라우드 도입을 선호


    [DB서버 생성과 접속 실습]
    > 생성하기 
    DB 서버 생성을 해봤다.
    생성 과정에서 이 DB에 접근할 수 있는 HOST(ip)도 지정할 수 있다. (모두 다 들어올 수 있게(any) 하고싶으면 %로 지정)
    여기서 %로 하더라도, 추후에 별도로 ACG로 다시 접근을 제한해줄 수 있다.
    > 접속하기
    mysql 서버 생성 완료 후, mysql workbench를 통해 방금 만든 cloud DB에 접속해보았다.
    cloud DB서버에 public 도메인을 신청하면, 외부에서 DB서버로 접근할 수 있다.
    외부에서 통신하는 데이터는 네트워크 사용량으로 과금이 된다.
    > ACG
    DB서버를 만들면 ACG가 자동생성된다. Access Control Group이며, 아래 설정을 하게 된다.
      Inbound 규칙  : 프로토콜, 접근소스, 허용포트 (서버에 접속 가능할 ip를 지정!)
      Outbound 규칙 : 프로토콜, 목적지, 허용포트 

    > 백업/복원 실습, fail-over 테스트도 진행!

    *참고: 새로운 ssh 접속 프로그램을 이용해봄 (MobaXterm)

    



<br>
<br>
2023-02-09-thu

 ─ 네이버 클라우드 특강

    [사용한 상품]
    ♡ Management & Govermance 상품
      - Cloud Insight (Monitoring)
      - Sub Account
      - Cloud Log Analytics (CLA)
    ♡ Developer Tools 
      - Terraform을 이용한 naver cloud infra 구축 실습
        terraform VPC 구성 및 리눅스서버 자동생성

    [Cloud Insight (Monitoring) 실습과정]
      1. 새로운 VPC 생성
      2. 그 Server에다가 상세모니터링, 네트워크 모니터링 신청을 해두면
      3. 해당 VPC에 대한 커스텀 대시보드 만들어서 (Monitoring 상품에서 Dashboard) Widget등록시 데이터 설정 단계에서 Target(감시대상)서버를 해당 서버로 할 수 있다. 그리고 '메트릭'을 SERVER/savg_cpu_used_rto 선택하여 항목추가를 해봤다. 그럼 해당 데이터(그래프)를 확인 가능!
      4. 서버 부하 주고 알림받아보기! Notification Recipient에 통보대상자 김예은씨를 등록
      5. Configuration의 Event Rule에서 감시할 이벤트 룰을 적절히 설정한다. 오늘은 CPU 부하에 대해 Email과 SMS 알림이 오도록 설정해봤다.
      6. CPU 부하 발생시키기 -> 김예은씨에게 알림 간다!!
      * 참고: CPU에 부하 발생시키기 : 해당 서버에 ssh 접속해서 -> EPEL 레포지토리를 설치했다 (yum install epel-release) -> 부하 tool을 설치했다 (yum install stress) -> CPU 부하를 진행 (stress -c 2)

    [Sub Account 실습 과정]
      서브계정 만들고 권한 제한을 줘봤다.
      콘솔 창 접근 제한 등!

    [Cloud Log Analytics(CLA) 실습 과정] 쉽고 간편한 로그조회!
    1. CLA -> Subscription에서 CLA 구독 신청!
    2. CLA -> Management에서 해당서버에 로그수집 설정!
       네이버에서는 다양한 Log Template를 제공한다.
       실습때는 SYSLOG랑 APACHE Log Template을 추가했다.
       다음의 로그 경로가 자동 등록되었다.
        Syslog의 log경로: /var/log/messages
        Apache의 log경로: /var/log/httpd/error_log
                          /var/log/httpd/eccess_log
        커스텀 로그도 물론 직접 등록 가능!
    3. 해당서버에 Agent 설치하는 방법이 안내된다. (ssh접속 후 명령어를 통해 설치했음)
       참고) 해당 서버에서 Apache 로그를 찍어보려는 상황인데 Apache 설치가 안되어있는 상황이라 yum install httpd -y 해주었다.
    4. 해당서버의 공인ip로 웹브라우저로 접속했다. 
       (잠깐! 먼저 서비스를 start해줘야 함 => systemctl start httpd.service)
       (그리고 당연히 해당 서버에 ACG의 inbound 설정도 해줘야 함. http는 80포트를 사용하기 때문에, 80포트 inbound 열어줘야 함)
    5. 새로고침 여러번 눌러.... Apache 로그가 찍히도록 했다!
    6. CLA -> Dashboard에 들어가면 로그확인 가능!!!

    * 참고 : 서버에 CLA Agent를 설치한 상황이라면, ssh콘솔통해 서버접속해서 로그를 직접 확인할 수도 있다. 
    (웹콘솔로 CLA -> Dashboard 접속할 필요 없이)
    cd /var/log/httpd/ -> cat access_log
    이런 식으로 log 직접 들어가서 확인 가능!

    * CLA -> Search 기능으로 다양하게 로그 검색도 가능




    [Terraform] 
    : Dev Tool로서 제공되는 오픈소스이다.
    : 인프라에 대한 형상관리 툴!
    : 필요성? VPC 생성 등을 클릭으로 하기 귀찮고 오래걸리고 실수가능성도 있는데, 정형화된 코드로 인프라를 쉽게  구성할 수 있다.

    [Terraform VPC 구성 및 Server(Linux) 자동 생성]
    ◆ VPC만들면 Subnet 만들고, NACL 만들고, ACG 만들고.. 많이 해야 한다.
      이런 과정을 샘플코드를 통해 한번에 생성/삭제 다 가능한 실습을 진행해보자.
    1. 루트에 mkdir terraform후 거기에 테라폼 설치함(wget ~~~~.zip -> unzip ~~~~.zip)
       그리고 mv terraform /usr/bin
       그리고 terraform version으로 설치 확인 완료!  
    2. 테라폼 예제코드를 다운받아서 사용했음
       wget https://kr.object.ncloudstorage.com/test001/Terra_20221121.zip
       unzip Terra_20221121.zip
       테라폼은 확장자가 .tf이다. 압축 풀면 main.tf, versions.tf, variables.tf가 있다.
    3. 테라폼 검증 (terraform init)
    4. 테라폼 플랜 (terraform plan)
    5. 테리폼 실행 (terraform apply) | 서버 생성되는 거 기다리면, 생성됨!
    6. 테라폼 생성 리소스 삭제 (terraform destroy)

참고<br>
Terraform 파일 예제 -  [main.tf](https://github.com/yyhh314/TIL/blob/main/Network/NCLOUD/main.tf_content.txt) and [variables.tf](https://github.com/yyhh314/TIL/blob/main/Network/NCLOUD/variables.tf_content.txt)



<br>
<br>
2023-02-10-fri

 ─ 네이버 클라우드 특강

    [사용한 상품]
    ♡ Compute의 Load Balancer

    ■ NAVER CLOUD 핵심 서비스로 간단한 웹 애플리케이션 만들기
    ㄴ> "안전성 & 고가용성을 확보한" by Load Balancer!

    [LoadBalancer 실습]
    1. VPC 생성
        Subnet 생성
            lb, private, public subnet 생성!
        Network ACL설정
            lb, private, public nacl을 생성!
            ICMP, TCP에 대한 inbound와 outbound 규칙을 설정!
                ex)
                웹 접속 할거라서 public nacl의 inbound에는 80포트를 지정했어야 했다.
                ssh접속도 할 거라서 22포트도 지정했다.
        그리고 저번실습때 사용한 Init Script를 사용하여 웹(httpd)또한 서버에 세팅했다.
    2. LoadBalancer의 Target Group 생성
        로드밸런서에 이 Target Group을 지정하게 된다.
        프로토콜, 포트, Target유형, 연결 로드밸런서, VPC 정보를 볼 수 있다. (HTTP, 80, VPC Server)
    3. LoadBalancer 생성 (application loadbalancer!!)
        대상 vpc를 지정 
        LoadBalancer subnet을 선택 
        리스너를 설정(프로토콜과 포트! http, 80을 설정)
        Target Group을 선택
        -> LoadBalancer 생성 완료!

    웹 접속시 서버 계속 바뀌는 것을 확인했다. 부하분산이 일정하게 되고 있는 모습 봄.
    Auto Scaling Group도 만들어서 Auto Scaling 대상이 되는 서버그룹을 관리해봄. (Target Group을 로드밸런서 타겟으로 지정)

    아ㅠㅠ 오늘 많이 졸았는데 녹화본도 없어서 좀 어렵고 정리가 안 된다..!
    실습한 게 더 있었는데 혼란스럽네..!?
    로드밸런서 중요한 개념이었는데.. 김예은 반성해야겠다.
    Todo에 적어두고 다음에 또 만나자. 
    

    ■ NCA 자격증을 인식했다! 기출문제 몇개 풀어봄
      ㄴ> 무료 접수기회 있으니까 한번 해봐??




<br>
<br>
2023-02-11-sat

2023-02-12-son


<br>
<br>
2023-02-13-mon

    - 팀프로젝트
    - nginx


<br>
<br>
2023-02-14-tue

    - Cloud 복습 (밀린 TIL 정리)



<br>
<br>
2023-02-15-wed

    - 졸프 : 라디오 포맷팅
    - Cloud 복습 (밀린 TIL 정리)
    - 졸프회의


<br>
<br>
2023-02-16-thu

> 하루종일 놀았다.. 팀원들이랑 밥->카페->보드게임!

> 유은님께 COUP라는 겜을 배웠는데 와 진짜 이거보다 재밌는 보드게임 없다..


<br>
<br>
2023-02-17-fri

> 졸프 미팅 준비 & 조교님과 미팅 => 정말 최고야..

2023-02-18-sat

2023-02-19-son


<br>
<br>
2023-02-20-mon

> 졸프 정리함

> tiled : 지도 그림


<br>
<br>
2023-02-21-tue

> tiled : 학교 지도 그리기


<br>
<br>
2023-02-22-wed

> tiled : 하루종일 지도만 그렸다 (은근 잼)

<br>
<br>
2023-02-23-thu

  
>졸프 : 백엔드 구축 시작 : 기능추가 : mp3 -> DB

