                                          Universidad autónoma de ciudad Juárez
                                
                                   Departamento de ingeniería eléctrica y computación
                         
                              
                        
  ![uacjlogo.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/uacjlogo.png)

                                                                                                               Work Tools Management
                                                                                                 
                                                                                                 Software requirements Specification

                                                                                                                        Raul Lucero
                                                                                                                        
                                                                                                                        May 16th 2019


1.0 Introduction

Telmex (Telefonos de Mexico) it is a large company in the business of communications in Mexico.
A TELMEX plant at Ciudad Juarez lack of tools inventory, instead of using software to automatize processes, they face several problems
and difficulties to control the management of every work tool that is being used due to traditional or obsolete methods as using paper.

1.1 Purpose

The purpose of this document is to give a detailed description of the features, requirements and what the system should do and the way
it operates.

The document is meant to be used by the stakeholders of the project for the development processes and other stages.

1.2 Scope
  
This software will be a work tools management for Telmex company. It will solve manual and paper doing processes problems just as
slownessprocedures and confusion troubles that causes equipment loses by using software automatization, which allow the tool manager to
have control of the work tools being used, available items, and identify the number of objects in real time as well is meant to register
when an item has been recollected from the technical, storing information such as date and hour of the order and the identity of the
employer who ask for the tool. 

A database will be used to recollect the tools information just as date, name of tool, ID tool, employee ID, etc.
In case of loss  of tools or material and malfunction, as well as any reason or circumstance that implicates the use of some other tools 
not provided in first instance by the company it is imperative for the technical to ask for new tools to the tools manager who will
operate the software application to ease the tools to the technical and interact with the tools supplier to add new tools to the system
or ask for more if it is needed. Also, supervisor of management tools department will check all the processes involved to avoid and
solve any possible anomaly.

1.3 Glossary

![glossary1.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/glossary1.png)

1.4 References

Davis, A., & Overmeyer, S. (1993). Identifying and measuring quality in a software requirements specification. Baltimore: Proceedings
First International Software Metrics Symposium.

Dobing, B. (2006). "How UML is used". COMMUNICATIONS OF THE ACM.

Mariscal, J. (2005). New trends in the Latin American telecommunications market: Telefonica & Telmex. ELSEVIER.

1.5 Overview

The next content gives information of the functionality of the system, the specific requirements, such as functional and nonfunctional
using high-level language to give place to a more technical terminology in the chapter below.

The document also uses technical language and is meant to be used by the development team, including more detailed description about
requirements.

In general, describes the whole project and its characteristics using different languages in order to communicate with different 
readers as we all any stakeholder or part of the deveploment team, and different purposes too.

2.0 Overall description

The Management Tool should be an intuitive interface compound by interface, database server, in the software aspects.
The human aspects play the most important role, as actors, the technical request for tools that is needed and the manager tool operates
and edit the list of tools, the name, the pieces available, the ID, etc.

The technical request for a tool and the manager search for the tool if its available in the storage,select the item  and
automatically decrease the amount and then save the changes,and a small report is generated, which contained the employer number and the
date request for control aspects.

A connection must be made between the interface compound of graphic buttons and the database server where all the data will be stored.
The buttons displayed to operate the interface are:
Edit, Remove, Add, Increase, Decrease, Search Bar, Go Back. In order to a proper software performance.

2.1 Product perspective 

The product is expected to be a single and independent entity, not related with any other component or large system.

The inventory software is a common application used in all large and small companies around the world to have control of their objects 
and items to have a record of loss and malfunction tools or material. It is considered a priority in the modern world, as well as the
use of database to display information and be able to add, edit and remove data.

 A graphic representation of the processes involved in the department for a better understanding is explained in the diagram below.

![Work Tools Diagram.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/Work%20Tools%20Diagram.png)

2.2 Site adaptation requirements

* A database server should exist already in the company to implement the created tables.

* A laptop or computer desktop in optimal conditions should be available for the software implementation.

* A laptop or computer desktop should have the minimum performance requirements (such as processor, RAM memory, etc.) to run a database
server in a reasonable amount of time without any difficulties.

* Java environment should be installed on computer to run the software successfully.

 2.3 Product functions
 
The software would allow to add, edit and remove items from the cellar in real time to have control over the database.
Also, the manager will have control increase or decrease the number of available tools by selecting two different colored arrows for up
and down buttons. 

Information about requested tools are saved on the system for future references and security, such as date of requested tool, ID of 
employees, etc. 
The connection with the database would allow to view the available tools on the cellar with additional information such as the existing
unities, as well as the not available work tools in real time.

The manager tool could search any tool by typing its identification number or tool name using an intuitive interface by selecting 
buttons.

Some changes such as delete items can be undone to avoid accidental loss of memory.


2.4 Interfaces

The interface is a simple screen created on JAVA graphic environment making use of buttons to ease the application use.

The interface is compound by a soft interface (not full of plenty action buttons or useless information), which contained a list of work
tools containing its respective ID, and the manager can add new tool data, also edit or remove it by selecting the buttons displayed on
screen.

