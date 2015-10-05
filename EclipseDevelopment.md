#**ECLIPSE IN DEVELOPMENT**

- Eclipse can be used to develop software modules in various languages.
- Languages that are supported in Eclipse include C, C++,java, ABAP, COBOL, Python, Ruby, Fortran, Birt etc.
- Let us consider Java for demonstrating the Eclipse development environment.
- Before getting started verify the Java runtime Environment.
- Select Windows in Menu Bar > preferences >Java >Installed JRE. Confirm that a JRE has been detected as shown in the diagram below.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img9.png "JRE Verification")

- Launch Eclipse which pops up a dialog box to select the workspace.
- Create a Workspace for saving all the data handled and modified in eclipse and click on OK.
- This dialog appears only if the java path variable is configured correctly else it does not launch the IDE. To configure the path variable check [here](https://java.com/en/download/help/path.xml).
- Select the menu item File > New > Project.... to open the New Project wizard
- Enter the project Name and select the version of JRE to be used and click on Finish

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img11.png "Project Start")

- After creating the project this can be seen in the project explored as shown in figure below.
- In the project explorer only a source directory and an instance of JRE is created.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img10.png "Created JRE")

- After creating the java project create a class in the source folder. Go to source package > New > Class.
- A dialog box will pop up to help create the class file. Enter the class name, package name and the stubs to be created. Click Finish.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img13.png "ProjectName")

- The class file is created with empty stubs in it.
- Include the source code in the file using the editor as show.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img14.png "ProjectBuild")

- Once the source code is completed build the project by right clicking on the package and select build project.
- Build compiles all of the source files to object files, then links them together into one executable. When there is any syntax errors it is shown in the problems view of eclipse as shown in the figure below.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img16.png "ProjectBuildAuto")

##**Java Compiler in Eclipse**
- Eclipse Java compiler
  * JCK-compliant Java compiler
  * Helpful error messages
  * Generates runnable code even in presence of errors
  * Fully-automatic incremental recompilation
  * High performance
  * Scales to large projects
- Multiple other uses besides the obvious
  * Syntax and spell checking
  * Analyze structure inside Java source file
  * Name resolution
  * Content assist
  * Refactoring
  * Searches

- Another option in Eclipse is the build automatically option where every time the code is saved the IDE compiles source code. To check this option Click on Project option in Menu bar and select build automatically.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img19.png "ProjectImport")

- We can also reuse the existing code by importing the same into the workspace. For this Right Click on the Package > Import. This will redirect you through a dialog box where the kind of file imported and the path of the file is specified.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img18.png "ProjectReuse")

- To run the project Right click on the project > Run as > Run as Java Application. The source code is executed and the results is displayed in the console view of eclipse.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img21.png "ProjectConsole")

- Ideal case if the program executes correctly the output is displayed in the console view. But when it fails, Eclipse offers a GUI based debugger which helps debugging the programs line by line.
- Open Debug perspective to proceed with debugging. Go to Perspective > open Perspective and select debug option.

- Set the break points on the lines which are to be debugged. Click on debug option a dialog box appears as a check for switching perspectives. The Debug perspective is shown below.
![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img22.PNG "ProjectDebug")



