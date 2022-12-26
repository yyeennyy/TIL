# IoC
**제어의 역전**<br>
 자기가 사용할 객체를 자기가 생성안하게 해야 한다. 이는 곧 결합도를 느슨하게 하기도 함. 

실습에서는 IoC Container로 사용할 클래스인 OrderContext를 두었음. 여기서 객체들의 의존관계 설정이 이루어지게 하고, 객체 생성과 파괴를 모두 맡겼음. 

스프링에서는 이러한 IoC Container를 제공해줌. 그것이 바로 ApplicationContext임!(=> Interface이다)<br>
 이것은 BeanFactory를 상속하여 IoC관련 제어를 가능케 함.<br>
Bean은 IoC Container에서 관리되어지는 객체를 의미함.<br>
스프링의 ApplicationContext는 실제 만들어야 할 정보를 Configuration Metadata로부터 받아옴(=> 객체 도면으로 보면 된다)<br>
 이 Config Metadata는 XML기반으로 작성하거나 Java파일로 작성하는데, 요즘은 Java기반 설정을 많이 함. 이때 AnnotationConfigApplicationContext라는 구현체를 사용하면 됨.<br><br><br>




# Dependency
제어의 역전을 이야기할 때 빠지지 않은 Dependency Injection!! 일종의 IoC를 구현하는 패턴이라고 보면 된다.<br>

***참고: IoC 구현 패턴***<br>
* 전략 패턴
* 서비스 로케이터 패턴
* 팩토리패턴
* DI 패턴
<br><br>

DI 방법은 다양하지만, Spring은 **생성자 주입**을 권장함. 이유는 이러하다.
* 필요한 모든 의존관계가 초기화할 때 형성되어 null safety
* 잘못된 패턴을 찾기 쉬워짐.<br> (수많은 의존관계가 있는 생성자가 있다면, 그 클래스는 너무 많은 책임을 가진 것이기에 관심사의 분리가 필요한 상태)
* test를 쉽게 해줌.<br>
(쉽게 Mock객체를 전달하여 test가능)
* 불변성 확보<br>
(일단 Setter주입이나 field주입은 final키워드를 못 씀)<br>
(상태가 변하지않는 불변객체를 만들어지게 함 - multi thread환경에서 thread-safety!)