Also, it has the search bar to look for a specific tool using name product or ID tool.

The interface has no priority for esthetic aspects including special colors, shapes or other graphical aspect. The style it could be 
considerate minimalist.

All the main features of the interface  remains in one single screen with smalls secundary windows that appears in case of system
notifications like confirm actions or warning.

The interface is connected to a database to store tools information, such as register date information of the order, availability of the
item, and also to store new tools to the system so any change will impact the database in real time.

The screen is a GUI compound of buttons to operate  the tools information, a list with columns containing tools information is displayed
on the screen and enables scrolling to see the full list.

The graphic buttons displayed on the screen are Add,Edit,remove and Save. When the user select a requested tool the manager double click 
on it and a small second screen appears containing buttons to  confirm or denied action.

The first screen begins with a log in feature in order to access to the software application followed by the main screen that contains
the tool list, buttons actions, and more.

Inside functional requirements is stated with detailed the use cases of all the interactions of the user with the interface and the
whole system.

Simulations has to been done with a "prototype" of the GUI using and image model which represent the buttons and in general the
structure of the interface.
In summary the results of apply this model to common people with no  previous technical of software knowledge this software application
we need to assume is a very intuitive interface and no capacitation will be need it to make use of it.

2.5 User characteristics

![userchar.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/userchar.png)

2.6 Constraints

(1) Hardware

 * The hardware being use on the cellar is a single Dell desktop computer Windows 10 installed.
 
 * The computer has 4GB of RAM memory
 
 * Processor Intel i5 -5th generation

(2) Policies

The company’s policies do not allow other hardware rather than the available located on the cellar.

2.7 Assumptions and dependecies
    
The inventory tool software assumes windows 10 as the operative system selected to work with.

Names of all the work tools are expected to be known and access to them as well.

A desktop or laptop supporting windows 10 is expected to be available for the software implementation.

A person in charge of operating the software is imperative. (Tools manager).

3.0 Specific requirements

This chapter contains all the information about requirements specification in detailed, such as functional and nonfunctional
requirements to help development team for the software design by using diagrams, and functions description of all the components.

3.1 Functional requirements Specifications

The following section gives a description about each functionality of the software and the interaction of the actors with the system
supported by use case diagrams

3.2 Tool manager use cases

![MANAGER.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/MANAGER.png)

3.2.1 Use case: Add a new tool

Description

The manager tools enters a new tool on the system.

Step-By-Step Description

The tool manager must log in to add new tools to database.
1.	The Manager tools selects to Add a new tool.
2.	The system asks for the tool name. 
3.	A confirm selected option is deployed.
4.	Changes are saved in the database.

3.2.2 Use case: History

Description

The manager views histroy of requested tool to check date and other tools.

Step-By-Step Description

1.The Manager tools selects the history button.
2.The system display the history of the requestes tools.

3.2.3 Use case: Select tool

Description

The manager select tool asked by the technical to register the order.

Step-By-Step Description

1. The manager double click on selected tool
2. Automatically a window appears to type employee ID
2. Click ok button to confirm the action
3. Number of available tools decrease automatically
4. Changes are saved in the database automatically.

3.2.4 Use case: Remove tool 

Description

The manager tools removes tools from the system.

Step-By-Step Description

1.The Manager tools selects to Remove a tool.
2.The system deploys a confirm screen.
3. The system save changes.

3.2.5 Use case: Edit a tool name or amount

Description

The manager tools edits name and quantity of selected items.

Step-By-Step Description

