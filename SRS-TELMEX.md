1.0 Introduction

Telmex (Telefonos de Mexico) it is a large company in the business of communications in Mexico.
A TELMEX plant at Ciudad Juarez lack of tools inventory, instead of using software to automatize processes, they face several problems
and difficulties to control the management of every work tool that is being used due to traditional or obsolete methods as using paper.

1.1 Purpose

The purpose of this document is to give a detailed description of the features, requirements and what the system should do and the way
it operates.
The document is meant to be used by the stakeholders of the project for the development processes and other stages.

1.2 Scope
  
This software will be a work tools management for Telmex company. It will solve manual and paper doing processes problems just as slowness
procedures and confusion troubles that causes equipment loses by using software automatization, which allow the tool manager to have 
control of the work tools being used, available items, and identify the number of objects in real time as well is meant to register when
an item has been recollected from the technical, storing information such as date and hour of the order and the identity of the employer
who ask for the tool. 
A database will be used to recollect the tools information just as date, name of tool, ID tool, employee ID, etc.
In case of loss  of tools or material and malfunction, as well as any reason or circumstance that implicates the use of some other tools 
not provided in first instance by the company  it is imperative for the technical to ask for new tools to the tools manager who will
operate the software application to ease the tools to the technical and interact with the tools supplier to add new tools to the system or
ask for more if it is needed. Also, supervisor of management tools department will check all the processes involved to avoid and solve any
possible anomaly.

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
readers, and different purposes too.

2.0 Overall description

The Management Tool should be an intuitive interface compound by interface, database server, in the software aspects.
The human aspects play the most important role, as actors, the technical request for tools that is needed and the manager tool operates
and edit the list of tools, the name, the pieces available, the ID, etc.

The technical request for a tool, and the manager search for the tool if its available in the storage, then save the changes, just as
the actual amount of available unities in the cellar, and a small report is generated, which contained the employee number and the date request.
A connection must be made between the interface compound of graphic buttons and the database server where all the data will be stored.
The buttons displayed to operate the interface are:
Edit, Remove, Add, Increase, Decrease, Search Bar, Go Back. In order to a proper software performance.
There is also an autocompleted sentence to fill the field in order to ease the search and make more efficient the process.

2.1 Product perspective 

The product is expected to be a single and independent entity, not related with any other component or large system.
The inventory software is a common application used in all large and small companies around the world to have control of their objects 
and items to have a record of loss and malfunction tools or material. It is considered a priority in the modern world, as well as the
use of database to deploy information and be able to add, edit and remove data.

2.2 Site adaptation requirements

A database server should exist already in the company to implement the created tables.
A laptop or computer desktop in optimal conditions should be available for the software implementation.
A laptop or computer desktop should have the minimum performance requirements (such as processor, RAM memory, etc.) to run a database
server in a reasonable amount of time without any difficulties.
Java environment should be installed on computer to run the software successfully.

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
An auto-completed sentences will be implemented in order to ease the search.


2.4 Interfaces

The interface is a simple box on JAVA graphic environment making use of buttons to ease the application use.
The interface consists of a soft interface (not full of plenty action buttons or useless information), which contained a list of work
tools containing its respective ID, and the manager can add new tool data, also edit or remove it by selecting the buttons displayed on
screen.
Also, it has the search bar to look for a specific tool using name product or ID tool.
The interface has no priority for esthetic aspects including special colors, shapes or other graphical characteristics.
All the features of the interface it remains in one single tab with small popping tabs in case of system notifications like confirm
actions or warning.
The interface is connected to a database to store tools information, such as register date information of the order, availability of the
item, and also to store new tools to the system.

2.5 User characteristics

![userchar.png](https://github.com/RequirementEngineering/ch-re-al147172/blob/master/userchar.png)

2.6 Constraints

(1) Hardware

 The hardware being use on the cellar is a single Dell desktop computer Windows 10 installed.
 The computer has 4GB of RAM memory
 Processor Intel i5 -5th generation

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






