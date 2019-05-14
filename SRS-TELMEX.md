
Telmex Work Tools Management

1.Introduction
Telmex (Telefonos de Mexico) it is a large company in the business of communications in Mexico.
A TELMEX plant at Ciudad Juarez lack of tools inventory, instead of using software to automatize processes, they face
several problems and difficulties to control the management of every work tool that is being used due to traditional or obsolete methods as using paper.


1.1 Purpose

The purpose of this document is to give a detailed description of the features, requirements and what the system should do and the way 
it operates.
The document is meant to be used by the stakeholders of the project for the development processes and other stages.

  1.2 Scope

This software will be a tools inventory for Telmex work tools management. It will solve manual and paper doing processes problems just as slowness procedures and confusion troubles that causes equipment loses by using software automatization, which allow the tool manager to have control of the work tools being used, available items, and identify the objects
of the cellar in real time. A database will be used to recollect the tools information just as address, object, category, etc. 
1.3 Definitions
Definitions, acronyms, and abbreviations:
Telmex: Teléfonos de México

[TECHINCAL.png]

1.4 References

Davis, A., & Overmeyer, S. (1993). Identifying and measuring quality in a software requirements specification. Baltimore: Proceedings First International Software Metrics Symposium.
Dobing, B. (2006). "How UML is used". COMMUNICATIONS OF THE ACM.
Mariscal, J. (2005). New trends in the Latin American telecommunications market: Telefonica & Telmex. ELSEVIER.

1.5 Overview
The next content gives information of the functionality of the system, the specific requirements, such as functional and nonfunctional using high-level language to give place to a more technical terminology in the chapter below.
The next chapter uses technical language and is meant to be used by the development team, including more detailed description about requirements.
In general, describes the whole project and its characteristics using different languages in order to communicate with different readers, and different purpose too.



2. Overall description
The Management Tool should be an intuitive interface compound by interface, database server, in the software aspects.
The human aspects play the most important role, as actors, the technical request for tools that is needed and the manager tool operates and edit the list of tools, the name, the pieces available, the ID, etc.
The technical request for a tool, and the manager search for the tool if its available in the storage, then save the changes, just as the actual amount of available unities in the cellar, and a small report is generated, which contained the employee number and the date request.
A connection must be made between the interface compound of graphic buttons and the database server where all the data will be stored.
The buttons displayed to operate the interface are:
Edit, Remove, Add, Increase, Decrease, Search Bar, Go Back. In order to a proper software performance.
There is also an autocompleted sentence to fill the field in order to ease the search and make more efficient the process.
2.1 Product perspective 
The product is expected to be a single and independent entity, not related with any other component or large system.
The inventory software is a common application used in all large and small companies around the world in order to have control of their objects and items to avoid lost material and reduce costs of possible theft. It is considered a priority in the modern world, as well as the use of database to deploy information and be able to add, edit and remove data.
2.2 Site adaptation requirements
A database server should exist already in the company to implement the created tables.
A laptop or computer desktop in optimal conditions should be available for the software implementation.
A laptop or computer desktop should have the minimum performance requirements (such as processor, RAM memory, etc.) to run a database server in a reasonable amount of time without any difficulties.
Java environment should be installed on computer to run the software successfully.

    2.3 Product functions
    The software would allow to add, edit and remove items from the cellar in real time to have control over the database.
Also, the manager will have control increase or decrease the number of available tools by selecting two different colored arrows for up and down buttons. 
Information about requested tools are saved on the system for future references and security, such as date of requested tool, number of employees, etc. 
The connection with the database would allow to view the available tools on the cellar with additional information such as the existing unities, as well as the not available work tools in real time.
The manager tool could search any tool by typing its identification number or tool name using an intuitive interface by selecting buttons.
Some changes such as delete items can be undone to avoid accidental loss of memory.
An auto-completed sentences will be implemented in order to ease the search.
2.4 Interfaces
The interface is a simple window build on JAVA graphic environment which allow intuitive buttons to interact with.
The interface consists of a log in screen followed by a soft interface, which contained a list of work tools, and the manager can add new tool data, also edit or remove it by selecting the buttons displayed on screen.

    2.5 User characteristics 
    The tool manager is expected to operate the software, having privileges to add, edit, or delete items from the inventory list. As well he oversees the cellar and new items orders for the lack of specific tools.
    The technical is expected to be the actor who will interact with the tool manager to ask for the needed tools.



    2.6 Constraints 
(1) Hardware
 The hardware being use on the cellar is a single Dell desktop computer Windows 10 installed.
The computer has 4GB of RAM memory
(2) Policies
The company’s policies do not allow other hardware of software rather than the available located on the cellar.

    2.7 Assumptions and dependencies 
The inventory tool software assumes windows 10 as the operative system selected to work with.
Names of all the work tools are expected to be known and access to them as well.
A desktop or laptop supporting windows 10 is expected to be available for the software implementation.
A person in charge of operating the software is imperative. (Tools manager).

