Function Module Test Drive  
=======================================================================================================================
**Certifies the data type support of the SAP Camel Component running in a Fuse camel runtime.**  

* * *
Summary: SAP requires to include the function module testing during Test Drive. The goal is to assure camel-sap supports the required SAP data types.
Target Product: Red Hat Fuse  
* * *

System requirements
-------------------

Before building and running this quick start you will need:

* Maven 3.1.11 or higher
* JDK 1.11
* SAP JCo3 and IDoc3 libraries (sapjco3.jar, sapidoc3.jar and JCo native library for your OS platform). 

Configuring the Certification Test for your environment
-------------------------------------------------------

To configure the quick start for your environment: 

1. Copy the JCo3 library jar and native library (for your platform) and IDoc3 library jar to the `lib` folder of the tests you are running.   
2. Edit the parent project's POM file (`../pom.xml`) and modify the `SAP Instance Configuration Configuration Parameters` properties to match the connection configuration for your SAP instance.  

Build and Run the Certification Test
------------------------------------

To build and run the test:

1. Change your working directory to the `8_2_RFC_FUNCTION_Module_Test_Drive` directory.
2. Run `mvn clean install` to build the quick start of the test you are running. ALL_TEST for all tests at once.
3. Run `mvn spring-boot:run` to execute the tests. You should see the query result in the terminal in a successful run.

