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

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/404c1537-c869-4dd0-a6b9-caa5ce47fd24)


* Test Execution Metrics

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/bed1d579-6e28-474a-968d-f1a4fb6586d1)

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

The test cases with steps can be viewed here: [TestCases.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Zephyr%20TestCases.pdf)
## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* The test cases are written for the story to be tested
* The story was implement and the code was deployed to the testing environment
* The tester is using a stable internet connection (15-20 megabits-per-second Mb/s at a minimum)
* The tester is able to use a laptop or PC with Windows operating system
* The Chrome browser is installed

## 1.6 Test Execution

Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Zephyr%20Tests%20%2B%20Executions%20%2B%20Results.pdf)

* Bugs have been created based on the failed tests. The complete bug reports can be found here: [Bugs.pdf](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/blob/main/Bugs.pdf)
    *  The user is not redirected to add a review from product page
    *  The social media share buttons are not displayed on any product page
    *  In the product comparison page the products are not displayed
    *  The shopping cart button on feature products is not according to technical documentation
    *  The user is redirected to the product page when adding to the shopping cart the last 2 products from feature products
    *  The link name "Gift Certificates"/"Affiliate" should be "Gift Vouchers"/"Affiliates" in the "Extras" category from footer
    *  The links from the "Information" category redirect the user to a page without content, only title is displayed
    *  Incorrect order of "Information" category links from footer
    *  When the user clicks on the slideshow banners is redirected to a wrong page or product page is not opened
    *  Internal server error page is displayed when searching for a product

## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here:

Tracebility matrix - Stories & Test Cases

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/e21c90de-ba14-41e9-aef4-a377dbdcfa96)

Tracebility matrix - Stories & Bugs

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/59c70def-41d3-4f13-b9a3-940cddd3bcb4)

* TO BE ADDED - Test execution chart was generated, the final report shows.... -> describe the final report
  
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/0f3e4eab-0455-4a8d-a142-831c7a9058ae)

# 2 API section

In this section will be deschide how API testing was performed. 

API base URL: http://192.168.1.174:8080/alina/index.php?route=

| Endpoint  | Method | Parameters | What it does |
| :---: | :---: | :---: | :---: |
| api/account/login  | POST | username/ key as form-data | Return API Token |
| api/sale/cart&api_token=your_token | GET | api_token | Return cart products |
| api/sale/cart.add&api_token=your_token | POST | api_token and in body as form-data product_id and quantity | Add products to cart |
| api/sale/cart.remove&api_token=your_token | POST | api_token and in body as form-data product key as key | Remove products from cart |
| api/sale/voucher.add&api_token=your_token | POST | api_token and in body as form-data form_name / from_email/ to_name / to_email / voucher_theme_id / message / amount | Add voucher |
| api/sale/voucher.remove&api_token=your_token | POST | api_token and and in body as form-data add product key as key | Remove voucher |

## api/account/login ## POST 

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/23d86580-41c7-495a-9ab5-6d0af359b488)

## Response ##
``` json
{
  "status": "success",
  "message": "Token generated successfully.",
  "data": {
    "api_token": "a601dcaaf2c93d8c89ae641045"
  }
}
```
## api/sale/cart.add&api_token=your_token ## POST

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/22a27e37-835e-4863-a3cf-10f7cb536309)

## Response ##
``` json
{
  "status": "success",
  "message": "The product was added successfully to the cart.",
  "data": {
    "product_id": "41",
    "quantity": "1",
    "product_name": "Iphone 12s",
    "timestamp": "2023-07-21T10:30:00Z"
  }
}
```

## api/sale/cart&api_token=your_token ## GET 

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/a5743217-19f3-47a3-bf90-ffd2af42ce48)