3. Specific requirements
This chapter contains all the information about requirements specification in detailed, such as functional and nonfunctional requirements in order to help development team for the software design by using diagrams, and functions description of all the components.

3.1 Functional requirements Specifications
The following section gives a description about each functionality of the software and the interaction of the actors with the system supported by use case diagrams

3.2 Tool manager use cases


 TECHINCAL.png
 
3.3 Use case: Add a new tool
Description
The manager tools enters a new tool on the system.
Step-By-Step Description
The tool manager must log in, in order to add new tools to database.
1.	The Manager tools selects to Add a new tool.
2.	The system asks for the tool name. 
3.	A confirm selected option is deployed.
4.	Changes are saved in the database.

3.4 Use case: Remove tool 
Description
The manager tools removes tools from the system.

Step-By-Step Description
Use case: Remove a tool
1.The Manager tools selects to Remove a tool.
2.The system deploys a confirm screen.
3. The system save changes.
             
3.5 Use case: Edit a tool name or amount
Description
The manager tools edits name and quantity of selected items.
Step-By-Step Description
Use case: Edit a tool
1.The Manager tools selects to Edit a tool.
2.The system deploys a screen showing three different options, edit tool name, edit quantity   (the last action works by a single up button to increase number or down button to decrease quantity). 

3.6 Use case: Search 
Description
The manager searches a specific tool from the system.
Step-By-Step Description
1.The Manager tools selects the bar to type the tool´s name or ID number.
2.The system deploys the results

3.7 Use case: Log in
Description
The manager logs in into the system to be able to make changes.
Step-By-Step Description
1.The Manager select log in button.
2.The tool manager use his user name and password to access to the system.
3. System interface is deployed.

3.8 Technical use cases
 
3.9 Use case: Tools order
Description
The technical ask for a specific tool needed.
Step-By-Step Description
1.The Technical ask for tools to manager.
  
4. Security
In order to avoid access to unauthorized people to the system. It is recommended to use an account with privileges using a password.
For the safety and integrity of information, when removal items are selected, a warning windows will deploy to confirm this action, in order to avoid accidental loss of memory.
NOTE: A superior user account should be created in case of difficulties with the tool manager account.

5. Performance requirements
(1) The system is created to allow two or more administrator account to manage the database at a time.
(2) The system allows number and character data.
(3) The database should have enough capacity to save all work tools data.
(4) The operative system should support Java environment for software implementation.
Render aspects
The results display of searching an item should not last more than 1 second.
The log in function should not last more than 5 seconds.
The database should have at least 1 TB of capacity. (for a wide margin)
The database should have capacity for more than 500 hundred items information and other.

5.1 Logical database
ER diagram showing system relations and the attributes that contains.
The logical structure information should be store in the Telmex cellar database server.
System must be able to function 24/7, with constant frequency of use.

5.2 ER diagram.
5.3 Design constraints
(1) Only one desktop computer is available
(2) The hardware has 4 GB of memory RAM.
(3) The computer lack of Java Environment.
(4) Windows 10 is the OS installed on the computer.
(5) The tool manager has minimum knowledge of informatic. (An intuitive interface is imperative in order to avoid capacitation costs).



6. Software System Attributes
Tool Data Entity
Data ItemTypeDescriptionCommentNameTextName of tool
ID
NumberTracing informationTo distinguish different tools
DateDateDate of entry or exit
Tool manager Data Entity
Data ItemTypeDescriptionCommentNameTextName of the manager
The person who interacts directly with the system.User accountTextAccount namePassword accountIntegerPassword key
Technical Data Entity
Data ItemTypeDescriptionCommentNameTextName of Techincal
The person who ask for the tools and use them.ID
NumberTracing information



6.1 Security
The system avoids access to unauthorized person by using one single user account and password account with privileges of edit. Only the superior can have access to the system if it needed with his user account and password account. Also, only the superior has privileges to add or delete accounts.
Also, the system will shut down if more than 3 attempts to access has been reached.

6.2 Maintainability
A technical support must be available to contact with in case of problems.
JAVA Environment could need updates to correct software functionality.
The software needs update information to find and correct errors.
	
3.6.5 Portability
The software is meant to be build for the specifications stated above in the document.
The considerations taken for the software design, assums and expect specific hardware and previous software to work with.
Portability is not a goal for the software development but the specific cases needs to be analyzed.
Some key factors to support portability is the OS (windows 10) and Java Environment updated.

7.0 Appendixes

Requirements elicitation interview

The following interview expose the needs of the customer to stablish the principal features of the software system.
The tools manager Emilio Barraza and supervisor answered the list of question below, here are the results of the interview.

1.- Q: How many tools are you managing?
A: More than 500 hundred different tools or material.
2. Q: Do you need to add, edit and delete information about the availability?
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
