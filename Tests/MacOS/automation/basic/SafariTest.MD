## Test Case ID
* Basic_005
## Test Case Script Location
* https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/ChromeTest.java
## Test Case Name
* SafariTest
## Test Case Description
* Webdrivermanager check Safari version and download corresponding chromedriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ and click heading.
## Pre-conditions
* The test machine must have internet connection
* MAC OS
## Post-conditions
* Webdriver and corresponding Safari browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 12/22/21 14:06:47
## Test Case Results (Pass / Fail / Not executed / Suspended)
* Pass
---
## Test Steps
1. Step 1
	* Step Details
		* Open Safari and navigate to https://bonigarcia.org/webdrivermanager/ using chromewebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Safari open successully then navigate to https://bonigarcia.org/webdrivermanager/
	* Actual Results
		* As expected
	* Pass / Fail / Not executed / Suspended
		* Pass
2. Step 2
	* Step Details
		* Click element has id = "examples"
	* Test Data
		* N/A
	* Expected Results
		* element tagName= "body" has text value = "WebDriverManager"
	* Actual Results
		* As expected
	* Pass / Fail / Not executed / Suspended
		* Pass
---