1.The Manager tools selects to Edit a tool.
2.The system deploys a screen showing two different options, edit tool name, edit quantity (the last action also works by a single up 
button (green arrow) to increase number or down button to decrease quantity (red arrow). 

3.2.6 Use case: Search 

Description

The manager searches a specific tool from the system.

Step-By-Step Description

1.The Manager tools selects the bar to type the tool´s name or ID number.
2.The system deploys match results.

3.2.7 Use case: Log in

Description

The manager logs in into the system to be able to operate the system and make changes.

Step-By-Step Description

1.The Manager select log in button.
2.The tool manager use his user name and password to access to the system.
3. System interface is deployed.

3.2.8 Supervisor use cases

![SUPERVISOR.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/SUPERVISOR.png)

3.2.9 Use case: Add a new tool

Description

The supervisor enters a new tool on the system.

Step-By-Step Description

5.	The supervisor tools selects to Add a new tool.
6.	The system asks for the tool name. 
7.	A confirm selected option is deployed.
8.	Changes are saved in the database.

3.3 Use case: History

Description

The supervisor views histroy of requested tool to check date and other tools.

Step-By-Step Description

1.The Manager tools selects the history button.
2.The system display the history of the requestes tools.

3.3.1 Use case: Select tool

Description

Step-By-Step Description

1. The supervisor double click on selected tool.
2. Click ok button on the tab which appears to confirm action.
3. Number of available tools decrease automatically.
4. Changes are saved in the database.

3.3.2 Use case: Remove tool 

Description

The supervisor tools removes tools from the system.

Step-By-Step Description

Use case: Remove a tool
1.The supervisor tools selects to Remove a tool.
2.The system deploys a confirm screen.
3.The system save changes.

3.3.3 Use case: Edit a tool name or amount

Description

The supervisor tools edits name and quantity of selected items.

Step-By-Step Description

1.The Supervisor selects to Edit a tool.
2.The system deploys a screen showing two different options, edit tool name, edit quantity (the last action also works by a single up
button (green arrow) to increase number or down button to decrease quantity (red arrow). 

3.3.4 Use case: Provide ID

Description

The Technical provide employee ID to register the order by the manager tools.

Step-By-Step Description

1.The technical provides ID to ask for tools.
2.Manager select the tool.
3.Manager type ID in the window which appears.
4. The system register the order.

4.0 Security

In order to avoid access to unauthorized people to the system. It is recommended to use an account with privileges using a password for
the machine and not only trust in the software application log in.

A sotftware application log in must be incorporated for major security using a dedicated account for itself.

4.1 Security features

(1) The system will be locked down for 10 minutes if more than 3 attempts to access has been reached.

(2) if after the countdown another failed attempt is made, the account will be blocked permanently until the supervisor unblock it with
his account.

(3) For the safety and integrity of information, when removal items or selected,editing or adding, a warning windows will display to 
confirm this action, to avoid accidental loss of memory.


4.2 Recovery information

A backup for the system is recommended too for loss information risk by using a USB and only the supervisor able to have it and use it
in case of hardware or software damage.

Another feautre to avoid accidental loss of memory is to undone actions using command ctrl+Z

NOTE: A superior user account should be created in case of any difficulties with the tool manager account, in this case the supervisor
account.

5.0 Performance requirements
 
* The system is created to allow two or more administrator account to manage the database at a time.
* The system allows number and character data.
* The database should have enough capacity to save all work tools data.
* The operative system should support Java environment for software implementation.

5.1 Render aspects

* The results display of searching an item should not last more than 1 second.
* The log in function should not last more than 5 seconds.
* The database should have at least 1 TB of capacity. (for a wide margin)
* The database should have capacity for more than 500 hundred items information and other.

6.0 Logical database

*The logical structure information should be store in the Telmex cellar database server.
*System must be able to function 24/7, with constant frequency of use.
*A unique ID will be assigned automatically to each added tool to identify them.

![classdiagram.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/classdiagram.png)

5.1 Design constraints

(1) Only one desktop computer is available

(2) The hardware has 4 GB of memory RAM.

(3) The computer lack of Java Environment.

(4) Windows 10 is the OS installed on the computer.

(5) The tool manager has minimum knowledge of informatic. (An intuitive interface is imperative in order to avoid capacitation costs).

5.2 Software System Attributes

Tool Data Entity

![tooldataentity.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/tooldataentity.png)

Tool manager Data Entity

![managerentity](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/managerentity.png)

Supervisor Data Entity

![supervisorentity](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/supervisorentity.png)

Technical Data Entity

![technicalentity](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/technicalentity.png)

6.0 Maintainability

A technical support must be available to contact with in case of problems.

JAVA Environment could need updates to correct software functionality.

The software needs update information to find and correct errors.

In case of misuse which can cause loss of information technical support will be needed.

6.1 Portability

The software is meant to be build for the specifications stated above in the document.

The considerations taken for the software design, assums and expect specific hardware and previous software to work with, and the 
devolpment considerate only the factors and circunstances of the specific case of the company.

Portability is not a goal for the software development but the specific cases needs to be analyzed if its mean to use in a different
enviroment.

Some key factors to support portability is the OS (windows 10) and Java Environment updated.

7. Appendixes

7.1 Requirements elicitation interview

The following interview expose the needs of the customer to stablish the principal features of the software system.

The tools manager Emilio Barraza and supervisor answered the list of question below, therefore the results of the interview.

1.- Q: How many tools are you managing?

A: More than 500 hundred different tools and material.

2. Q: Do you need to add, edit and delete information about the tool state and availability?

A: Yes, specially availability

3. Q: Do you need any specification in terms of interface design (for example, any color or button style request)

A: No, just an intuitive and simple interface.

4.  Q: Would you prefer to search tools in the system by using an ID tool or name tool, or both?

A: Both 

5. Q: Do you need a log in or password to use the application to protect information?

A: We can use the administration account, but it could be useful a second log in.

6. Q: Do you have any other specific request?

A: I prefer to delegate the major part of the decisions that you consider the system needs.

We just need to manage the availability of the tools to ease our work using a simple interface with the minimum-security considerations.

7.  Q: Would you like to store the information in a different place or device for security o any other reason?

A: No, it is not necessary.
 
8.  Q: Would you like to have a history of the requested tools?

A: Yes, we need that for control and security.
 
9.  Q: The person who will operate the software application has this kind of knowledge?

A: No, thats why we need an intuitive interface, very simple to minimize or avoid training.

10. Q: How often will the system be used?

A: Very often, every day

11. Q: How many people do you wish to be able to add new tools to the database?

A: Just me (the supervisor)

 











