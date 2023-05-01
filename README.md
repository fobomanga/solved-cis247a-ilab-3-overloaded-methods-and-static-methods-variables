Download Link: https://assignmentchef.com/product/solved-cis247a-ilab-3-overloaded-methods-and-static-methods-variables
<br>
<p class="ui header product-top-header" title="CIS247A iLab 3: Overloaded Methods and Static Methods / Variables Solution">CIS247A iLab 3: Overloaded Methods and Static Methods / VariablesGeneral Questions – General General Questions

iLab 3 of 6: Overloaded Methods and Static Methods / Variables

Scenario and SummaryThe objective of the lab is to take the UML Class diagram and enhance last week’s Employee class by making the following changes:

Create a static variable called numEmployees that holds an int and initialize it to zero. This will allow us to count all the Employee objects created in the main class. Increment numEmployees in all of the constructors Add overloaded versions of setDependents and setAnnualSalary that accept strings. This way, we will have two “set” methods for both dependents and annual salary; one that accepts a string, and one that accepts its default data type.

Deliverables

Due this week:

Capture the Console output window and paste it into a Word document. Zip the project folder files. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Diagram

Employee – firstName : string – lastName : string – gender : char – dependents : int – annualSalary : double – static numEmployees : +Employee() +Employee(in fname : String, in lname : String, in gen : char, in dep : int, in sal : double) +calculatePay() : double +displayEmployee() : void +getFirstName() : String +setFirstName(in name : String) : void +getLastName() : String +setLastName(in name : String) : void +getGender() : char +setGender(in gen : char) : void +getDependents() : int +setDependents(in dep : int) : void +getAnnualSalary() : double +setAnnualSalary(in sal : double) : void +setAnnualSalary(in sal : String) : void

The following attribute has been added:

– static numEmployees: The following behaviors have been added:

+ static getNumEmployees( ) : int+ setDependents(in dep : String) : void+ setAnnualSalary(in sal : String) : void

STEP 2: Create the Project

You will want to use the Week 2 project as the starting point for the lab.

STEP 3: Modify the Employee

Using the UML Diagrams from Step 1, code the changes to the Employee class. Create a static numEmployees variable and initialize it to zero. Increment numEmployees by 1 in each of the constructors. Create an overloaded setDependents method and this time make the parameter a string. Create an overloaded setAnnualSalary method and this time make the parameter a string.Remember that you will have to convert the string in the above two “set” methods to the data type of the attribute. Make the getNumEmployees a static method. (This way, you can call it with the class name instead of an object name.)

Be sure you follow proper commenting and programming styles (indentation, line spacing, etc.).

STEP 4: Modify the Main Method

In the Main class, create code statements that perform the following operations. Be sure you follow proper commenting and programming styles (header, indentation, line spacing, etc.). Note that several of the steps below were accomplished in last week’s assignment. New steps are in bold.

Create an Employee object using the default constructor. Prompt for and then set the first name, last name, and gender. Consider using your getInput method from Week 1 to obtain data from the user for this step as well as Step 3. Prompt for and then set dependents and annual salary using the new overloaded setters. Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the Employee Information. Display the number of employees created using getNumEmployees. Remember to access getNumEmployees using the class name, not the Employee object. Create a second Employee object using the multi-arg constructor, setting each of the attributes with the following values: “Mary”, “Noia”, ‘F’, 5, 24000.0 Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the employee information for the second Employee object. Display the number of employees created using getNumEmployees. Remember to access getNumEmployees using the class name, not the Employee object.

STEP 5: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

STEP 6: Screen Prints

Capture the Console output window and paste it into a Word document. The following is a sample program output.

Screenshot of program that reads: ************** Employee 1 ************** Please enter your First Name Nana Please enter your Last Name Liu Please enter your Gender Female Please enter your Dependents 2 Please enter your Annual Salary 60000 Employee Information ________________________________________ Name: Nana Liu Gender: F Annual Salary: 60000.00 Weekly Salary: 1153.85 — Number of Employee Object Created — Number of employees: 1 ************** Employee 2 ************** Employee Information _______________________________________ Name: Mary Noia Gender: F Dependents: 2 Annual Salary: 150000.00 Weekly Salary: 2884.62 — Number of Employee Object Created — Number of employees: 2 The end of the CIS247C Week3 iLab. Press any key to continue…

STEP 7: Submit Deliverables

Capture the Console output window and paste it into a Word document. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

5/5 - (4 votes)