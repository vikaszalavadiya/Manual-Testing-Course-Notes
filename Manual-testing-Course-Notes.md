# Manual Testing

### What is Software and what type of software?

![image](https://user-images.githubusercontent.com/47386222/215966294-c32fe3c7-c1e4-4900-845c-3e4e091b1ec0.png)

------------------------------------------------------
### What is software testing?
-	Software testing is part of software development.
-	Software development is not only about writing code. 
-	There will be some bugs.
-	we have tested the software.
-	It is working as per customer requirement or not?

-	Software testing is an activity to detect and identify defect in the software.

----------------------------------------------------------------------------------------------
### Why do we need testing?

-	We need to test because deliver quality products to the customer.
-	Ensure software is bug-free and fulfils customer requirements, it should work as customer acceptance.

------------------------------------------------------------------------
### Software Quality parameters
-	Bug-free
-	Delivered on time
-	Within Budget
-	Meets requirements
-	Maintainable

---------------------------------------------------------------------------------------------
### Project Vs Product
Project: if software app. Is developed for specific customers based on their requirements then it is called a project.

Product: if software app. Is developed for multiple customers based on market requirements then it is called product.
----------------------------------------------------------------------------------------------
### Error, Bug/defect and Failure:
-	Error: Error is basically a human mistake.
-	Bug: it is a coding error. Something is not working in our application according to your requirement.
-	Failure: something is not working properly. It is called failure.

----------------------------------------------------------------------------------------------
### SDLC (software development life cycle)
SDLC is a process used by the software industry to design, develop and test software’s.
There 
 
![image](https://user-images.githubusercontent.com/47386222/215966481-0bf3fef3-8562-419e-bf2a-938f1b815aea.png)


P – People
P – Process
P – Product

----------------------------------------------------------------------------------------------
###Waterfall Model:

![image](https://user-images.githubusercontent.com/47386222/215967862-efce43d6-3c9c-41c1-bb55-d5e64ccf07c4.png)

 
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
### Spiral Model:
 
![image](https://user-images.githubusercontent.com/47386222/215967940-a07782a0-b63c-4014-bbd4-082afeb2fa15.png)

![image](https://user-images.githubusercontent.com/47386222/215967977-49e96b30-172b-4ff4-843f-31a05319ee47.png)

 
----------------------------------------------------------------------------------------------
### V Model / VV Model:
 
![image](https://user-images.githubusercontent.com/47386222/215968039-5c294556-7d3f-49f2-9b4f-97c17a152afe.png)
 
 
BRS/CRS/USR => business/customer/user requirement specification
SRS => software requirement specification
HLD => Hight level design doc.
LLD => low level design doc

----------------------------------------------------------------------------------------------
### Static Testing (Verification):
Testing the project-related documents are called as static testing

-	Review
-	Walkthrough
-	Inspection

**Review:**  
 
Review is planned.

![image](https://user-images.githubusercontent.com/47386222/215968108-98ab7fab-316f-418e-abb6-1f2d440ea3a2.png)


**Walkthrough:**
 
Walkthrough is not pre planed.

![image](https://user-images.githubusercontent.com/47386222/215968173-62533683-d5fa-4bb8-bb43-9ad7f6cb8ace.png)

Inspection:
It is more formal.

![image](https://user-images.githubusercontent.com/47386222/215968193-d35d4931-e609-412f-a50b-f656eb9e7f35.png)


----------------------------------------------------------------------------------------------
### Dynamic Testing (Validation):
-	Testing the actual software
-	White box testing and black box testing.

**White Box Testing techniques:**
-	Unit testing + integration testing => white Box Testing
-	white Box Testing is done by the developer.
-	Test the internal logic of the program.
-	Whatever testing is conducted into code it is called white box testing.

**Black Box Testing techniques:**
-	System testing + User Acceptance testing => Black Box Testing
-	Black box testing is done by the tester.
-	Tester can validate the software of work properly as per customer requirement.


Integration testing: integrate multiple module in single code
----------------------------------------------------------------------------------------------
### Verification / Validation:

![image](https://user-images.githubusercontent.com/47386222/215968227-cabdbae4-dcd9-4fe1-9cfb-10aa44300222.png)


----------------------------------------------------------------------------------------------
### QA vs QC vs QE

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
### Levels of Testing:

1-> Unit Testing (test small modules / small piece of code)
2-> Integration Testing (combine multiple modules into a single module. And it will test)
3-> System Testing (Testing the overall functionaly of)
4-> User Acceptance Testing (UAT)

**Unit Testing**
----------------

![image](https://user-images.githubusercontent.com/47386222/215968319-911f66d4-af72-4b76-93f0-80a9c153ff33.png)



**Unit Testing Techniques:**
-	Basis path testing
-	Conditional coverage
-	Loops coverage
-	Mutation testing
Basis path testing: each and every line will be executed into the entire code.
Conditional coverage: if- else condition cover, work properly or not
Loops coverage: for, while loops cover, work properly or not
Mutation testing: repetition, testing multiple time same part of code


**Integration Testing**
------------------------
 
![image](https://user-images.githubusercontent.com/47386222/215968350-3acbcbcd-a471-4ebb-a995-864caa288010.png)

![image](https://user-images.githubusercontent.com/47386222/215968380-99848b94-0c6b-4820-bcd3-40bc8154782f.png)


**Incremental Testing:**
------------------------
 
![image](https://user-images.githubusercontent.com/47386222/215968500-8c0a1d2a-d0e6-495f-889e-aa02ad2f2f1b.png)

![image](https://user-images.githubusercontent.com/47386222/215968525-a1a69b78-a901-416c-9327-1896af1492de.png)

![image](https://user-images.githubusercontent.com/47386222/215968562-20cbbf12-66df-48c7-88bd-086848ef9b5d.png)


**Non-Incremental Testing:**
------------------------------

![image](https://user-images.githubusercontent.com/47386222/215968590-d6560db8-2cf9-46e8-ab3e-85fb7f51f47f.png)

 

**System Testing:**
-----------------------

![image](https://user-images.githubusercontent.com/47386222/215968617-3c63557f-88dd-435d-ae06-3d37a8b314b3.png)


**User Acceptance Testing (UAT):**
----------------------------------

![image](https://user-images.githubusercontent.com/47386222/215968698-3841b48f-b2fe-4a07-8374-0474586c45cf.png)


============================================================================================	

### System Testing Types
 
![image](https://user-images.githubusercontent.com/47386222/215968731-64bd0830-0c3d-4a7a-b6fa-65a4994fcd54.png)

![image](https://user-images.githubusercontent.com/47386222/215968762-1803e87a-b124-4764-b273-6d5c0b756151.png)
 

GUI testing
-	front end testing
-	mainly focus to UI of application

![image](https://user-images.githubusercontent.com/47386222/215968798-1b0b9dff-8093-4ed2-9800-dd2f3fdaef44.png)
 
----------------------------------------------------------------------------------------------
### Usability Testing:
 
-	Easy ness of application.
-	Users will be comfortable with the application
-	If there is a document It have simple context and simple English.
-	Basically it is easy to understand and use for customer.

![image](https://user-images.githubusercontent.com/47386222/215968844-fdff8f02-2532-4765-9ede-30e6aac307ba.png)


---------------------------------------------------------------------------------------------
### Functional Testing:
 

Focus on UI => size, colour, width, position of text box
Focus on functionally of application. => text box allow the -> Character limitation, valid Ch. , 

![image](https://user-images.githubusercontent.com/47386222/215968894-432b268d-6227-420b-bb21-d3511f028069.png)



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




**Detailed database Testing:**

![image](https://user-images.githubusercontent.com/47386222/215968943-e4d460ea-396d-40d3-8f18-5fa0d739cbc9.png)

 
Error Handling testing:
------------------------

![image](https://user-images.githubusercontent.com/47386222/215969008-f40951f2-b871-4282-a44c-9a86108f4a6b.png)


Calculations Testing:
-----------------------
Testing should verify the calculations.

Links Testing:
---------------
 
![image](https://user-images.githubusercontent.com/47386222/215969059-e77a72ab-561f-407b-8b2f-2c3f001c7e89.png)


Cookies & Session:
----------------------
Cookies: it is temporary file or data which is created by our browsers. while you browning the pages through internet.

Session: The session is created on the server side. sessions are time slots created by the server. Session will be expired after some time (If you are idle for some time)


----------------------------------------------------------------------------------------------
### Non-Functional Testing:
-	Focus on the customer acceptation.

![image](https://user-images.githubusercontent.com/47386222/215969105-60227a89-f05e-4545-b8b5-8c3fec865962.png)


Performance Testing:
------------------------
Speed of the application
Load testing => increate number of user (load) slowly and check speed of application
Stress => suddenly increase/ decrease the load on the application and check speed of application

Volume => check how much data is able to handle by the application.

Security testing: How secure our application.
 
![image](https://user-images.githubusercontent.com/47386222/215969159-22b7caad-430d-4b27-8f38-7c94861e846a.png)
 

Compatibility Testing:
----------------------------
Forward compatibility
Backword compatibility
hardware compatibility

Installation Testing
-------------------------

![image](https://user-images.githubusercontent.com/47386222/215969203-4e172375-c1d0-4d33-a523-8b251b1e4a25.png)
 

Sanitation / Garbage testing:
------------------------------

![image](https://user-images.githubusercontent.com/47386222/215969241-2a0a8361-4592-4760-b791-dd4600fd2adf.png)
 

----------------------------------------------------------------------------------------------
### Regression Testing:
-	If some bug in a particular function in the software and the developer modify that function and generate a new build. That new version software can not impact the existing other function in the software.
 
![image](https://user-images.githubusercontent.com/47386222/215969271-719c3630-c63b-48ed-b957-0e5f3fdca308.png)

----------------------------------------------------------------------------------------------
### Re-Testing:

-	If we find bug in a particular function. Then it will fix and tester test again it will fix or not it is called Re-testing.

-	In regression testing we test the modified functions along with the impacted modules.
-	But in re-testing we just verified bug is present or not. 

 
![image](https://user-images.githubusercontent.com/47386222/215969311-4f54545a-b9e9-4c39-acb0-cde0788edc47.png)

![image](https://user-images.githubusercontent.com/47386222/215969336-2f4baa10-bbdf-4b95-accf-ca1d3dd4ca6e.png)

 
----------------------------------------------------------------------------------------------
### Smoke vs Sanity Testing:
 
![image](https://user-images.githubusercontent.com/47386222/215969373-a55573a8-0515-4ff3-b2bb-1763a933e6b1.png)

![image](https://user-images.githubusercontent.com/47386222/215969420-087c6e25-1651-4454-b144-4fa622faab05.png)
 
----------------------------------------------------------------------------------------------
### Exploratory Testing:
 
![image](https://user-images.githubusercontent.com/47386222/215969455-0bf98a4c-1208-4be7-babd-c8b21ce87449.png)


----------------------------------------------------------------------------------------------
### Adhoc Testing:
 
![image](https://user-images.githubusercontent.com/47386222/215969508-6b04f642-aebe-4b31-a8da-7da72f5aaf10.png)


Adhoc testing = random testing without any test case, based on previous experience
Testers have knowledge about that application testing base on previous experience.

----------------------------------------------------------------------------------------------
### Monkey / Gorill Testing:
Monkey Testing => random testing without any test case and without knowledge of application testing.
 
![image](https://user-images.githubusercontent.com/47386222/215969559-f0f77bc4-b248-42da-b395-731614f268d2.png)

![image](https://user-images.githubusercontent.com/47386222/215969598-9f2b6700-844d-4d4d-8faa-2d5d7cc0855d.png)

----------------------------------------------------------------------------------------------
### Positive Testing:

![image](https://user-images.githubusercontent.com/47386222/215969629-013f4e3a-a76e-4170-ba36-32d057a00a35.png)

----------------------------------------------------------------------------------------------
### Negative Testing:

![image](https://user-images.githubusercontent.com/47386222/215969654-ef2aaa54-f047-4372-9a63-a03ff6602c05.png)

![image](https://user-images.githubusercontent.com/47386222/215969685-223551f7-8ca8-42d3-b03e-4769070c6b44.png)

----------------------------------------------------------------------------------------------
### END to END Testing:
 
![image](https://user-images.githubusercontent.com/47386222/215969734-9c43ca94-a5ae-4862-a018-d265faf238ee.png)

----------------------------------------------------------------------------------------------

### Test case Design Techniques
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
### Equivalence class partitioning (ECP):
---------------------------------------
Focus on the values
 
![image](https://user-images.githubusercontent.com/47386222/215969775-efb514bc-55a5-4dbe-a4db-5785edfe373d.png)

![image](https://user-images.githubusercontent.com/47386222/215969825-d30f64b8-f234-48a7-b982-8e5358e672dd.png)

 
 
----------------------------------------------------------------------------------------------
### Boundary Value Analysis (BVA)
 
![image](https://user-images.githubusercontent.com/47386222/215969856-3c9f080a-a385-47fb-890c-36829b7a90f4.png)

----------------------------------------------------------------------------------------------
### Input domain Testing:
-	The value will be verified in the text box/input filed.
-	We use ECP & BVA techniques.

----------------------------------------------------------------------------------------------
### Decision Table Based Testing
If we have more number of conditions/action then we use decision table technique.
 
![image](https://user-images.githubusercontent.com/47386222/215969887-2e18affa-ded0-4189-aa4e-d1f83b405ac2.png)

![image](https://user-images.githubusercontent.com/47386222/215969934-7a494156-5fbd-43a1-bc34-4a29ddeae0de.png)

![image](https://user-images.githubusercontent.com/47386222/215969966-4ef49094-fef3-442a-9d0e-d4e47c83219a.png)


------------------------------------------------------------------------
### State Transition:
 
![image](https://user-images.githubusercontent.com/47386222/215970009-d29f42de-d5be-4d84-8f31-952f3a6524d8.png)


----------------------------------------------------------------------------------------------
### Error Guessing:
 
![image](https://user-images.githubusercontent.com/47386222/215970063-b07ddcb6-5354-4ad0-b5aa-38e1c1233a4c.png)

----------------------------------------------------------------------------------------------

### STLC (Software Testing Life Cycle):

SDLC => reqAnalysis, Design, coding, testing, deployment, maintanace.

STLC => Software Testing Life Cycle
1.	Requirement Analysis
2.	Test Planning
3.	Test Design
4.	Test Execution
5.	Defect/Bug Reporting & Tracking
6.	Test Closer
 
![image](https://user-images.githubusercontent.com/47386222/215970119-192c6e9b-de2c-4278-8220-a469add8712b.png)

![image](https://user-images.githubusercontent.com/47386222/215970155-8ea75c9a-03e0-4cab-ba84-6d6f6c247dd2.png)


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
### Test Plan contents (Test plan is Doc)

![image](https://user-images.githubusercontent.com/47386222/215970197-2a2cb9b8-c331-4cb5-82ae-156140de47e6.png)
 


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
### Use Case VS Test Case
Use Case => Describe functional requirement, prepared by Business Analyst or product manager
Test Case => Describe Test steps/procedure by test engineer.



Test Scenario VS Test Case
-	Test Scenario is “What to be tested” and Test case is “How to be tested”.
 
![image](https://user-images.githubusercontent.com/47386222/215970253-a319ef16-11a2-4f31-b8a1-7980d6d7477c.png)

----------------------------------------------------------------------------------------------
### Test Suite
-	Test suite is group of test cases which belong to same category.
 
![image](https://user-images.githubusercontent.com/47386222/215970326-e87d2a38-3b3f-4b90-9602-4fed8a813369.png)

----------------------------------------------------------------------------------------------
### Test Case Contents (Test Case is Doc.)

![image](https://user-images.githubusercontent.com/47386222/215970354-e608b604-d75c-4bd8-b271-5eeb356d8c55.png)


Test Case Template
 
![image](https://user-images.githubusercontent.com/47386222/215970401-d44fe292-31cb-4e47-8dae-fb99a0655dad.png)

----------------------------------------------------------------------------------------------
### Requirement Traceability Matrix (RTM)

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


 


