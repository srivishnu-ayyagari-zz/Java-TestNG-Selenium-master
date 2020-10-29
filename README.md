# Java TestNG Selenium 

### Environment Setup

1. Add Lambdatest Credentails details in Config.properties
    ```
    LambdaTest_UserName
    LambdaTest_AppKey
    ```
    
### Running Tests

```
To run single test
    $ mvn test -P single

To run local test
    $ mvn test -P local

To run parallel test
    $ mvn test -P parallel

To run single test fron Jenkins
    $ mvn test -P singleJenkins

To run parallel test from Jenkins
    $ mvn test -P parallelJenkins
```
### Test Result Setup

Please navigate to https://automation.lambdatest.com/ page for test result.
