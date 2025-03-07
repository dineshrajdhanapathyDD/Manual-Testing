


### Manual testing

## Manual Software Testing Part-1

Software
--
A Software is a collection of computer programs that helps us to perform a task.
-  Types of Software:
   - System software
        Ex: Device drivers, Operating Systems, Servers, Utilities, etc.
   -  Programming software
        Ex: compilers, debuggers, interpreters, etc.
   -  Application software
     Ex: Web Applications, Mobile Apps, Desktop Applications etc.

```x Bank(company)-----=---> IT Company---> Develop--->Test--->Deliver --->XBank```

What is software Testing?
--
- Software Testing is a part of software development process.
- Software Testing is an activity to detect and identify the defects in the software.
- The objective of testing is to release quality product to the client.

Software Quality
--
- Bug-free.
- Delivered on time.
- Within budget.
- Meets requirements and/or expectations.
- Maintainable.

Project Vs Product
--
 - If software application is developed for specific customer based on the requirement then it is called Project.
 - If software application is developed for multiple customers based on market requirements, then it called Product.

Error, Bug/defect & Failure
--
- Error: any incorrect human action that produces a problem in the system is called the error.
- Bug: Deviation from the expected behavior to the actual behavior is called the bug/defect.
- Failure: the deviation identified by end- user while using the system is called a failure.

Why the software has bugs?
--
- Miscommunication or no communication
- Software complexity
- Programming errors
- Changing requirements
- Lack of skilled testers

## Manual Software Testing Part-2

SDLC- Software Development Life Cycle
--
 - Software Development Life Cycle is a process used by software industry to design, develop and test software's.
  - P - People
  - P - Process
  - P - Product


Software Development Life Cycle
- Requirements Analysis
- Design
- Development
- Testing    
- Maintenance                                      
   
### Waterfall Model
     Requirement Analysis --> System Design --> Implementation Testing -->Deployment Maintenance 
   
Advantages of Waterfall Model
--
- Quality of the product will be good.
- Since Requirement changes are not allowed, chances of finding bugs will be less.
- Initial investment is less since the testers are hired at the later stages.
 - Preferred for small projects where requirements are feezed.
 
 Disadvantages of water model
--
 - Requirement changes are not allowed.
 - If there is defect in Requirement that will be continued in later phases.
 - Total investment is more, because time taking for rework on defect is time consuming which leads to high investment.
- Testing will start only after coding.
    
### Spiral model
         Planning --> Risk Analysis --> Engineering & Execution --> Evaluation.
        Version-1 --> Requirements analysis - prototype - Development & Testing- Customer Evaluation  - one cycle completed
        new requirements 
        version -2 -->  Requirements analysis - prototype - Development & Testing- Customer Evaluation   - second cycle

- Spiral Model is iterative model.
- Spiral Model overcome drawbacks of Waterfall model.
- We follow spiral model whenever there is dependency on the modules.
- In every cycle new software will be released to customer.
- Software will be released in multiple versions. So it is also called version control model.
     
Advantages of Spiral Model
--
- Testing is done in every cycle, before going to the next cycle.
- Customer will get to use the software for every module.
- Requirement changes are allowed after every cycle before going to the next cycle.

Disadvantages of Spiral Model
--
- Requirement changes are NOT allowed in between the cycle.
- Every cycle of spiral model looks like waterfall model.
- There is no testing in requirement & design phase.
        
```Prototype--- blue print of the software.```
```initial requirements from the customer---> Prototype--> Customer--> design, coding, testing```


Gmail
--
login
Inbox
compose
sent
receive email
etc....


Banking
--
Login
check balance
fund transfer
req statement
add payee
etc...

V-model/VV Model
--
```verification  --> BRS/CRS/URS --> SRS --> HLD,LLD --> coding```
```Validation --> unit testing (white box testing) --> integration testing (white box testing) --> system testing (black box testing) --> UAT (black box testing)```

VERIFICATION 
--
- Verification checks whether we are building the right product.
- Focus on Documentation


Static Test Technique
--
- Testing the project related documents is called as static testing.
 - Review
 - Walkthrough
 - inspection

VALIDATION
--
- Validation checks whether we are building the product right.
- Takes place after verifications are completed.
- Focus on Software

Dyanamic Testing
--
Testing the actual software

- unit testing
- integration testing
- system testing
- UA testing

```s1--> s2---> s3.......**** Application```

Advantages :
  -  Testing is involved in each and every phase.
 
Disadvantages:
   - Documentation is more.
   - Initial investment is more.



