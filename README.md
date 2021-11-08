# aws-spring

- gradle 6.9.1 로 설치
https://gradle.org/releases/
https://gradle.org/next-steps/?version=6.9.1&format=bin

- java 1.8 로 설치
https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=love_tolty&logNo=221585458347

https://github.com/frekele/oracle-java/releases
wget https://github.com/frekele/oracle-java/releases/download/8u92-b14/jdk-8u92-linux-x64.tar.gz

- aplication.propertis 파일 수정
```
spring.profiles.include=oauth
spring.jpa.show_sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5InnoDBDialect
spring.h2.console.enabled=true
spring.session.store-type=jdbc
```
