# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://demo.opencart.com/ 

Application documentation: http://docs.opencart.com/en-gb/introduction/

API Documentation: https://docs.opencart.com/en-gb/system/users/api/

**The final project will be split into 2 sections: [Testing section](https://github.com/julai215/itf_final_project_example_and_portofolio/blob/main/Final%20Project/README.md#1-testing-section) and [SQL section](https://github.com/julai215/itf_final_project_example_and_portofolio/blob/main/Final%20Project/README.md#2-sql-section).**

Tools used:

# Functional specifications

-> enter here the functional specifications created in JIRA


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the NEW graphic interface of OpenCart application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

| Job Title  | Number of employees |
| :---: | :---: |
| Project Manager  | 1  |
| Product Owner  | 1 |
|Senior Lead Promgrammer| 1|
|Middle Programmers| 2|
|User experience/ User Interface Designer| 1|
|QA Lead| 1|
|Manuela Tester| 1|

#### 1.1.2 Entry criteria defined

* The website feature is partial/fully implemented
* Requirements and specifications are written and approved 
* When persons are allocated on their roles
* Required hardware (e.g. computers, mobiles etc)
* A designated space to work
* The manual tests are written based on application documentation

#### 1.1.3 Exit criteria defined

* All manual tests are executed
* At least 90% of manual test are passed 
* The unresoled defects have low priority
* All defects have been re-tested and confirmed as fixed

#### 1.1.4 Test scope

* __Tests in scope:__ All the features related to the NEW graphic interface of OpenCart application - which were defined in software requirement specs need to be tested: functional testing, graphic user interface testing
* __Tests not in scope:__ compatibility testing with multiple browsers/ devices, existing functionalities implemented before, performance

#### 1.1.5 Risks detected

Project risks: 

* Insufficient budget to finalize the project
* Insufficient employees
* Lack of experience for the employees to finalize the project
* It might be not enought time to finalize the project at deadline

Product risks: 

* The NEW graphic user interface is not suitable for the existing users
* The graphic user interface is not fully funtional
* There should be no better competitors
* New browsers might not be supported


#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test. It will include:

* Daily test execution progress
  
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/f4d37a9f-b7a5-4c65-8914-9434a69e54b4)

* Test Execution Metrics

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/bed1d579-6e28-474a-968d-f1a4fb6586d1)

* Traceability matrix Test Cases done on Stories
  
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/e21c90de-ba14-41e9-aef4-a377dbdcfa96)


#### Regarding Test Control, we will:

* Prioritizing the testing efforts
* Reorganizing the test environment
* Re-prioritizing the test cases

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the NEW graphic interface of OpenCart application. The following test conditions were found:

- Test the new page header and validate:
	- Store logo functionality
	- Store currency functionality
	- Shopping cart functionality
	- Seach box functionality
	- Header links functionality
	- Telephone number functionality
	- My Account functionality
- Test the new top menu and validate:
	- Dropdown on subcategories functionality
	- Categories functionality
	- Presence of top menu
- Test the slideshow and validate if the user is redirected to the product accessed from the slideshow
- Test the feature products and validate if the user is able to access feature products
- Test the footer and validate:
	- The links order
	- If the footer is present in any page
	- If the footer links redirected the user to the desired page
- Test the product page and validate all required data that a product page require to displayed regarding the documentation
- Test product compare and validate if the user is able to compare products

## 1.4 Test Design

The stories parent is an epic and can be viewed here: [Epic.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Epic.pdf)

* NEW graphic interface of OpenCart application

Based on the analysis of the specifications, the stories were created in Jira and can be viewed here: [Jira Stories.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Jira%20Stories.pdf)

* Implement the checkout page
* Implement the account creation page
* Implement the shopping cart page
* Implement the product compare page
* Implement the category product listings
* Create the product pages
* Create the footer
* Implement the featured products
* Implement the slideshow
* Create the top menu
* Implement the page header 

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are:

* On any product page all the information is displayed according to documentation
* The user is able to compare products
* Footer links redirected the user to the desired page
* Check if the footer is present on any page
* Check the links order in footer
* The user is able to access the feature products
* A new page will be displayed when accessing categories
* When the banner is clicked on, the customer will be directed to the product on the banner's page
* By clicking on the category, you will be redirected to the respective category
* The top menu will be displayed on each page
* A drop-down menu will display subcategories
* Test implementation of the my account
* Check if the telephone number is displayed and it is correctly written
* The user is able to access header links and is redirected to the desired page
* Test functionality of the search box
* Test functionality of the shopping cart
* Currency block: The customer can select which currency the store's products will be in by clicking on any of the currency icons
* Clicking on the store logo will direct the customer back to the home page of the store

TO BE ADDED - The test cases with steps can be viewed here: [test_cases.pdf]() 

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* The test cases are written for the story to be tested
* The story was implement and the code was deployed to the testing environment
* The tester is using a stable internet connection (15-20 megabits-per-second Mb/s at a minimum)
* The tester is able to use a laptop or PC with Windows operating system
* The Chrome browser is installed

## 1.6 Test Execution

* TO BE ADDED - Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf]()
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [Bugs.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Bugs.pdf)
    *  enter here bug titles



## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
* Test execution chart was generated, the final report shows.... -> describe the final report

-> enter here test execution report/chart

# 2 SQL section