## Manual Software Testing Part-3
                
Static testing techniques
 - Review
 - Walkthrough
 - Inspection
 
 Dynamic testing techniques
 - Unit testing
 - integration testing
 - System testing
 - UAT
 
 Review
--
 - Conducts on documents to ensure correctness and completeness.
 - Requirement Reviews
 - Design Reviews
 - Code Reviews
- Test plan reviews
- Test cases reviews etc.

Walkthrough
--
 - It is a informal review.
 - Author reads the documents or code and discuss with peers.
 - It's not pre-planned and can be done whenever required.
 - Also walkthrough does not have minutes of the meet.

Inspection
--
 - its a most formal review type.
 - In which at least 3- 8 people will sit in the meeting 1- reader 2-writer 3- moderator plus concerned.
- Inspection will have a proper schedule which will be intimated via email to the concerned developer/tester:

QA Vs QC Vs QE
--
QA 
--
 - QA is Process related.
 - QA focuses on building in quality.
 - QA is preventing defects.
 - QA is process oriented.
 - QC for testing part in SDLC

QC
--
- QC is the actual testing of the software. 
- QC focuses on testing for quality.
- QC is detecting defects.
- QC is Product oriented.
- QA for entire life cycle.

QE
--
QE --> Quality engineering

 - Software Enginner /SE
 - Quality Engineer /QE

- p - people --> QC (testers)
- р- process -->
- p- product

SDLC
--
- Requirement Analysis
- Desing
- Coding
- Testing
- Deployment
- Maintenance

Levels of testing
--
 - Unit Testing
 - Integration Testing
 - System Testing
 - User Acceptance Testing (UAT)


Unit Testing
--
- A unit is a single component or module of a software.
- Unit testing conducts on a single program or single module.
- Unit Testing is white box testing technique.
- Unit testing is conducted by the developers.

Unit testing techniques:
--
- Basis path testing
- Control structure testing
- Conditional coverage
- Loops Coverage
- Mutation Testing

examples:- 
--
```
a=20 b=10
 if a>b
  print a is largest
 else
  b is largest
 1....5 numbers
 i=1
 max=10
while(i<=max)
{
print i
            12345
i=i+1
 }
 if user='scott' and password="123"
     allow login
 else
  Not allow login
```
Integration Testing
--
 - Integration testing performed between 2 or more modules.
 - Integration testing focuses on checking data communication between multiple modules.
 - Integrated Testing is white box testing technique.

Types of integration testing
--
1) Incremental Integration Testing
2) Non- Incremental Integration Testing

Incremental Integration Testing: 
--
- Incrementally adding the modules and testing the data flow between the modules.

- 2 Approaches
  - Top Down
  - Bottom Up

- Top Down -Incremental Integration Testing:
Incrementally adding the modules and testing the data flow between 1 the modules. And ensure the module added is the child of
previous module.

- Bottom Up -Incremental Integration Testing:
Incrementally adding the modules and testing the data flow between the modules. And ensure the module added is the parent of
the previous module.

Non- Incremental Integration Testing
--
- Adding all the modules in a single shot and test the data flow between modules.
Drawbacks:
  - We might miss data flow between some of the modules.
  - If you find any defect we can't understand the root cause of defect.

System Testing
--
 - Testing over all functionality of the application with respective client requirements.
 - It is a black box testing technique.
 - This testing is conducted by testing team.
- After completion of component and integration level testing's we start System testing.
 - Before conducting system testing, we should know the customer requirements.
 - System Testing focusses on below aspects:
    - User Interface Testing (GUI)
   - Functional Testing
   - Non-Functional Testing
   - Usability Testing

 User Acceptance Testing (UAT)
 --
 
- After completion of system testing UAT team conducts acceptance testing in two levels.
  - Alpha testing
  - Beta testing



## Manual Software Testing Part-4


What is GUI Testing?
--
-  Graphical User-interface Testing or GUI testing is a process of testing the user interface
  of an application.
 - A graphical user interface includes all the elements such as menus, checkbox, buttons,
  colors, fonts, sizes, icons, content, and images.
     
GUI Testing Checklist
--
  - Testing the size, position, width, height of the elements.
  - Testing of the error messages that are getting displayed.
  - Testing the different sections of the screen.
  - Testing of the font whether it is readable or not.
  - Testing of the screen in different resolutions with the help of zooming in and zooming out.
  - Testing the alignment of the texts and other elements like icons, buttons, etc. are in proper place or not.
  - Testing the colors of the fonts.
  - Testing whether the image has good clarity or not.
  - Testing the alignment of the images.
  - Testing of the spelling.
  -  The user must not get frustrated while using the system interface.
  - Testing whether the interface is attractive or not.
 - Testing of the scrollbars according to the size of the page if any.
