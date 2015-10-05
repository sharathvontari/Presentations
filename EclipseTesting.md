##**ECLIPSE IN TESTING**
- A software test is a piece of software which executes another pierce of software and validates if that code results in the correct state (state testing) or executes the correct sequence of events (behavior testing).
- Software unit tests allow the developer to verify that a piece of program logic is correct.
- There are several kinds of testing that has been integrated on Eclipse. For demonstration let us consider Junit testing here.
- A JUnit test is a method contained in a class which is only used for testing. This is called a Test class.
- To start with junit development in eclipse download Junit archive and save it in a directory.
- Open eclipse -> right click on project and click on property > Build Path > Configure Build Path and add the junit-4.10.jar in the using Add External Jar button.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img27.jpg "projectTest")

- Junit plugin is required to run the Junit tests and is a part of JDT.
- To install JDT check [here](http://www.eclipse.org/jdt/)
- To use JUnit you must create a separate .java file in your project that will test one of your existing classes.
- In the Package Explorer area on the left side of the Eclipse window, right click on the class you want to test and click New → JUnit Test Case.
- A dialog box will pop up to help you create your test case.Make sure that the option at the top is set to use JUnit 4, not JUnit 3. Click Next.(shown in figure below)

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img29.png "projectTestpop")

- This creates a test file with built in skeleton of the test cases of the methods in the class and the setup and the teardown methods.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img31.png "projectTestskeleton")

- Write the test cases for individual modules or methods and run the test cases. To run the test cases right click on project > run as >junit test.
- Once the test case is executed it shows the results as shown in in the Junit view of Eclipse.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img30.png "projecttestresult")

- The results are of 3 kinds
  * Errors : Test Cases with errors
  * Failures : Test cases with wrong logic
  * Success : Test cases that passed the test.




[**NEXT**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/EclipseDesign.md)     

[**BACK TO CONTENTS**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/README.md)
