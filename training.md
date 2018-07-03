# Quality Engineering Training Manual

In order to correctly automate multiple types of testing, we need to use a technology stack. For the purposes of DevOpsIcon, we will use a Gradle based testing framework utilizing the following technologies:

- Gradle: Overall framework 
- JUnit: Test execution framework
- Cucumber: Test scenario writing and execution skeleton 
- Hamcrest: Assertions library 
- Rest-Assured: Service level testing framework, designed for REST.
- Selenium: UI testing framework
- Appium: Mobile testing framework

### Core Java
* Udemy's Master Java Class, it should take a good 3 months to cover it completely. About 7 percent a week is reasonable.
  * https://www.udemy.com/java-the-complete-java-developer-course/

### Service Testing
* REST-Assured is a very through testing framework, one of the most popular in Java. 
  * Site to use for testing: http://www.jsontest.com/
  * Rest Assured: 
  
### Batch Files Testing
Batch files are best validated via JUnit in accordance with a cucumber scenario. Apache Commons, Lombok, Hamcrest and Google's Guava are excellent libraries in parsing text files and validations.

* https://commons.apache.org/
* https://github.com/google/guava
* http://hamcrest.org/
* https://projectlombok.org/

### Web UI Testing
Selenium is the most popular framework for UI testing and below are links to it in the context of WebDriver.

* http://www.seleniumeasy.com/selenium-webdriver-tutorials

### Mobile UI Testing
Appium is the most popular framework for mobile testing, all SAAS providers such as Perfecto Mobile, Sauce Labs etc.

* https://www.guru99.com/introduction-to-appium.html
* https://www.youtube.com/watch?v=KAj3XGtVLhg
* https://www.youtube.com/watch?v=g6tCIvdk6-I
