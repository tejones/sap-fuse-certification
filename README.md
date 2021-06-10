SAP Certification Tests for Red Hat Fuse (camel-sap) 
================  
 **This directory contains two sets of tests for the SAP certification**  
 
***  
Summary: These are the required tests for SAP certification with SAP ECC and S/4HANA.       
Target Product: Fuse  
***  

Overview  
--------  

The Fuse SAP certification tests are divided into two folders. The 8_2_RFC_Function_Module_Test_Drive folder has tests designed to validate the solution supports a completes set of data type structures coming from SAP. They can be run individually or all at once using the ALL_TESTS folder. These tests use Spring Boot to deploy and execute the tests with the results written to file and the console.

The 8_3-4_Performance_Load_And_Unicode_Test_Drive folder contains tests that check for load and unicode support. These test require a Karaf server 

###[8_2_RFC_Function_Module_Test_Drive](8_2_RFC_Function_Module_Test_Drive/README.md)  

The tests in this directory demonstrate how to configure.


###[Fuse](fuse/README.md)  

The quick starts in this directory demonstrates how to configure, deploy and run the JBoss Fuse SAP Camel components in a JBoss Fuse OSGi container runtime.

###[Spring Boot](spring-boot/README.md)  

The quick starts in this directory demonstrates how to configure, deploy and run the JBoss Fuse SAP Camel components in a Spring Boot Camel container runtime.

-----
For more information see:

* <https://access.redhat.com/documentation/en-us/red_hat_fuse/7.8/html-single/apache_camel_component_reference/#SAP> for more information about the Red Hat Fuse SAP Camel components 
* <https://access.redhat.com/products/red-hat-fuse> for more information about using Red Hat Fuse

System requirements
-------------------

To run these quick starts you will need:

* Maven 3.1.1 or higher
* JDK 1.8
* Red Hat Fuse version to be certified (7.8 was used for the current certification) 
* SAP JCo3 and IDoc3 libraries (sapjco3.jar, sapidoc3.jar and JCo native library for your OS platform)
* SAP instance with [Flight Data Application](http://help.sap.com/saphelp_erp60_sp/helpdata/en/db/7c623cf568896be10000000a11405a/content.htm) setup.



  
  