## Response ##
``` json
{
  "status": "success",
  "message": "Cart products retrieved successfully.",
  "data": {
    "cart_id": "43",
    "products": [
      {
        "product_id": "23",
        "product_name": "LG Monitor",
        "price": 192.99,
        "quantity": 2
      },
      {
        "product_id": "41",
        "product_name": "Iphone 12s",
        "price": 1231.49,
        "quantity": 1
      }
    ]
  }
}
```

## api/sale/cart.remove&api_token=your_token ## GET 

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/a73c39cf-7afa-4e67-b867-0c66d2c8c3ad)

## Response ##
``` json
{
  "status": "success",
  "message": "Product removed from cart successfully.",
  "data": {
    "cart_id": "43",
    "removed_product": {
      "product_id": "23",
      "product_name": "LG Monitor"
    }
  }
}
```

##  api/sale/voucher.add&api_token=your_token ## POsT

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/88db6e8a-b7da-4a6c-99a5-0728cfcf8f53)


## Response ##
``` json
{
  "status": "success",
  "message": "Voucher added successfully.",
  "data": {
    "voucher_key": "0",
    "from_name": "a",
    "to_name": "b",
    "message": "waw",
    "voucher_amount": 100
  }
}
```

##  api/sale/voucher.remove&api_token=your_token ## POsT

## Request ##
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/e50a8093-bdb8-4d69-ac8d-529305638ec9)

## Response ##
``` json
{
  "status": "success",
  "message": "Voucher removed successfully.",
  "data": {
    "voucher_key": "0"
  }
}
```

## Tests Examples ##

