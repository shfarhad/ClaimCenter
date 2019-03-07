# ClaimCenter

Test framework for automation of cc-claim

1) Introduction:
 
This document describes the creation of the framework from scratch for automating CC-claim manual test cases. 


2) Requirement:

 a. Test case document
 b. Regression test cases
 c. Smoke tests

	  
3) Goals:

We will develop a framework that could be used to automate manual test cases. We will start by automating smoke test cases and make it run nightly using Jenkins integration tool. 
  

4) Constrains for selecting automation 
    Not able to automate dynamic changes
	Not able to automate Flash Play(custom)
	Not able to automate non-GUI test cases
	
5) Tools:
    a. Intelij IDE
	b. Maven to build the code
	c. github repository to keep the code
	d. Jenkins for continues integration
	c. SauceLab for cross browser testing
	e. Selenuim WebDriver using page object 
	
6) Program Language:
    Java 8

7) Unit testing framework:

  a. it manipulate tests in xml and gerenate a Report.html for failed and passed tests
  b. Supports multi threading testing
  c. Flexible plug-in API
  
	
8) Data Flow:
   a. Data from database using jdbconnect
   b. Data Sheet (Excel sheet)
   c. Hard code data 
   d. Properties files 
   e. Random generating data using API(Random)
   f. DataProvidvers - API-external 
   h. Data should be created and delete data after the test is executed
 
 9) Cross browser testing:
     Will use Sauce lab to run tests on different browsers


      


