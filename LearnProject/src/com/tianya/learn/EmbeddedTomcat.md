
-- maven 内嵌tomcat服务

~~~xml
<build>
        <plugins>
            <plugin>
                <groupId>org.apache.tomcat.maven</groupId>
                <artifactId>tomcat7-maven-plugin</artifactId>
                <version>2.1</version>
                <configuration>
                    <port>8080</port>
                    <path>/web</path>
                    <uriEncoding>UTF-8</uriEncoding>
                    <finalName>web</finalName>
                    <server>tomcat7</server>
                </configuration>
            </plugin>
        </plugins>
</build>

~~~