- Testing of the disabled fields if any.
 - Testing of the size of the images.
  - Testing of the headings whether it is properly aligned or not.
 - Testing of the color of the hyperlink.
 - Testing UI Elements like button, textbox, text area, check box, radio buttons, drop downs, links etc.

Usability Testing
--
 -   During this testing validates application provided context sensitive help or not to the
  user.
  -  Checks how easily the end users are able to understand and operate the application is
  called usability testing.

  Functional Testing
--
-  Functionality is nothing but behavior of application.
-  Functional testing talks about how your feature should work.
 	- Object Properties Testing
	- Database Testing
   -  Error Handling
	- Calculations/Manipulations Testing
	- Links Existence & Links Execution
	- Cookies & Sessions

 - Object Properties Testing
	  - Check the properties of objects present on the Application.
   Ex: Enable, disable, visible, Focus......

 -  Database Testing/Backend testing:
	- Checking database operations with respect to user operations.
	 - DML Operations ( Data Manipulation Language)
		 - insert
		 - update
		 - delete
		 - select
	- Table & Column level validations(Column type, column length, number of columns...)
 Relation between the tables ( Normalization)
	- Functions
	 - Procedures
	 - Triggers
	 - Indexes
	 - Views
	 - etc......

 - Error Handling Testing
	- Tester verify the error messages while performing incorrect actions on the application.
	- Error messages should be readable.
	- User understandable/Simple language.
		- incorrect data
		- invalid data (more related)

 - Calculations/Manipulations Testing
	- Tester should verify the calculations.


 - Links Existence & Links Execution
	 - Where exactly the links are placed---- Links existence
	 - Links are navigating to proper page or not .... Links execution
		 - Internal links
		 - External links
		 - Brokens links

 - Cookies & Sessions
	 - Cookies:
		 - Temporary files created by Browser while browsing the pages through internet.
	 - Sessions:
		 - Sessions are time slots created by the server. Session will be expired after some time (If you are idle for some time)

Non-Functional Testing
--
  - Once the application functionality is stable then we do Non-Functional testing.
  - Focus on performance, load it can take and security etc.

	- Performance Testing
	     - Load Testing
	      - Stress Testing
	      - Volume Testing
	- Security Testing
	- Recovery Testing
	- Compatibility Testing
	- Configuration Testing 
	- Installation Testing
	- Sanitation/Garbage Testing
           
 - Performance Testing: speed of the application.               
	- Load: Gradually Increasing the load on the application then check the speed of the application.
	- Stress: suddenly increase/decrease the load on the application and check speed of the application.
	- Volume: Check how much data is able to handle by the application.

- Security testing: How secure our application.
   - Authentication ---> Users are valid or not
   - Authorization/Access Control ---> permissions of the valid user.

- Recovery testing:
     - check the system change to abnormal to normal.

- Compatibility testing
	- Forward Compatibility
	- Backward Compatibility
	- Hardware Compatibility (configuration testing)

- Installation testing
	- Check screens are clear to understand.
	- Screens navigation
	- Simple or not
	- Un-installation

- Sanitation/Garbage testing
	 - If any application provides extra features/functionality then we consider them as bug.

## Functional Testing vs Non-functional Testing

|Functional Testing|                     Non-Functional Testing                        |
|----------------|-----------------------------|
| Validates functionality of Software. |Verify the performance, security, reliability of the software.         |
|  Functionality describes what software does.      |Non-Functionality describes how   software works.       |
| Concentrates on user requirement.| Concentrates on user expectation.|
|Functional testing takes place before Non-functional testing.| Non-Functional testing performed after finishing Functional testing. |

## Manual Software Testing Part-5

Regression Testing
--
- Testing conducts on modified build to make sure there will not be impact on
  existing functionality because of changes like adding/deleting/modifying features.
   - Unit regression testing
   - Testing only the changes/modifications done by the developer.
   - Regional Regression Testing
   - Testing the modified module along with the impacted modules
	 - Impact Analysis meeting conducts to identify impacted modules with QA & Dev.
   - Full Regression
	 - Testing the main feature & remaining part of the application.
	 - Ex: Dev has done changes in many modules, instead of identifying impacted modules,
    we perform one round of full regression.


