# API-Cucumber

This API framework is developed using REST Assured and Cucumber.  REST Assured is a Java library that provides a domain-specific language (DSL) for writing powerful, maintainable tests for RESTful APIs. Cucumber is an open source library, which supports behavior driven development. 

Cucumber can be defined as a testing framework, that serves as a tool to write the automated tests.

Testing is done for [Restful-booker](https://restful-booker.herokuapp.com/apidoc/index.html).

### **Test framework**

1. It generates Extent report with all the step details.  
2. Generates execution logs, with detailed request and response details.
3. Feature file has examples of reading request details from json and excel file.
4. This also has an example to validate response body using json schema and java pojo classes.
5. Test execution can be triggered form command line. 
6. Easy integration to CI/CD pipeline.

## **Pre-Requisites**

- Java should be installed.
- Maven should be installed and configured.

## **Test Run**

- Open the command prompt and navigate to the folder in which pom.xml file is present. Run maven command - "mvn clean test".
- Test report will be generated in below folder once the execution completes.

**Report:** 		*target/report*<br>
**Log:** 		*target/logs*
