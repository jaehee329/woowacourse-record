# 우아한테크코스 활동 기록
우아한형제들 산하의 교육 기관으로 10개월 간 **프로젝트 운영**을 경험하며 **2주 간격의 미션**을 기반으로 학습합니다.<br>
미션의 각 단계마다 새로운 요구사항을 구현합니다.<br>
각 미션은 **페어 프로그래밍**, 선배 개발자 혹은 크루 간 **코드 리뷰**를 바탕으로 진행됩니다.<br>

<br>

## Level 4 (2022.08.29 ~ 2022.10.25)
### 미션
| Project | 목표 | Repository | 1단계 PR | 2단계 PR | 3단계 PR | 4단계 PR |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|레거시 코드 리팩터링 <br>|의존성 방향 수정<br> 모듈 분리| [Repository](https://github.com/jaehee329/jwp-refactoring)| [1단계 PR](https://github.com/woowacourse/jwp-refactoring/pull/460) | [2단계 PR](https://github.com/woowacourse/jwp-refactoring/pull/600) | [3단계 PR](https://github.com/woowacourse/jwp-refactoring/pull/662) | [4단계 PR](https://github.com/woowacourse/jwp-refactoring/pull/744) |
|JDBC 라이브러리 구현하기 <br>|트랜잭션, JDBCTemplate 구현| [Repository](https://github.com/jaehee329/jwp-dashboard-jdbc)| [1단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/322) | [2단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/486) | [3단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/486) | [4단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/597)|
|@MVC 구현하기 <br>| MVC 프레임워크를 구현<br> 레거시를 새 프레임워크 기반으로 수정 |[Repository](https://github.com/jaehee329/jwp-dashboard-mvc)| [1단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/400) | [2단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/498) | [3단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/528) | x |
|Tomcat 구현하기 <br>| 간단한 웹 서버를 제작<br>스레드 풀을 적용 |[Repository](https://github.com/jaehee329/jwp-dashboard-http)| [1단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/336) | [2단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/336) | [3단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/457) | [4단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/457) |
### 관련 글
[Enum에서는 valueOf()보다 table switch로 최적화된 switch ~ case를](https://jaehee329.tistory.com/47)  
[EntityManager의 merge() 동작 방식 유의점](https://jaehee329.tistory.com/48)  

<br>

## Level 3 (2022.06.27 ~ 2022.08.18)

<img width="900" alt="image" src="https://github.com/jaehee329/woowacourse-record/assets/77962265/00b1cdf0-8438-47a7-8860-da2f00190aa5">

[하루스터디](https://haru-study.com/) 서비스 기획, 구현 및 운영 <br>
[Repository](https://github.com/woowacourse-teams/2023-haru-study)

### 관련 글
[인증 관련 플로우 및 기능 점검](https://jaehee329.tistory.com/50)  
[우리 서버는 어느 정도의 부하를 견딜 수 있을까 - 부하 테스트 계획 & 실행](https://jaehee329.tistory.com/49)  
[밤에 DB와 서버를 안전하게 예약 중단 배포하기](https://jaehee329.tistory.com/46)  
[SpringBoot Application과 Grafana 기반의 Metric & Log 모니터링](https://jaehee329.tistory.com/45)  
[언제 JPA를 통해 슈퍼/서브타입을 사용해야 할까?](https://jaehee329.tistory.com/43)  
[RDB에 JPA로 변경 가능성이 높은 데이터를 JSON으로 저장하기](https://jaehee329.tistory.com/42)  
<br>

## Level 2 (2022.04.11 ~ 2022.06.09)
### 미션
| Project | 목표 | Repository | 1단계 PR | 2단계 PR | 3단계 PR |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|쇼핑 주문 <br>|API 구현, 서버 띄우기<br> 프론트엔드와 협업| [Repository](https://github.com/jaehee329/jwp-shopping-order)|x|[2단계 PR](https://github.com/woowacourse/jwp-shopping-order/pull/102) |x|
|지하철 <br>|복잡한 비즈니스 요구사항 구현<br> 웹 앱에서의 TDD| [Repository](https://github.com/jaehee329/jwp-subway-path)| [1단계 PR](https://github.com/woowacourse/jwp-subway-path/pull/62) | [2단계 PR](https://github.com/woowacourse/jwp-subway-path/pull/135) | [3단계 PR](https://github.com/woowacourse/jwp-subway-path/pull/185)
|쇼핑 장바구니 <br>|쇼핑몰의 상품 관리 CRUD 구현 |[Repository](https://github.com/jaehee329/jwp-shopping-cart)| [1단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/180) | [2단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/286)|x|
|웹 자동차 경주 <br>| 콘솔 기반 앱을 웹앱으로 변경<br>Spring MVC 처음 도입 |[Repository](https://github.com/jaehee329/jwp-shopping-cart)| [1단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/180) | [2단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/286) |x|
### 관련 글
[logback-spring.xml을 사용해 로그 커스터마이즈하기](https://jaehee329.tistory.com/36)  
[순수 JDBC + Spring 조합의 웹앱 테스트하기](https://jaehee329.tistory.com/38)  
[ViewResolver의 동작 과정](https://jaehee329.tistory.com/37)  
[왜 Mockito를 통해 테스트를 해야 할까?](https://jaehee329.tistory.com/34)  
[필터와 인터셉터에서 요청에 대한 처리를 어떻게 캐싱할까?](https://jaehee329.tistory.com/33)  
[핸들러(컨트롤러 메서드)는 어떤 우선순위로 선택되는가?](https://jaehee329.tistory.com/32)  
[왜 Random Port의 SpringBootTest에서는 @Transactional 적용이 되지 않을까?](https://jaehee329.tistory.com/31)  
[필드 주입도 순환 참조를 검사해 준다?](https://jaehee329.tistory.com/30)  
[외래 키를 사용해야 할까?](https://jaehee329.tistory.com/29)
[@Autowired와 의존성 주입](https://jaehee329.tistory.com/28)

<br>

## Level 1 (2022.02.07 ~ 2022.03.31)
### 미션
| Project | 목표 | Repository | 1단계 PR | 2단계 PR | 3단계 PR | 4단계 PR |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|체스 <br>|콘솔로 체스 게임 구현<br> DB로 게임 진행도 저장| [Repository](https://github.com/jaehee329/java-chess)|[1단계 PR](https://github.com/woowacourse/java-chess/pull/438)|[2단계 PR](https://github.com/woowacourse/java-chess/pull/438) | [3단계 PR](https://github.com/woowacourse/java-chess/pull/610) | [4단계 PR](https://github.com/woowacourse/java-chess/pull/610)|
|블랙잭 <br>|작은 크기의 클래스로<br>Clean Code 작성| [Repository](https://github.com/jaehee329/java-blackjack)| [1단계 PR](https://github.com/woowacourse/java-blackjack/pull/481) | [2단계 PR](https://github.com/woowacourse/java-blackjack/pull/561) |x|x|
|사다리 타기 <br>|TDD로 진행 |[Repository](https://github.com/jaehee329/java-ladder)| [1단계 PR](https://github.com/woowacourse/java-ladder/pull/100) | [2단계 PR](https://github.com/woowacourse/java-ladder/pull/178)|x|x|
|자동차 경주 <br>| 단위 테스트 구현<br> MVC 패턴 적용 |[Repository](https://github.com/jaehee329/java-racingcar)| [1단계 PR](https://github.com/woowacourse/java-racingcar/pull/513) | [2단계 PR](https://github.com/woowacourse/java-racingcar/pull/622) |x|x|
### 관련 글
[왜 try-with-resources를 사용할까?](https://jaehee329.tistory.com/26)  
[동일성과 동등성, 그리고 equals와 hashCode](https://jaehee329.tistory.com/25)  
[가변 인수 적절하게 사용하기](https://jaehee329.tistory.com/24)  
[템플릿 콜백 패턴으로 동일한 작업을 효율적으로 처리하기](https://jaehee329.tistory.com/23)  
[원시값을 포장해 사용하자](https://jaehee329.tistory.com/22)  

