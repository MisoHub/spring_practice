# spring_in_practice


* spring 은 왜 사용하는가?
개발자들에게 컴포넌트 모델을 제공하고, 단순하면서도 일관성 있는 API 집합을 제공하여 개발자들이 복잡한 으용프로그램을 설계하는 동안 복잡하고 어려운 기반코드에 연연하지 않도록 도움을 준다. 

* spring 프레임워크 기본적인 영역
핵심 spring 컨테이너 : DI의존성주입. 컨테이너는 빈 생성, 구성 관리에 대한 구현을 응용 코드로부터 분리시켜준다. 
관점 지향 프로그래밍(AOP) : 보안, 로그, 트랜잭션 관리 등의 cross-cutting concers 에 대한 캡슐화 구현 
데이터 액세스/통합 : JDBC와 ORM, OXM과 JMS, 트랜잭션 기능 제공. DB와 관련된 구현을 추상화/자동화
웹 : 공용 웹 인프라 코드를 스프링 웹 , multipart 파일 업로드, 웹기반 리모팅 기능에 통합
테스트 : junit, testng 

* 의존 dependency : 의존성을 
말할 때는 항상 방향성을 부여해줘야 한다. 
(A -----> B) 라면 A가 B에 의존하고 있는 것. 
B가 변하면 A에 영향이 생긴다. (ex. A에서 B에 정의된 메소드를 호출, A가 B 객체를 사용하는 경우)
인터페이스에 대해서 의존관계를 만들어두면 인터페이스 구현 클래스와의 관계는 느슨해지면서 변화에 영향을 덜 받는 상태가 됨. 

* 주입 Injection : 
