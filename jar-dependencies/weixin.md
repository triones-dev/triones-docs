### 微信集成
#### 添加依赖管理
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-weixin-spring-boot-starters</artifactId>
    <version>1.0-SNAPSHOT</version>
    <type>pom</type>
    <scope>import</scope>
    <exclusions>
        <exclusion>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-dependencies</artifactId>
        </exclusion>
    </exclusions>
</dependency>
```

#### 公众号集成
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-weixin-offiaccount-spring-boot-starter</artifactId>
</dependency>
```
#### 小程序集成
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-weixin-miniprogram-spring-boot-starter</artifactId>
</dependency>
```