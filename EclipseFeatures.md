##**ECLIPSE AND ANT BUILD**

 - ANT build is a software tool for automating build processes developed in java.
 - The main known usage of Ant is the build of Java applications. Ant supplies a number of built-in tasks allowing to compile, assemble, test and run Java applications.
 - Ant can also be used effectively to build non Java applications, for instance C or C++ applications. More generally, Ant can be used to pilot any type of process which can be described in terms of targets and tasks.
 - The most immediately noticeable difference between Ant and Make is that Ant uses XML to describe the build process and its dependencies, whereas Make uses [Makefile format](https://en.wikipedia.org/wiki/Makefile#Makefiles).
 - Ant buildfiles are just text files, to create an Ant buildfile in Eclipse: File > New > File (Enter a name for the file) Click Finish.
 - By default the Ant Editor has an association with build.xml file or File associations can be manually set using Window > Preference > General > Editors > File associations and add an association between the created xml file and the ant editor. 
 - Now, as long as the file has a .xml extension, Eclipse will consider it to be a possible Ant buildfile, and will enable Ant-related actions when it is selected. Until a file has Ant buildfile content, you will need to open it using Open With [Ant Editor](http://help.eclipse.org/juno/topic/org.eclipse.platform.doc.user/reference/ref-anteditor.htm)
 
 - Open the xml file created with the Ant Editor and add the contents as shown.
 
 ![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img51.png "Features1")
 
 - Notice the syntax coloring for property values.
 - Save the buildfile contents.
 - Select the file and run as AntBuild from its context menu.
 
  ![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img52.png "Features1")
 
 - This dialog allows the configuration of many aspects of the way an Ant buildfile is run, but for now concentrate on the Targets tab which allows the selection of which Ant targets to run and their order. Select both targets and leave the order as the default. Click on Run and the output is displayed in the console view.
 
 ##**Memory Analyzer in Eclipse**
 
 - The Eclipse Memory Analyzer is a fast and feature-rich Java heap analyzer that helps you find memory leaks and reduce memory consumption.
 - Use the Memory Analyzer to analyze productive heap dumps with hundreds of millions of objects, quickly calculate the retained sizes of objects, see who is preventing the Garbage Collector from collecting objects, run a report to automatically extract leak suspects.
 - Eclipse represents the memory utilized at that point in time by a process in a graphical representation as shown.
 
   ![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img53.png "Features2")
 
 - For more information check [here](http://help.eclipse.org/juno/index.jsp?topic=/org.eclipse.platform.doc.user/gettingStarted/qs-81_basics.htm).

##**LTTng Plug-in for Eclipse**

 - LTTng  - Linux Trace Toolkit, next generation.
 - This is a highly efficient tracing tool for Linux that can be used to track down kernel and application performance issues as well as troubleshoot problems involving multiple concurrent processes and threads.
 - It consists of a set of kernel modules, daemons - to collect the raw tracing data - and a set of tools to control, visualize and analyze the generated data. It also provides support for user space application instrumentation.
 - The LTTng Eclipse plug-in has a number of features to allow efficient handling of very large traces 
   - Support for arbitrarily large traces (larger than available memory)
   - Support for correlating multiple time-ordered traces
   - Support for zooming down to the nanosecond on any part of a trace or set of traces
   - Views synchronization of currently selected event
   - Efficient searching and filtering of events
   - Support for trace bookmarks
 - For more information about LTTng, refer to the [project site](http://lttng.org/).
 
 ##**Callgraph plug-in for Eclipse**
 - A graphical explorer for call and class hierarchies. Designed to help understand complex relations in larger scale applications.
 - This plug-in allows you to profile C/C++ projects directly within the Eclipse IDE, providing various runtime details such as:
     - The relationship between function calls
     - Number of times each function was called
     - Time taken by each instance of a function (relative to the program's execution time)
 - Time taken by all instances of a function (relative to program's execution time)
 - Eclipse Callgraph uses SystemTap to perform function traces. For more information about SystemTap, refer to the [here](http://sources.redhat.com/systemtap/SystemTap_Beginners_Guide).
 - This leverages the internal platform Call Hierarchy and Search mechanisms.
 - For more information check [this](https://marketplace.eclipse.org/content/callgraph-viewer#sthash.CVhMjnkx.dpuf).
 


[**NEXT**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/Conclusion.md)     

[**BACK TO CONTENTS**](https://github.com/pkdevaraj/Presentations/blob/gh-pages/README.md)
