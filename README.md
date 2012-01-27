Thymeleaf Spring-MVC Maven Archetype
====================================

This project is a maven archetype for creating a web application with Thymeleaf and Spring.

Thymeleaf
---------

The main goal of Thymeleaf is to provide an elegant and well-formed way of creating HTML 5 templates. Its Standard and SpringStandard dialects allow you to create powerful natural templates, that can be correctly displayed by browsers and therefore work also as static prototypes.

Website: (http://www.thymeleaf.org/)

HTML5 + CSS 3 Form Using Thymeleaf + Spring MVC: (http://www.lordofthejars.com/2011/11/your-big-daddys-got-no-place-to-stay.html)

Application
-----------

This web application is composed by two html templates `WEB-INF/views` one for showing a form using HTML5 and CSS3 and another one for listing inserted data.

Spring controller is located in controller package.

Application is internationalized too using LocaleChangeInterceptor with en_US as default locale. Properties are in `src/main/resources/locale` folder.

And finally server-side validation is provided by using JSR-303 provider.

Versions
--------

Spring: 3.0.5

Thymeleaf: 1.1.2

Hibernate-Validator: 4.1.0

Slf4j: 1.5.10

Servlet-api: 2.5

JUnit: 4.9

Installation
------------

### From source:

Execute:

`mvn clean install`

`mvn archetype:generate -DarchetypeCatalog=local`

### From jar:

Download archetype from:

(https://oss.sonatype.org/content/repositories/releases/com/lordofthejars/thymeleafarchetype/thymeleaf-spring-maven-archetype/1.0.0/thymeleaf-spring-maven-archetype-1.0.0.jar)

Execute:

`mvn install:install-file \
   -DgroupId=com.lordofthejars \
   -DartifactId=thymeleaf-spring-maven-archetype \
   -Dversion=DOWNLOADED_VERSION \
   -Dpackaging=jar 
   -Dfile=PATH_TO_JAR_YOU_DOWNLOADED/thymeleaf-spring-maven-archetype-VERSION.jar`

or:

`mvn install:install-file \
   -DgroupId=com.lordofthejars \
   -DartifactId=thymeleaf-spring-maven-archetype \
   -Dversion=DOWNLOADED_VERSION \
   -Dpackaging=jar 
   -Dfile=https://oss.sonatype.org/content/repositories/releases/com/lordofthejars/thymeleafarchetype/thymeleaf-spring-maven-archetype/1.0.0/thymeleaf-spring-maven-archetype-1.0.0.jar`

Contact
--------

Blog: (www.lordofthejars.com)

Twitter: @alexsotob