Re-Testing
--
-  Whenever the developer fixed a bug, tester will test the bug fix is called Re-
  testing.
- Tester close the bug if it worked otherwise re-open and send to developer.
- To ensure that the defects which were found and posted in the earlier build were
  fixed or not in the current build.
-  Example
	  - Build 1.0 was released. Test team found some defects (Defect Id 1.0.1, 1.0.2)
    and posted.
	  - Build 1.1 was released, now testing the defects 1.0.1 and 1.0.2 in this build is
    retesting.

Example: Re-Testing Vs Regression Testing
--
-  An Application Under Test has three modules namely Admin, Purchase and Finance.
                                      
- Finance module depends on Purchase module.
- If a tester found a bug on Purchase module and posted. Once the bug is fixed, the tester needs to do Retesting to verify whether the bug related to the Purchase is fixed or not and also tester needs to do Regression Testing to test the Finance module which depends on the Purchase module.
         ```Admin --> Purchase --> Finance```

Smoke Vs Sanity Testing
--
 - Smoke and Sanity Testing come into the picture after build release.

| Smoke Testing |Sanity Testing|
|---------------|--------------|
|Smoke Test is done to make sure the build we received from the development team is testable/stable or not|Sanity Test is done during the release phase to check for the main functionalities of the application without going deeper.|
|Smoke Testing is performed by both Developers and Testers|Sanity Testing is performed by Testers alone|
|Smoke Testing, build may be either stable or unstable|Sanity Testing, build is relatively stable|
|It is done on initial builds.|It is done on stable builds.|
|It is a part of basic testing.|It is a part of regression testing.|
|Usually it is done every time there is a new build release.|It is planned when there is no enough time to do in- depth testing.|

![Screenshot 2024-10-10 172126](https://github.com/user-attachments/assets/522d0b79-f066-4976-bade-9a3f51eadaa7)

Exploratory Testing
--
   - We have to explore the application ,understand completely and test it.
    - Understand the application, identify all possible scenarios, document it then use it for
    testing.
    - We do exploratory testing when the Application ready but there is no requirement.
    - Test Engineer will do exploratory testing when there is no requirement.
    - Drawbacks:
	    - You might misunderstand any feature as a bug (or) any bug as a feature since you do not have requirement.
	    - Time consuming
	    - If there is any bug in application, you will never know about it.
 
Adhoc Testing
--
-  Testing application randomly without any test cases or any business requirement document.
 - Adhoc testing is an informal testing type with an aim to break the system.
 - Tester should have knowledge of application even thou he doesn't have requirements/test cases.
 -  This testing is usually an unplanned activity.
		- no documentation
		- no test design 
		- no test case

Monkey/Gorilla Testing
--
 - Testing application randomly without any test cases or any business requirement document.
 - Ad hoc testing is an informal testing type with an aim to break the system.
 - Tester do not have knowledge of application
 - Suitable for gaming applications.

Adhoc Testing Vs Monkey Testing Vs Exploratory Testing
--
   
   |Adhoc Testing|Monkey Testing|Exploratory Testing|
   |-------------|--------------|------------------|
   |No Documentation|No Documentation|No Documentation|
   |No Plan|No Plan|No Plan|
   |Informal testing|Informal testing|Informal testing|
   |Tester should know Application functionality|Testers doesn't know Application functionality|Testers doesn't know Application functionality|
   |Random Testing|Random Testing|Random Testing|
   |Intension is to break the application/find out corner defects|Intension is to break the application/find out corner defects|Intension is to learn or explore functionality of application|
   |Any Applications|Gaming Applications|Any Applications which is new to tester|



 Positive Testing
--
-  Testing the application with valid inputs is called as Positive Testing.
-  It checks whether an application behaves as expected with positive inputs.
    - For example -
                Enter Only Numbers
                     99999
                Positive Testing
		- There is a text box in an application which can accept only numbers. Entering values up to 99999 will be acceptable by the system and any other values apart from this should not be acceptable.
		- To do positive testing, set the valid input values from o to 99999 and check whether the system is accepting the values.
     
 Negative testing
--
-  Testing the application with invalid inputs is called as Negative Testing.
- It checks whether an application behaves as expected with the negative inputs.
   -  For example -
                 Enter Only Numbers
                     abcdef
                 Negative Testing
		- Negative testing can be performed by entering characters A to Z or from a to z.
Either software system should not accept the values or else it should throw an
error message for these invalid data inputs.


Positive V/s Negative Test Cases
--
- Requirement:
	  - For Example if a text box is listed as a feature and in FRS it is mentioned as Text box accepts
	  -  6 - 20 characters and only alphabets.
 - Positive Test Cases:
	  - Textbox accepts 6 characters.
	  - Textbox accepts upto 20 chars length.
	  - Textbox accepts any value in between 6-20 chars length.
	  - Textbox accepts all alphabets.
 - Negative Test Cases:
	  - Textbox should not accept less than 6 chars.
	  - Textbox should not accept chars more than 20 chars.
	  - Textbox should not accept special characters.
	  - Textbox should not accept numerical.

END-To-END Testing
--
-  Testing the overall functionalities of the system including the data integration
  among all the modules is called end-to-end testing.

**End-To-End Test**

   -  Login
   - ADD New Customer
   - Edit customer
   - Delete Customer
   - Logout

![Screenshot 2024-10-10 174248](https://github.com/user-attachments/assets/a3dda118-da2f-4cb1-9b46-11e1e9609616)
 

Globalization and Localization Testing
--
- Globalization Testing:
	- Performed to ensure the system or software application can run in any cultural or local environment.
	- Different aspects of the software application are tested to ensure that it supports every language and different attributes.
	- It tests the different currency formats, mobile number formats and address formats are supported by the application.
	- For example, Facebook.com supports many of the languages and it can be accessed by people of different countries. Hence it is a globalized product.
  
- Localization Testing:
	- Performed to check system or software application for a specific geographical and cultural environment.
	- Localized product only supports the specific kind of language and is usable only in specific region.
	- It testes the specific currency format, mobile number format and address format is working properly or not.
	- For example, Baidu.com supports only the Chinese language and can be accessed only by people of few countries. Hence it is a localized product.



 ## Manual Software Testing Part-6

- Test Design Techniques/Test Data Design Techniques/Test case Design Techniques
-Used to prepare data for testing.
  1) Reduce the Data
  2) More Coverage
	
