# GoogleMaps
Validate the functionality of Google Maps

**Notes:** 
1. All the points mentioned in Assessment are **Completed** and are **executable** without any errors. 
2. **Cucumber** and **JUnit** is used with **JAVA** language for automation of Google Maps.
3. JSON Report, HTML Report & Junit Report is integrated to see the results. These files contained in repository shows all test results **Passed.**

**Description of Folder Structure:** 
1. StepDefinition(GoogleMap.java) and TestRunner java class files are present in src/test/java package.
2. FeatureFile(GoogleMap.feature) and drivers folder is present in src/test/resources package. 
3. data folder contains the .txt file generated while code execution for keeping the travel time.
4. target folder contains all the reports which are generated: **JSONReport, JUnitReport & HTMLReport**

**Description of Files:**
1. **GoogleMap.java** : This is step definition file which keeps java code used to automate the steps present in feature file
2. **TestRunner.java** : This file helps to combine test cases in feature file to their corresponding methods in step definition file
3. **GoogleMap.feature** : Contains the test cases in Gherkin format
4. **routes.txt** : This file is generated while code execution for keeping the travel time
5. **report.JSON** : Results of Suite run in json format 
6. **Report.xml** : Results of Suite run in xml format
7. **HTMLReports.html :** Results of Suite run in html format
8. **pom.xml** contails all the dependencies used

**Ways to run the project on eclipse:** 
1. Open TestRunner.java file -> Right click on file -> Run As '1 JUnit Test'
2. Open GoogleMap.feature file - Right click on file - > Run As '1 Cucumber feature'
