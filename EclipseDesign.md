##**ECLIPSE IN DESIGN**

- Eclipse can be used for developing the design documentation of a project like Class diagram, Sequence diagram etc.
- Eclipse has a plugin called Object Aid which generated the class diagram and sequence diagram from the source code.
- ObjectAid can be installed from [here](http://www.objectaid.net/update) with the installation instructions [here](http://objectaid.com/installation).
- The ObjectAid UML Explorer is an agile and lightweight code visualization tool for the Eclipse IDE.

- It shows your Java source code and libraries in live UML class and sequence diagrams that automatically update as your code changes. 
- It uses the UML notation to show a graphical representation of existing code that is as accurate and up-to-date as the text editor, while being very easy to use.
- Using ObjectAid all diagrams in your Eclipse workspace are updated with refactoring changes as appropriate. If necessary, they are checked out of your version control system.

##**ObjectAid : A Plugin for Eclipse**

- Objectaid is a free tool for Eclipse which can be used to automatically create  class diagrams.
- Lets consider the procedure for creating UML Class diagrams.
- After installing the plugin, from the package explorer or File menu , Create a new ObjectAid class diagram
- Click on the File package >  New > Other and select Class Diagram.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img33.png "Design1")

- While creating the diagram , you can specify what all Classifiers and Relationships among classes you need in the diagram to have  . You can also specify the Attributes and Operations of a class that you want to be shown in the diagram.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img35.png "Design1")
- You can mark Save Image in case you need the diagram in an Image file for some presentation etc.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img34.png "Design2")
- Once created , the Class diagram icon will show in package explorer.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img36.png "Design3")

- You can open and drag into it the classes whose diagram you want to create.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img37.png "Design4")
- After you drag , the diagram will appear , listing the attributes and operations were allowed while creating it. Example shown in figure below.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img38.gif "Design5")
In this case several classes are present in the same file hence it generates such a class diagram.
- Right click on a class to open the menu which has useful operations through which you can extend the diagram by adding Associates and Relationships. By clicking an operation or attribute , you can go to its source code .

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img39.png "Design6")

- If you want to change the type of attributes and operations you allowed while creating the diagram , you can also change it from this Menu.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img40.png "Design7")

##**ObjectAid Advantages**

Several unique features of ObjectAid includes:
  - Generates the diagram with simple drag and drop.
  - Any update in the code in Eclipse, UML diagram is updated as well; there is no need to reverse engineering of the source code.
  - Refactoring updates on the diagram as well as the source code. Renaming a field or moving a class, diagram simply reflects the changes without going out of sync.
  - All diagrams in Eclipse workspace are updated with refactoring changes as appropriate. If necessary, they are checked out of version control system.(Integration of Version control)
  - Diagrams are fully integrated into the Eclipse IDE. Java classes can be dragged from any other view onto the diagram, and diagram-related information is shown in other views wherever applicable.
  - The ObjectAid UML Explorer achieves all this while staying light, fast and easy to use
  - More options are available to edit the diagram by adding and removing certain features and relationships in the diagram.
  - For more information check [this](http://objectaid.com/).

##**JAVADOC IN ECLIPSE**
- Javadoc  is a documentation generator created by Sun Microsystems for the Java language for generating API documentation in HTML format from Java source code.
- We can generate the javadoc for a java project from Eclipse. Go to project > generate java doc.
- At first step, define settings for:
   - Select path for the javadoc.exe tool from the JDK
   - Classes and methods for which to generate Javadoc based on their visibility.
   - Location of the Javadoc

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img42.png "Design8")

- Generated Javadoc can be viewed in the project explorer

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img41.png "Design9")


[**NEXT**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/EclipseSourceControl.md)     

[**BACK TO CONTENTS**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/README.md)
