##**ECLIPSE IN SOURCE CONTROL**

- Source Control or Version Control is the management of source code of softwares and other files.
- These can be used to track the changes and revert back if necessary without affecting the other modules. Each changes made are identified by a unique Identifier.
- Examples include : Perforce, Git, ClearCase, Vault etc.

- ECLIPSE has been integrated with a plugin called Egit to access Git repositories.
- For instructions to install the Egit plugin into Eclipse click [here](https://www.youtube.com/watch?v=AhSOyDi-P18).
- Git is a distributed SCM(), which means every developer has a full copy of all history of every revision of the code, making queries against the history very fast and versatile.
- This is one of the major features of Eclipse because of which it is used in industrial developments as well. It can be integrated with many public and private Source Control tools.
- Examples : Perforce – P4Eclipse, Git – Egit etc.

##**EGIT - Plugin for Git in Eclipse**
- Lets consider an example of Egit for the Source Control in Eclipse.
- Install Egit plugin on Eclipse from [here](http://www.eclipse.org/egit/download/).
- Create a sample project in any language and save it.
- For Ex : a project named Test is created here.
- Right Click on the project and select Team > Share Project.
- Share the project on Git and this allows you to create a local repository for the project if it is not created previously.
- To create a repository click on the Create button in the pop-up and specify a name. A local repository is created with the name specified and initializes Git in the repository. This is equivalent to executing “git init” command in the repository.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img44.png "projectSC1")

- Once the repository is created and initialized the structure in the project explorer displays the repository name and the branch name in git if any. In the example below the project is in LocalgitRep directory and on master branch.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img45.png "projectSC2")

- To add the changes made into the local repository we use the commit option. This pushes all the data in the staging area into the local workspace.
- To commit right click on the project and select team and check commit option as shown.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img46.png "projectSC3")

- After checking the commit option a pop up is displayed where we fill the commit message and select the files individually which are to be committed.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img47.png "projectSC4")

- After the changes are committed we can check the branch and the commit changes in the history view of eclipse. To view this right click on the project and select show In history.
- History View shows the author , branch information, commit messages and their Ids, Authored Date and the date of each commit. Ex : In figure below, this has only one commit on Master branch.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img48.png "projectSC5")

- All the changes committed are now saved in the local repository and not in the server.
- To push the changes from the local repository to the remote repository we use the push option available when we right click on project and select Team.
- A pop up appears when clicked on Push which requests for the url of the repository and the user credentials to authenticate the user.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img49.png "projectSC6")

- Successful push sends the changes to the remote repository and can be viewed on github account of the user.

![alt text](https://github.com/pkdevaraj/Software-Engineering-Presentations/blob/master/images/img50.png "projectSC7")

- Eclipse offers a GUI based access to Git and is integrated to the development environment which makes it easier to use.
- Similarly Eclipse offers a wide range of plugins for many Source Control SCMs.
- More information on Egit can be found [here](https://wiki.eclipse.org/EGit/User_Guide).






