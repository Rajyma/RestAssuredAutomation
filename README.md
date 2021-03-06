# API-Testing-REST-Assured-Framework

**API** = https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false

**Acceptance Criteria:**
*Name = "Carbon credits"
*CanRelist = true
*The Promotions element with Name = "Gallery" has a Description that contains the text "Good position in category"

# Steps to Import the project in eclipse and execute test suite 

**Technology Used:**
1. RestAssured Java API
2. TestNG Framework 
3. Report and logger for generating reports and logs.

**Github repository:**  https://github.com/Rajyma/RestAssuredAutomation

**Steps to import project**
- Download repo from [https://github.com/Rajyma/RestAssuredAutomation] [RestAssuredAutomation.zip]  unzip it
- Go to Eclipse > File > Import > Maven > Existing Maven Projects into Workspace
- Click on Next 
- Click on Browse
- Select the Folder “RestApiTesting”
- Click on Open
- Click Finish

Note: Once you Imported the project in eclipse Make sure the project directory is there. 

See Example below: This is the folder structure . 


**Note:**
Once you have same folder structure imported wait for a while until maven download all the dependencies. 

![image](https://user-images.githubusercontent.com/26476263/162620329-d7900cf4-0560-45a3-a677-735ff190a8d3.png)



**Now you all set to run the project.**

### It has following this implemented. 
1. Base Class
2. Test Case Class
3. Listeners Class


 **Steps to Run the Test suite using TestNG**

------------


- Right click on testng.xml file in the project directory level
Select Run As >  TestNG Suite



![image](https://user-images.githubusercontent.com/26476263/162620378-f3f22de1-0348-4da4-b657-0394435bc6e9.png)


![image](https://user-images.githubusercontent.com/26476263/162620484-9b60c3dc-b616-47bf-b35f-54e3e5434f7f.png)


*Note: Now your test suit is running. It will log all the success or errors on the eclipse console*


**Steps to see the results using report.html**

- Go to Reports Directory
- Right click ExtentReport.html > Open With WebBrowser
- This will open the ExtentReport.html in WebBrowser and it will show the entire test suite report
<ROOT_PROJECT>/reports/index.html

![image](https://user-images.githubusercontent.com/26476263/162618695-fc7a47c5-70a2-4552-8186-fc7525276267.png)


**Note:**
- Entire test suite is verified and work as expected with no errors. 




Regards,
Rajesh

Have a great day


