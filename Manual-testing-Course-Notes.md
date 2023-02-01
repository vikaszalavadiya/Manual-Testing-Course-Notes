# Manual Testing

What is Software and what type of software?
 ![image](https://user-images.githubusercontent.com/47386222/215966294-c32fe3c7-c1e4-4900-845c-3e4e091b1ec0.png)

------------------------------------------------------
What is software testing?
-	Software testing is part of software development.
-	Software development is not only about writing code. 
-	There will be some bugs.
-	we have tested the software.
-	It is working as per customer requirement or not?

-	Software testing is an activity to detect and identify defect in the software.

----------------------------------------------------------------------------------------------
Why do we need testing?

-	We need to test because deliver quality products to the customer.
-	Ensure software is bug-free and fulfils customer requirements, it should work as customer acceptance.

------------------------------------------------------------------------
Software Quality parameters
-	Bug-free
-	Delivered on time
-	Within Budget
-	Meets requirements
-	Maintainable
-	
---------------------------------------------------------------------------------------------



Project Vs Product
Project: if software app. Is developed for specific customers based on their requirements then it is called a project.

Product: if software app. Is developed for multiple customers based on market requirements then it is called product.
----------------------------------------------------------------------------------------------
Error, Bug/defect and Failure:
-	Error: Error is basically a human mistake.
-	Bug: it is a coding error. Something is not working in our application according to your requirement.
-	Failure: something is not working properly. It is called failure.

----------------------------------------------------------------------------------------------
SDLC (software development life cycle)
SDLC is a process used by the software industry to design, develop and test software’s.
There 
 

P – People
P – Process
P – Product
----------------------------------------------------------------------------------------------




Waterfall Model:
 
The next phase is started only after the previous is completed.
Advantages:
-	The quality of the product will be good
-	Initial investment is less 
-	Preferred for small projects.
Disadvantages:
-	Requirement changes are not allowed.
-	If there id a defect in the requirement that will be continued in the late stage.
-	Testing will start only after coding.


----------------------------------------------------------------------------------------------
Spiral Model:
 

 

----------------------------------------------------------------------------------------------
V Model / VV Model:
 

BRS/CRS/USR => business/customer/user requirement specification
SRS => software requirement specification
HLD => Hight level design doc.
LLD => low level design doc

----------------------------------------------------------------------------------------------
Static Testing (Verification):
Testing the project-related documents are called as static testing

-	Review
-	Walkthrough
-	Inspection

Review:
 
Review is planned.


Walkthrough:
 
Walkthrough is not pre planed.

Inspection:
It is more formal.
 

----------------------------------------------------------------------------------------------


Dynamic Testing (Validation):
-	Testing the actual software
-	White box testing and black box testing.

White Box Testing techniques:
-	Unit testing + integration testing => white Box Testing
-	white Box Testing is done by the developer.
-	Test the internal logic of the program.
-	Whatever testing is conducted into code it is called white box testing.

Black Box Testing techniques:
-	System testing + User Acceptance testing => Black Box Testing
-	Black box testing is done by the tester.
-	Tester can validate the software of work properly as per customer requirement.


Integration testing: integrate multiple module in single code
----------------------------------------------------------------------------------------------
Verification / Validation:

 

----------------------------------------------------------------------------------------------




QA vs QC vs QE

P – people – QC (Tester)
P – Process – QA
P - Product
-	QA is process related
-	QA is taking care of all SDLC process
-	QC is the actual testing of the software

-	QA focuses on building in quality.
-	QC focuses on testing for quality


-	QA is preventing a defect.
-	QC is detecting defect.

-	QA is process oriented.
-	QC is product oriented.

-	QA for entire life cycle.
-	QC for testing part in SDLC.

QE => Quality Engineering

----------------------------------------------------------------------------------------------

Levels of Testing:

1-> Unit Testing (test small modules / small piece of code)
2-> Integration Testing (combine multiple modules into a single module. And it will test)
3-> System Testing (Testing the overall functionaly of)
4-> User Acceptance Testing (UAT)

Unit Testing
----------------
 


Unit Testing Techniques:
-	Basis path testing
-	Conditional coverage
-	Loops coverage
-	Mutation testing
Basis path testing: each and every line will be executed into the entire code.
Conditional coverage: if- else condition cover, work properly or not
Loops coverage: for, while loops cover, work properly or not
Mutation testing: repetition, testing multiple time same part of code


Integration Testing
------------------------
 
 

Incremental Testing:
------------------------
 

 
 


Non-Incremental Testing:
------------------------------

 

System Testing:
-----------------------
 

User Acceptance Testing (UAT):
----------------------------------

 

============================================================================================	

System Testing Types
 
 

GUI testing
-	front end testing
-	mainly focus to UI of application

 
----------------------------------------------------------------------------------------------




Usability Testing:
 
-	Easy ness of application.
-	Users will be comfortable with the application
-	If there is a document It have simple context and simple English.
-	Basically it is easy to understand and use for customer.
-	
---------------------------------------------------------------------------------------------
Functional Testing:
 

Focus on UI => size, colour, width, position of text box
Focus on functionally of application. => text box allow the -> Character limitation, valid Ch. , 

Object Properties Testing:
----------------------------------
Object => btn, text box, drodown etc…
Object Properties=> enable/disable, select only one radio btn (male / female), select only element in dropdown, 

Database testing /backend testing:
------------------------------------
DML Operations (Data manipulation language)



Gray Box Testing => Combination of white box and black box testing
Gray Box Testing => Ex. Database testing
Database testing => test database using sql query (white box testing)
Database testing => sending or updating data from UI (black box testing)




Detailed database Testing:
 

Error Handling testing:
------------------------
 

Calculations Testing:
-----------------------
Testing should verify the calculations.

Links Testing:
---------------
 


Cookies & Session:
----------------------
Cookies: it is temporary file or data which is created by our browsers. while you browning the pages through internet.

Session: The session is created on the server side. sessions are time slots created by the server. Session will be expired after some time (If you are idle for some time)


----------------------------------------------------------------------------------------------
Non-Functional Testing:
-	Focus on the customer acceptation.
 

Performance Testing:
------------------------
Speed of the application
Load testing => increate number of user (load) slowly and check speed of application
Stress => suddenly increase/ decrease the load on the application and check speed of application

Volume => check how much data is able to handle by the application.

Security testing: How secure our application.
 

Compatibility Testing:
----------------------------
Forward compatibility
Backword compatibility
hardware compatibility

Installation Testing
-------------------------
 

Sanitation / Garbage testing:
------------------------------
 

----------------------------------------------------------------------------------------------

Regression Testing:
-	If some bug in a particular function in the software and the developer modify that function and generate a new build. That new version software can not impact the existing other function in the software.
 

----------------------------------------------------------------------------------------------
Re-Testing:

-	If we find bug in a particular function. Then it will fix and tester test again it will fix or not it is called Re-testing.

-	In regression testing we test the modified functions along with the impacted modules.
-	But in re-testing we just verified bug is present or not. 

 

 
----------------------------------------------------------------------------------------------
Smoke vs Sanity Testing:
 
 
----------------------------------------------------------------------------------------------



Exploratory Testing:
 
----------------------------------------------------------------------------------------------
Adhoc Testing:
 


Adhoc testing = random testing without any test case, based on previous experience
Testers have knowledge about that application testing base on previous experience.

----------------------------------------------------------------------------------------------
Monkey / Gorill Testing:
Monkey Testing => random testing without any test case and without knowledge of application testing.
 

 

----------------------------------------------------------------------------------------------
Positive Testing:
 
----------------------------------------------------------------------------------------------




Negative Testing:
 
 
----------------------------------------------------------------------------------------------
END to END Testing:
 

----------------------------------------------------------------------------------------------

Test case Design Techniques
-----------------------

Used to prepare data for testing
1 reduce the data
2 more coverage 

Types
------
1.	Equivalence class partitioning (ECP)
2.	Boundary Value Analysis (BVA)
3.	Decision Table Based Testing
4.	State Transition
5.	Error Guessing

----------------------------------------------------------------------------------------------
Equivalence class partitioning (ECP):
---------------------------------------
Focus on the values
 

 
 
----------------------------------------------------------------------------------------------
Boundary Value Analysis (BVA)
 

----------------------------------------------------------------------------------------------
Input domain Testing:
-	The value will be verified in the text box/input filed.
-	We use ECP & BVA techniques.

----------------------------------------------------------------------------------------------
Decision Table Based Testing
If we have more number of conditions/action then we use decision table technique.
 
 

 
------------------------------------------------------------------------
State Transition:
 
----------------------------------------------------------------------------------------------
Error Guessing:
 
----------------------------------------------------------------------------------------------

STLC (Software Testing Life Cycle):

SDLC => reqAnalysis, Design, coding, testing, deployment, maintanace.

STLC => Software Testing Life Cycle
1.	Requirement Analysis
2.	Test Planning
3.	Test Design
4.	Test Execution
5.	Defect/Bug Reporting & Tracking
6.	Test Closer
 
 

Phase 1 – Test Planning:
-	What to test -> what different scenario we test,  
-	How to test -> what type of test conduct, which tool use,
-	When to test -> how many hour/ days we conduct testing

-	Project plane => creating by project manager including time line


-	FRS => Functional Requirements Specification
-	Function requirement is available in FRS doc.

-	Test plane => one type of doc. Which is contain type testing, what feature test or not, schedules, resources etc..

   
-	Test plan sign-off => one type of approval process by a manager.

Phase 2 – Test Designing:

-	Test Designing => main part writing test cases
-	What test scenarios => What is area of test. scenarios means what to test in our application for example there is login box.

-	What is test case => test case is step by step action. which have to perform test the functionality of application.

-	Traceability Matrix => one type of small excel doc. Mapping between requirements and test cases. For example you have requirement one how many test case written. requirement two how many test case written. Traceability Matrix tell you what test cases cover or not

Test Phase 3 – Test Execution:

-	Test Report/test Log => Prepare test report day to day bases. How many test cases executed today, how many pass how many fails. All detailed inside the test log doc.

Test Phase 4 – Defect Reporting & Tracking

-	Defect report => prepare excel file. Add the defect into list. And tracking the defect it is fixed or not.

Test Phase 5 -  Test Closure/Sign-Off

----------------------------------------------------------------------------------------------
Test Plan contents (Test plan is Doc)

 


Use Case
-	Use case describes the requirement.
-	Use case contains THREE iterms
o	Actor, which is the user, which can be single person a or a group of people, interacting with a process.
o	Action, which is to reach the final outcome.
o	Goal/Outcome, which is the successful user outcome.
Test Scenario => A possible area to be tested (what to test)
Test Case 
-	Step by step action to be performed to validate functionality of AUT (How to test)
-	Test case contain test step, expected result & actual result.
-	A Test case is a set of action executed to validate particular feature or functionality of your software application.

----------------------------------------------------------------------------------------------
Use Case VS Test Case
Use Case => Describe functional requirement, prepared by Business Analyst or product manager
Test Case => Describe Test steps/procedure by test engineer.



Test Scenario VS Test Case
-	Test Scenario is “What to be tested” and Test case is “How to be tested”.
 

----------------------------------------------------------------------------------------------
Test Suite
-	Test suite is group of test cases which belong to same category.
 

----------------------------------------------------------------------------------------------
Test Case Contents (Test Case is Doc.)

 

Test Case Template
 

----------------------------------------------------------------------------------------------
Requirement Traceability Matrix (RTM)

What is RTM?
-	RTM is describe the mapping of requirements with Test cases.
-	The main purpose of RTM is to see that all test cases are covered so that no functionality should miss while doing software testing.



















=========================================================================
Software Testing Life Cycle:
------------------------------
Manual Testing Project:
-------------------------
-	Project introduction
-	Understanding & explore the functionality of the product (need to read FRS doc.)
-	Test plan (before test plan => we need to refer project plan (duration) & FRS Doc.)
-	Writing test scenarios
-	Writing test cases & reviews
-	Environment setup & build deployment
-	Test execution
-	Bug reporting & tracking
-	Sanity Testing, Re-Testing & Regression testing
-	Test Sign off 

 

Demo Application for testing:
https://demo.opencart.com/


FRS => Functional Requirements Specification
Mockup Screen => it is dummy screen which will design before actual software design.

Test Plan Doc => which is describe the socp of the testing.(feature has to be tested, feature has not to be tested, schedules, what are the tool we used, what type of testing we conduct etc.. )


 


