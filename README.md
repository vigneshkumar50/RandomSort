# RandomSort
Sort Application Setup Guide

Sort Application:
Sort a given amount of numerical values by randomly change position of the values in ascending order. Also displays all the persisted results.
Technology Used:
Spring Tool Suite, Spring Boot, Bootstrap, AngularJS, Java 1.8, Apache Commons Lang3 API, Log4j
Setup and Run application:
Step to Setup and Run:
1.	Download and unzip the source repository for this guide 
2.	Open Spring Tool Suite.
3.	Go to File -> Import
4.	Select Existing Maven Projects into Workspace and click on Next button.
 
5.	Select Root Directory of extracted source folder.
6.	Click Finish.
 




7.	Press Ctrl+Shift+R to open java resource.
8.	Enter SortApplication.java
9.	Click on Open button.
 
10.	Right click on the SortApplication.java source file. Go to Run As -> Java Application

 



11.	Make sure your embedded server started.
 
12.	Hit application URL http://localhost:8080/
13.	Displays Sort Application page.
 

14.	Enter un sorted numbers and click on Sort Numbers button. 
 
15.	Displays Sorted numbers in ascending order, duration, changes of positions.
 
Follow below steps to test Negative Scenario.
1.	Enter invalid numbers. 
2.	Displays error message as “The given numbers are invalid.”
 





Run through SortNumbers-0.0.1-SNAPSHOT.jar:
1.	Download SortNumbers-0.0.1-SNAPSHOT.jar 
2.	Navigate to download directory
3.	Double click on the SortNumbers-0.0.1-SNAPSHOT.jar file.
4.	Hit URL http://localhost:8080/
5.	Enter un sorted numbers and click on Sort Numbers button.
6.	Displays Sorted numbers in ascending order, duration, changes of positions.

Sample Inputs:
  Un sorted numbers:
  13,14,86,21,3,38,74,33,22,34,78,74,32,80,62,75,2
  49,8,7,81,9,46,62,53,83,49,39,76,55,15,62,7,45
  60,55,48,90,91,46,12,73,77,43,53,31,89,47,32,77,45
  5,48,42,35,13,29,55,84,49,95,74,24,70,43,47,12,62
  28,9,72,64,46,87,99,84,93,100,71,24,63,55,37,59,68

