# SpringBoot_FirstApplication

初めての Spring Boot アプリケーションの開発:SpringBoot入門

## ローカルで実行

``` sh
mvn spring-boot:run
```

[http://localhost:8080](http://localhost:8080)

## jarファイルを生成する

``` sh
mvn package
```

## jarを実行する

``` sh
# mvn spring-boot:runしたときと同じ状態になる。
java -jar ./target/myproject-1.0-SNAPSHOT.jar  
```

## 参考

- [初めての Spring Boot アプリケーションの開発:SpringBoot入門](https://spring.pleiades.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.first-application)