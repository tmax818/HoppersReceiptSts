# HoppersReceiptSts


add to [pom.xml](./pom.xml)

```xml

    	<dependency>
                <groupId>org.apache.tomcat.embed</groupId>
                <artifactId>tomcat-embed-jasper</artifactId>
        </dependency>
		<dependency>
                <groupId>javax.servlet</groupId>
                <artifactId>jstl</artifactId>
        </dependency>

```

add to [index.jsp](./src/main/webapp/WEB-INF/index.jsp)

```html
<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>

```

add to [application.properties](./src/main/resources/application.properties)

```
spring.mvc.view.prefix=/WEB-INF/
```