# Selenium Automation Framework(with Java)
Author  - Yogita Solanki


### Tech Stack of Web Automation

1. Programming - Java ( JDK > 22, IntelliJ)
2. User Interactions, browser Automation Selenium
3. Test Framework -> TestNG
4. Build Management ->  Maven
5. Reporting - Allure Report, Extent Report.
6. Data Driven - DDT Apache POI.
7. CI / CD -> GIT, Jenkins
8. Coding Best Practice-  SonarLint
9. Logs - Log4j
10. Remote Selenium Grid - Cloud Grid, Selenoid

<img width="1024" alt="Screenshot 2023-10-31 at 12 27 14 PM" src="https://github.com/PramodDutta/AdvanceSeleniumFrameworkTTA/assets/1409610/02b0ef3b-1165-46cf-8c9d-89e41b17032f">

`mvn test -Dsurefire.suiteXmlFiles=testng.xml`

<img width="1215" alt="Screenshot 2023-10-31 at 12 27 28 PM" src="https://github.com/PramodDutta/AdvanceSeleniumFrameworkTTA/assets/1409610/b0905741-d88d-4559-93c2-65433e668170">


### Seleniod - Docker Grid Running
- Selenoid is a powerful tool for running Selenium tests in Docker containers.
- which can help you manage and scale your test automation infrastructure more efficiently.

## How to add Log4J in the Project ?
- Add this to the pom.xml
```<dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-core</artifactId>
      <version>3.0.0-beta2</version>
    </dependency>

    <!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-api -->
    <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-api</artifactId>
      <version>3.0.0-beta2</version>
    </dependency> 
```

```
-     private static final Logger logger = LogManager.getLogger(TestVWOLogin_PF_DM.class);
    
file
logger.info("Starting Test");

```