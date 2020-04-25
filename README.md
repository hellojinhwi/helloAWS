# helloAWS
### -> Spring Boot와 AWS로 구현하는 무중단 & 자동화 배포 웹 서비스<br><br>

**1. 개발배경**<br>
  - 단위 테스트 경험
    - 이전의 개발환경에서는 system.out.println() 으로 값을 찍어보고 확인하는 과정을 거치거나, 코드를 수정한 뒤에 프로그램을 실행하여
    직접 확인했었다. 실무에서 쓰이는 TDD(테스트가 주도하는 개발)을 경험하기 앞서 단위테스트를 통해 테스트 코드를 활용한 개발환경을
    직접 경험해보고 그 중요성을 느껴보고 싶었다.<br>
    
  - 스프링 시큐리티 OAuth 2.0 으로 소셜 로그인 기능 구현 경험
    - 스프링부트를 사용해 개발을 해왔지만 로그인 기능을 구현할 때는 인증환경, 비밀번호 변경, 회원정보 변경을 직접 만들어서 사용했었다.
    하지만 스프링부트에는 보안의 표준이라 할 수 있는 스프링 시큐리티 API를 제공하며, 소셜로그인을 사용한다면 위에 나열했던 기능들을 만들
    필요가 없기 때문에 좀 더 개발에 집중할 수 있게 된다.<br>
    
  - AWS 클라우드 서비스를 이용해 서버 배포
    - AWS가 가지고 있는 수백가지 솔루션 중 웹페이지를 구현하는 데 필요한 가장 기초적인 몇가지 솔루션들을 경험해보고 싶었다.
       - EC2를 활용해 서버환경 구축 (보안그룹, 탄력적IP, PuTTY를 활용해 EC2 접속
       - 직접 데이터베이스 환경을 구축하지 않고 이미 환경이 가춰진 RDS(MariaDB) 사용
       - Travis CI, S3, CodeDeploy를 활용한 CI & CD 환경 구축<br>
    
**2.Architecture**<br>
  - Spring MVC Pattern
  - AWS 자동화 & 무중단 배포 Solution Architecture <br>
  ![helloAWS_Architecture](https://user-images.githubusercontent.com/53262708/80268144-04d3b100-86e0-11ea-9a85-ea138ea2a231.jpg)<br>
  
**3.Skill Set**<br>
  *Front-end : Mustache, Javascript, Bootstrap
  *Back-end : Spring Boot, AWS ( EC2, IAM, RDS, S3, CodeDeploy ), Travis CI, NGINX
  *DB : MySQL, AWS RDS
  *Environment : IntelliJ
  *Build Tool : Gradle
  
  
