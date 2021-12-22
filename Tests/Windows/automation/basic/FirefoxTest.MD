## Test Case ID
* Basic_003
## Test Case Script Location
* https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/FirefoxTest.java
## Test Case Name
* FirefoxTest
## Test Case Description
* Webdrivermanager check Firefox version and download corresponding geckodriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ and click heading.
## Pre-conditions
* The test machine must have internet connection
* Windows OS
## Post-conditions
* Webdriver and corresponding Firefox browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 12/21/21 14:06:04
## Test Case Results (Pass / Fail / Not executed / Suspended)
* Pass
---
## Test Steps
1. Step 1
	* Step Details
		* Open Firefox and navigate to https://bonigarcia.org/webdrivermanager/ using geckodriver.
	* Test Data
		* N/A
	* Expected Results
		* Firefox open successully then navigate to https://bonigarcia.org/webdrivermanager/
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