* Check if status code is 200
```
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
* Check if response body contains string api_token
```
pm.test("Body matches string", function () {
    pm.expect(pm.response.text()).to.include("api_token");
});
```
* Check if response time is less than 200 ms
```
pm.test("Response time is less than 200ms", function () {
    pm.expect(pm.response.responseTime).to.be.below(200);
});
```
## Test Results Examples ##

![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/05d1f292-b3b8-4360-9b46-8e26fe08016f)


# 3 SQL section

In this section will be deschide how SQL testing was performed, in order to to that we will create 2 tables Categories and Products and perform different transactions to check if data is correctly added/updated/deleted.

* Categories
   * Create the table
 
		```sql
		CREATE TABLE categories (
		    category_id INT PRIMARY KEY,
		    category_name VARCHAR(255) NOT NULL
		);
		```
   * Add new category
 
		``` sql
		INSERT INTO categories (category_id, category_name) VALUES (1, 'Electronics');
		```
   
   * Check if category was successfully added

		``` sql
		SELECT category_id, category_name FROM categories WHERE category_name = 'Electronics';
		
		/*
		SELECT QUERY RESULT
		*/
		
		+-------------+--------------+
		| category_id | category_name |
		+-------------+--------------+
		|      1      | Electronics  |
		+-------------+--------------+
		```
	     
* Products
   * Create the table
 
		``` sql
		CREATE TABLE products (
		    product_id INT PRIMARY KEY,
		    product_name VARCHAR(255) NOT NULL,
		    category_id INT,
		    price DECIMAL(10, 2) NOT NULL,
		    description TEXT,
		    stock_quantity INT NOT NULL,
		    creation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
		    last_updated TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
		    FOREIGN KEY (category_id) REFERENCES categories(category_id)
		);
		```
   * Insert 10 products
     
		``` sql
		INSERT INTO products (product_name, category_id, price, description, stock_quantity)
		VALUES
		    ('Laptop', 1, 999.99, 'High-performance laptop', 50),
		    ('Smartphone', 1, 599.99, 'Latest model smartphone', 100),
		    ('T-shirt', 2, 19.99, 'Comfortable cotton t-shirt', 200),
		    ('Jeans', 2, 49.99, 'Classic denim jeans', 150),
		    ('Running Shoes', 3, 79.99, 'Breathable running shoes', 80),
		    ('Watch', 4, 149.99, 'Elegant wristwatch', 30),
		    ('Backpack', 5, 39.99, 'Durable travel backpack', 120),
		    ('Camera', 6, 799.99, 'Professional DSLR camera', 25),
		    ('Desk Lamp', 7, 29.99, 'Adjustable LED desk lamp', 90),
		    ('Sunglasses', 8, 59.99, 'UV protection sunglasses', 70);
		```
   * Check if products were added successfully
		
		``` sql
		SELECT product_id, product_name, category_id, price, description, stock_quantity FROM products;
		
		/*
		SELECT QUERY RESULT
		*/
		
		+------------+--------------+-------------+--------+-------------------------------+----------------+
		| product_id | product_name | category_id| price  | description                   | stock_quantity |
		+------------+--------------+-------------+--------+-------------------------------+----------------+
		| 1          | Laptop       | 1           | 999.99 | High-performance laptop       | 50             |
		| 2          | Smartphone   | 1           | 599.99 | Latest model smartphone      | 100            |
		| 3          | T-shirt      | 2           | 19.99  | Comfortable cotton t-shirt   | 200            |
		| 4          | Jeans        | 2           | 49.99  | Classic denim jeans          | 150            |
		| 5          | Running Shoes| 3           | 79.99  | Breathable running shoes     | 80             |
		| 6          | Watch        | 4           | 149.99 | Elegant wristwatch           | 30             |
		| 7          | Backpack     | 5           | 39.99  | Durable travel backpack      | 120            |
		| 8          | Camera       | 6           | 799.99 | Professional DSLR camera     | 25             |
		| 9          | Desk Lamp    | 7           | 29.99  | Adjustable LED desk lamp     | 90             |
		| 10         | Sunglasses   | 8           | 59.99  | UV protection sunglasses    | 70             |
		+------------+--------------+-------------+--------+-------------------------------+----------------+
		```
  * Update 6 products and check if the update was successful
	``` sql
	UPDATE products SET price = 899.99, stock_quantity = 60 WHERE product_id IN (2, 4, 6, 8, 10, 12);
	SELECT product_id, product_name, price, stock_quantity FROM products WHERE product_id IN (2, 4, 6, 8, 10, 12);
	
	/*
	SELECT QUERY BEFORE UPDATE
	*/
	
	+------------+--------------+--------+----------------+
	| product_id | product_name | price  | stock_quantity |
	+------------+--------------+--------+----------------+
	| 2          | Smartphone   | 599.99 | 100            |
	| 4          | Jeans        | 49.99  | 150            |
	| 6          | Watch        | 149.99 | 30             |
	| 8          | Camera       | 799.99 | 25             |
	| 10         | Sunglasses   | 59.99  | 70             |
	| 12         | Headphones   | 79.99  | 100            |
	+------------+--------------+--------+----------------+
	
	/*
	SELECT QUERY AFTER UPDATE
	*/
	
	+------------+--------------+--------+----------------+
	| product_id | product_name | price  | stock_quantity |
	+------------+--------------+--------+----------------+
	| 2          | Smartphone   | 899.99 | 60             |
	| 4          | Jeans        | 49.99  | 60             |
	| 6          | Watch        | 899.99 | 60             |
	| 8          | Camera       | 899.99 | 60             |
	| 10         | Sunglasses   | 59.99  | 60             |
	| 12         | Headphones   | 79.99  | 60             |
	+------------+--------------+--------+----------------+
	```
  * Delete 5 products

	``` sql
	DELETE FROM products WHERE product_id IN (2, 4, 6, 8, 10);
	SELECT product_id, product_name FROM products;
	
	
	/*
	SELECT QUERY AFTER DELETE
	*/
	
	+------------+--------------+
	| product_id | product_name |
	+------------+--------------+
	| 1          | Laptop       |
	| 3          | T-shirt      |
	| 5          | Running Shoes|
	| 7          | Backpack     |
	| 9          | Desk Lamp    |
	+------------+--------------+
	```

