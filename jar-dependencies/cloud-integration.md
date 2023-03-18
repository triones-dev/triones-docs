### 云服务依赖
#### 添加依赖管理
```
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.moensun.spring.boot</groupId>
            <artifactId>moensun-cloud-integration-spring-boot-starters</artifactId>
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
    </dependencies>
</dependencyManagement>
```

##### 添加阿里云依赖
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-cloud-integration-aliyun-spring-boot-starter</artifactId>
</dependency>
```

##### 添加华为云依赖
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-cloud-integration-huaweicloud-spring-boot-starter</artifactId>
</dependency>
```

##### 添加腾讯云服务依赖
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-cloud-integration-tencentcloud-spring-boot-starter</artifactId>
</dependency>
```

##### 添加七牛云依赖
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-cloud-integration-qiniu-spring-boot-starter</artifactId>
</dependency>
```

##### 添加其他依赖
包含 minio
```
<dependency>
    <groupId>com.moensun.spring.boot</groupId>
    <artifactId>moensun-cloud-integration-other-spring-boot-starter</artifactId>
</dependency>
```