Test Design Techniques
--
- Test design techniques helps to design better cases.
- Reduce the number of test cases to be executed.
  
- Techniques:
  - Equivalence Class Partitioning
  - Boundary Value Analysis (BVA)
  - Decision Table based testing.
  - State Transition
  - Error Guessing

Equivalence Class Partition (ECP)
--
- Partition data into various classes and we can select data according to class then test. It reduces the number of test-cases and saves time for testing.
- Value check
- classify/divide/partition the data into multiple classes

 
Enter a Number:                         * Allow Digits from 1--500

 ```
  Normal Test Data : 1,2,3,4,5,6,7,8....500
  Divide values into Equivalence : -100 to 0 -> -50 (invalid), 1 to 100 -> 30 (valid)
  Test Data using ЕСР : -50 , 30
```
###  add table for example

Name:                                  * Allow only alphabets

|Divide values into Equivalence Classes| Test Data using ЕСР|
|------------------------|------------------|
|A..Z (Valid)|XYZ |
|a..z (Valid)| zyz |                                       
|Special Characters (Invalid)|@#$%|
|Spaces 250 (Invalid)|Ху Z  |
|Numbers --> 320(Invalid) |  1234|                              


Boundary Value Analysis (BVA)
--
- BVA technique used to check Boundaries of the input.
    
Enter a Age:                           * Allow Digits from 18--35

```
          Min = 18 (Pass)    Max = 35 (Pass)
          Min-1 =17 (Fail)    Max-1 =34 (Pass)
          Min+1 =19 (Pass)   Max+1 =36 (Fail)
```

Input domain testing
--
- The value will be verified in the text box/input fields.
- We use ЕСР & BVA techniques
                               
Decision Table
--
- Decision Table is also called as Cause-Effect Table.
- This technique will be used if we have more conditions and corresponding actions.
- In Decision table technique, we deal with combinations of inputs.
- To identify the test cases with decision table, we consider conditions and actions.

Decision Table Example
--
- Take an example of transferring money online to an account which is already added and approved.
- If we have more number of conditions /actions then we use decision table technique.

- Here the conditions to transfer money are
	- Account already approved
	- ОТР (one time password) matched
	- Sufficient money in the account
- And the actions performed are
	- Transfer money
	- Show a message as insufficient amount
	- Block the transaction in case of suspicious transaction

