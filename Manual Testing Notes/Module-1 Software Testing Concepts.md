


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

