##**ECLIPSE IDE**

by- Praveen Kumar Devaraj (prde1873) and 
    Sharath Vontari (shvo9452)

###**INTRODUCTION**

What is IDE : Integrated Development Environment 
- Tool with features required for software development.
- Eclipse is one such open source IDE used for developing softwares.
- Can be used to develop software in C, C++,java, ABAP, COBOL, Python, Ruby etc.
- Provides an open platform for application development tools run on a wide range of operating systems.
- Can be used in any phase of development like Design, Development, Testing etc.
- Provides features for seamless integration of software modules developed individually.
- First release of the eclipse  project was made in 2001 and has been growing since then.
- Eclipse created by OTI and IBM teams responsible for IDE products
   - IBM VisualAge/Smalltalk (Smalltalk IDE) 
   - IBM VisualAge/Java (Java IDE)
   - IBM VisualAge/Micro Edition (Java IDE)

###**What is Eclipse**
- Eclipse is a universal platform for integrating development tools.
![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/Img1.PNG "EclipseArchitecture")

**Plug-in** - smallest unit of Eclipse function
Example – CDT, ObjectAid etc.

**JDT** - Provides the tool plug-ins that implement a Java IDE supporting the development of any Java application.

**Eclipse Platform** - Common base for all development, Includes runtime,frameworks etc

**JVM** - JAVA VIRTUAL MACHINE An abstract computing machine that enables a computer to run a Java program


###**Eclipse User-Interface**
User Interface of Eclipse can be changed according to the user preferences. This is the typical UI provided.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img2.png "EclipseArchitecture1")

The position of any forms (views in Eclipse) can be customised according to the user requirements.

##**Why Eclipse**

There are several reasons to use Eclipse. A few of them include:
- Open Source – Free of Cost.
- Supports most of the programming languages with appropriate plugins.
- Single tool that can be used for design, development, testing etc.
- User Friendly (Intuitive User Interface).
- Can be integrated with several Version management (Ex: Perforce etc) and build softwares(Ex: ANT).
- Available on most of the platforms

##**Getting Eclipse**

- Download the latest version from [here](http://www.eclipse.org/).
- You may need to install Java SDK1.6 or JRE if you haven’t from [here](http://www.oracle.com/technetwork/indexes/downloads/index.html#java).
- After installation the path variable is to be set to the bin folder of java installation.
- Unpack the package and run eclipse.exe in windows or eclipse in Linux.

##**Plugins**

- Eclipse is an extensible platform for building IDEs. It provides a core of services for controlling a set of tools working together to support programming tasks. Tool builders contribute to the Eclipse platform by wrapping their tools in pluggable components, called Eclipse plug-ins.
- A plug-in connects with a universe of other plug-ins to form a running application.
- In short Plug-in is the smallest unit of Eclipse.
- When a plug-in wants to allow other plug-ins to extend or customize portions of its functionality, it will declare an extension point. The extension point declares a contract, typically a combination of XML markup and Java interfaces, that extensions must conform to. Plug-ins that want to connect to that extension point must implement that contract in their extension.
- Extension point is a named entity for collecting “contributions” Example: Extension point for workbench preference User Interface.
- This is specified in the manifest.xml file of every plugin.

###**Typical arrangement in Plugin Architecture**

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/Img3.png "PluginArchitecture1")

- **Plug-in A**
   - Declares extension point P
   - Declares interface I to go with P
- **Plug-in B**
   - Implements interface I with its own class C
   - Contributes class C to extension point P
- Plug-in A instantiates C and calls its I methods

##**Plugin Installation**

- Plugins are mostly in java and can be installed either directly from the repository using the url or by downloading the package and importing the same.
- To learn how to install the plugin directly from the repository [check this](https://www.youtube.com/watch?v=T7t5daTM-T8)

##**Eclipse Runtime**
- The Eclipse runtime defines the plug-ins (org.eclipse.osgi and org.eclipse.core.runtime) on which all other plug-ins depend and is responsible for defining a structure for plug-ins and the implementation details of the same.
- The runtime is also responsible for finding and executing the main Eclipse application and for maintaining a registry of plug-ins, their extensions, and extension points.
- The runtime also provides utilities, such as logging, debug trace options, adapters, a preference store, and a concurrency infrastructure.

##**Eclipse Platform Architecture Detailed Overview**

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/Img4.PNG "EclipseArchitecture3")

The JDT project provides the tool plug-ins that implement a Java IDE supporting the development of any Java application, including Eclipse plug-ins.

The Plug-in Development Environment (PDE) provides tools to create, develop, test, debug, build and deploy Eclipse plug-ins, fragments, features, update sites and RCP products.

SWT – Standard Widget Toolkit - Used for generic low level graphics and widget set.

JFace - UI frameworks for common UI tasks

[**NEXT**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/EclipseDevelopment.md)     

[**BACK TO CONTENTS**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/README.md)