![Screenshot 2024-10-11 162314](https://github.com/user-attachments/assets/967db493-02d4-4625-b505-bb2cc9809aaa)

   
State Transition
--
- In State Transition technique changes in input conditions change the state of the Application.
- This testing technique allows the tester to test the behavior of an AUT.
- The tester can perform this action by entering various input conditions in a sequence.
-  In State transition technique, the testing team provides positive as well as negative input test values for evaluating the system behavior.

State Transition Example
--
-  Take an example of login page of an application which locks the username after three wrong attempts of password.

![Screenshot 2024-10-11 162805](https://github.com/user-attachments/assets/c1d43608-e07b-4e54-a95f-a9a223ffbe0b)
 
Error Guessing
--
-  Error guessing is one of the testing techniques used to find bugs in a software application based on tester's prior experience.
- In Error guessing we don't follow any specific rules.
- It depends on Tester Analytical skills and experience.
- Some of the examples are:
  - Submitting a form without entering values.
  - Entering invalid values such as entering alphabets in the numeric field.
        

## Manual Software Testing Part-7

SDLC - Software Development Life Cycle
--
  - Requirement Analysis, 
  - Design, 
  - Coding, 
  - Testing,
  - Deployment, 
  - Maintenance.
          
STLC - Software Testing Life Cycle
--
- Requirement Analysis
- Test Planning
- Test Desing
- Test Execution
- Defect/Bug Reporting & Tracking
- Test Closure


![Screenshot 2024-10-11 172901](https://github.com/user-attachments/assets/b7fc7072-421b-414f-96e6-73cb28f64884)



![Screenshot 2024-10-11 172933](https://github.com/user-attachments/assets/4709a412-edd7-47a8-8164-956ac52cc920)




## Manual Software Testing Part-8


Test Plan Contents
--
- A Test Plan is a document that describes the test scope, test strategy, objectives, schedule, deliverables and resources required to perform testing for a software product.
- Test plan template contents:
  	-  Overview
    - Scope
         - Inclusions
         - Test Environments
         - Exclusions
    - Test Strategy
    - Defect Reporting Procedure
    - Roles/Responsibilities
    - Test Schedule
    - Test Deliverables
    - Pricing
    - Entry and Exit Criteria
    - Suspension and Resumption Criteria
    - Tools
    - Risks and Mitigations
    - Approvals

Use case, Test Scenario & Test Case
--
-  **Use Case:**
	  - Use case describes the requirement.
	  - Use case contains THREE Items.
		     -**Actor**, which is the user, which can be a single person or a group of people, interacting with a process.
		     - **Action**, which is to reach the final outcome
		     - **Goal/Outcome**, which is the successful user outcome.
		     
- **Test Scenario:**
	  - A possible area to be tested (What to test)
	  
- **Test Case:**
	  - Step by step actions to be performed to validate functionality of AUT (How to test).
	  - Test case contains test steps, expected result & actual result.

![Screenshot 2024-10-11 192210](https://github.com/user-attachments/assets/ddfcc0f9-fccc-4e72-ad0c-35b60649d414)

Use Case V/s Test Case
--
 - **Use Case** - Describes functional requirement, prepared by Business Analyst (BA).
 - **Test Case** - Describes Test Steps/ Procedure, prepared by Test Engineer.

Test Scenario V/s Test Case
--
-  Test Scenario is 'What to be tested' and Test Case is 'How to be tested'.

- **Example: -**
- Test Scenario: Checking the functionality of Login button
      - TC1: Click the button without entering username and password.
      - TC2: Click the button only entering Username.
      - TC3: Click the button while entering wrong username and wrong password.

Test Suite
--
 - Test Suite is group of test cases which belongs to same category.

![Screenshot 2024-10-11 192530](https://github.com/user-attachments/assets/7d7ba9f9-fcc4-4e96-bff1-d0d871ed8aec)

What is Test case?
--
 - A Test Case is a set of actions executed to validate particular feature or functionality of your software application.

Test Case Contents
--
- Test Case ID
- Test Case Title
- Description
- Pre-condition
- Priority ( PO, P1,P2,P3)-order
- Requirement ID
- Steps/Actions
- Expected Result
- Actual Result
- Test data

Test Case Template
--

![Screenshot 2024-10-11 193220](https://github.com/user-attachments/assets/15189eda-9f68-47bb-9e25-6b444c747873)


Requirement Traceability Matrix(RTM)
--
-  **What is RTM (Requirement Traceability Matrix)?**
	 - RTM describes the mapping of Requirement's with the Test cases.
	 -The main purpose of RTM is to see that all test cases are covered so that no functionality should miss while doing Software testing.
  
  - **Requirement Traceability Matrix-Parameters include**
	  - Requirement ID
	  - Requirement Description
	  - Test case ID's

![Screenshot 2024-10-11 193600](https://github.com/user-attachments/assets/51079591-85e8-4bfd-99ab-dd8f37ccf341)

Test Environment
--
-  Test Environment is a platform specially build for test case execution on the software product.
- It is created by integrating the required software and hardware along with proper network configurations.
- Test environment simulates production/real time environment.
- Another name of test environment is **Test Bed**.

Test Execution
--
-  During this phase test team will carry out the testing based on the test plans and the test
  cases prepared.
-  **Entry Criteria:** Test cases, Test Data & Test Plan
-  **Activities:**
	  - Test cases are executed based on the test planning.
	  - Status of test cases are marked, like Passed, Failed, Blocked, Run, and others.
	  - Documentation of test results and log defects for failed cases is done.
	  - All the blocked and failed test cases are assigned bug ids.
	  - Retesting once the defects are fixed.
	  - Defects are tracked till closure.
 - **Deliverables:** Provides defect and test case execution report with completed results.

Guidelines for Test Execution
--
- The Build being deployed to the QA environment is the most important part of the test execution cycle.
- Test execution is done in Quality Assurance (QA) environment.
- Test execution happens in multiple cycles.
- Test execution phase consists of Executing the test cases + test scripts (if automation).

Defects/Bugs
--
-  Any mismatched functionality found in a application is called as **Defect/Bug/Issue**.
-  During Test Execution Test engineers are reporting mismatches as defects to developers through templates or using tools.
- Defect Reporting Tools:
	  - Clear Quest
	  - DevTrack
	  - Jira
	  - Quality Center
	  - Bug Jilla etc.

Defect Report Contents
--
-  **Defect_ID** - Unique identification number for the defect.
-  **Defect Description**-Detailed description of the defect including information about the module in which defect was found.
-  **Version** - Version of the application in which defect was found.
-  **Steps** -Detailed steps along with screenshots with which the developer can reproduce the defects.
-  **Date Raised** - Date when the defect is raised
- **Reference** - where you Provide reference to the documents like requirements, design, architecture or may be even screenshots of the error to help understand the defect
-  **Detected By**-Name/ID of the tester who raised the defect
-  **Status** - Status of the defect, more on this later
- **Fixed by**-Name/ID of the developer who fixed it
- **Date Closed** - Date when the defect is closed
- **Severity** which describes the impact of the defect on the application
- **Priority** which is related to defect fixing urgency. Severity Priority could be High/Medium/Low based on the impact urgency at which the defect should be fixed respectively

Defect Classification
--

![Screenshot 2024-10-11 194847](https://github.com/user-attachments/assets/e86ca2e0-5d3f-48f0-b63d-b2abf6cf97f2)

Defect Severity
--
-  Severity describes the seriousness of defect and how much impact on Business workflow.
-  Defect severity can be categorized into four class
	  - **Blocker (Show stopper):** This defect indicates nothing can proceed further.
			 - Ex: Application crashed, Login Not worked
	  - **Critical:** The main/basic functionality is not working. Customer business workflow is broken. They cannot proceed further.
		    - Ex1: Fund transfer is not working in net banking
		    - Ex2: Ordering product in ecommerce application is not working.
	  - **Major:** It cause some undesirable behavior, but the feature/application is still functional.
		   - Ex1: After sending email there is no confirm message
           - Ex2: After booking cab there is no confirmation.
	  - **Minor:** It won't cause any major break-down of the system
		   - Ex: Look and feel issues, spellings, alignments.

Defect Priority
--
-  Priority describes the importance of defect.
-  Defect Priority states the order in which a defect should be fixed.
- **Defect priority can be categorized into three class**
	  - **PO (High):** The defect must be resolved immediately as it affects the system severely and cannot be used until it is fixed.
	  - **P1 (Medium):** It can wait until a new versions/build is created
	  - **P2 (Low):** Developer can fix it in later releases.

High severity, priority and low severity, priority defects
--

![Screenshot 2024-10-11 195952](https://github.com/user-attachments/assets/077b352a-e19f-4c1a-8776-94aa4e1b06f3)


More examples...
--
-  **Low priority-Low severity-** A spelling mistake in a page not frequently navigated by users.
-  **Low priority-High severity-** Application crashing in some very corner case.
-  **High priority-Low severity-** Slight change in logo color or spelling mistake in company name.
- **High priority-High severity-** Issue with login functionality. (user is not able to login to the application)
-  **High Severity- Low Priority-** Web page not found when user clicks on a link (user does not visit that page generally)
-  **Low Priority- Low Severity-** Any cosmetic or spelling issues which is within a paragraph or in the page

Defect Resolution
--
-  After receiving the defect report from the testing team, development team conduct a review meeting to fix defects. Then they send a Resolution Type to the testing team for further communication.
-  Resolution Types:-
	  - Accept
	  - Reject
	  - Duplicate
	  - Enhancement
	  - Need more information
	  - Not Reproducible
	  - Fixed
	  - As Designed


## Manual Software Testing Part-9


Bug life cycle
--

![Screenshot 2024-10-14 154134](https://github.com/user-attachments/assets/852273f8-b1a2-4531-bb8c-9d061306ec9e)


Test Cycle Closure
--
-  Activities
	  - Evaluate cycle completion criteria based on Time, Test coverage, Cost, Software,
    Critical Business Objectives, Quality
	  - Prepare test metrics based on the above parameters.
	  - Document the learning out of the project
	  - Prepare Test summary report
	  - Qualitative and quantitative reporting of quality of the work product to the
    customer.
	  - Test result analysis to find out the defect distribution by type and severity.
	  
  - Deliverables
	  - Test Closure report
	  - Test metrics

Test Metrics
--

|S.NO |Required Data |
|-----|-------------| 
 |1|No. Of Requirements|
 |2 | Avg. No. of Test Cases written Per Requirement |
 |3 |Total No.of Test Cases written for all Requirement|
 |4 |Total No. Of test cases Executed|
 |5|No.of Test Cases Passed |6|No.of Test Cases Failed| 
 |7 |No.of Test cases Blocked |
 |8| No. Of Test Cases Un Executed|
 |9|Total No. Of Defects Identified |
 |10|Critical Defects Count |
 |11|Higher Defects Count |
 |12|Medium Defects Count |
 |13|Low Defects Count |
 |14|Customer Defects |
 |15|No.of defects found in UAT|

Test Metrics
--
-  % of Test cases Executed:
  No.of Test cases executed/Total No. of Test cases written) * 100
 
- % of test cases NOT executed:
  (No.of Test cases NOT executed/Total No. of Test cases written) * 100
 
- % Test cases passed
  (No.of Test cases Passed /Total Test cases executed) * 100

- % Test cases failed
  (No.of Test cases failed / Total Test cases executed) * * 100

- %Test cases blocked
  (No.of test cases blocked/Total Test cases executed * 100

Test Metrics
--
-  Defect Density: Number of defects identified per requirement/s
	  - No.of defects found / Size(No. of requirements)
- Defect Removal Efficiency (DRE):
```(A/A+B)*100
  (Fixed Defects / (Fixed Defects + Missed defects)) * 100
    - A- Defects identified during testing/ Fixed Defects
    - B- Defects identified by the customer/Missed defects
```
- Defect Leakage:
	  - (No.of defects found in UAT/No. of defects found in Testing) * 100
- Defect Rejection Ratio:
	  - (No. of defect rejected /Total No. of defects raised) * 100
- Defect Age: Fixed date-Reported date
- Customer satisfaction = No.of complaints per Period of time


QA/Testing Activities
--
-  Understanding the requirements and functional specifications of the application.
-  Identifying required Test Scenario's.
-  Designing Test Cases to validate application.
-  Setting up Test Environment (Test Bed)
- Execute Test Cases to valid application
- Log Test results (How many tests cases pass/fail).
- Defect reporting and tracking.
- Retest fixed defects of previous build
- Perform various types of testing's in application.
- Reports to Test Lead about the status of assigned tasks
- Participated in regular team meetings.
- Creating automation scripts.
- Provides recommendation on whether or not the application/ system is ready for
  production.

7 Principles of Software Testing
--
1. Start software testing at early stages. Means from the beginning when you get the
   requirements.
2. Test the software in order to find the defects.
3. Highly impossible to give the bug free software to the customer.
4. Should not do Exhaustive testing. Means we should not use same type of data for testing every time.
5. Testing is context based. Means decide what types of testing should be conducted based on type of application.
6. We should follow the concept of Pesticide Paradox. Means, if you are executing same cases for longer run, they wont be find any defects. We have to keep update test cases in every cycle/release in order to find more defects.
7. We should follow defect clustering. Means some of the modules contains most of the defects. By experience, we can identify such risky modules. 80% of the problems are found in 20% of the modules.



