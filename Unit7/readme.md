# Executive Summary
Talk about what the goal of this lab is

This week we learn about the basics of Object Oriented Programming. We also about organizing data in tables; organizing big data in connected tables. We will get a taste of how to run queries of those connect table to get useful information. And we learn about the ethics of informations system, big data, and how to protect personally created data.

# Object Oriented Programming
## This hase been completed. I've uploaded each class individually.
* Create a class (using paper and pencil or using the Microsoft whiteboard app) for the following: a) Phone b) House c) Employee
* Identify the features (In the video for the Car class, we identified the properties as Year, Make Model etc)
* Identify the actions (In the video a) for the Car class, we identified the methods as Drive, Park, Start etc)
* Then upload a screenshot of your diagram to github for each of the above classes.

# Data, Information and Knowledge
## Relational Data
* What is the difference between data, information and knowledge?

Data are the raw bits and pieces of qualitative or quantiative information with no context. Information is analized data with context. The consumption of the information produces knowledge.

* If you were creating a database for a small company and two tables you identify are customers and orders explain the following: (be sure to use the example in the chapter as a guide - customers and orders would be like clubs and events) 

a) What would be the primary key in the customers and orders table? "Customer ID" and "Order ID" respectively. 

b) How would the customers and orders table be related? "Customer ID" relates/links the two tables.

c) What would be the foreign key in the orders table? "Customer ID" from "Customers" as well as "Employee ID" from "Employees"

d) The orders table would likely have a date field. Explain why it is important to properly define the data type of a field.

A data type tells the databse what kind of data is there and what can be done with that data and how much storage space the data needs.

## Big Data
* Briefly describe the four "Vs" of big data

VOLUME is the main characteristic and it refers to the amount of the data itself. VARIETY refers to the unstructered data meaning many types of data with no clear identification thus processing rules. VELOSITY is the speed and frequency of the incoming data that needs to be processed. VERACITY refers to the trustworthiness of the data - is this data correct? 

* What types of technology have driven the increased need for big data?

The organization and storage of data into databases is how we've come to collect so much data. People use sofware such as Apache Open Office Base, Microsift Access DBMS, Amazon RDS (a relational database), and MySQL are interfaces that aide in the creation and organizaton of the data. 

# Structured Query Language (SQL)
* Explain RDBMS and how it relates to SQL and the purpose of SQL

A Relational DataBase Management System stores information in a tabular form and a Structured Query Language is used to communicate with a dabase.

* Pick two related tables from the diagram provided in the "module - SQL" and explain the relationship between them a) which is the primary key? b) which is the foreign key?

I choose "Orders" and "Order Details":  "Order ID" is primary key in "Oders" and a foreign key in "Order Details". "Orders" contains the information required to ship orders. "Order Details" contain a few pieces of data specific to the "Order" and a foreign key to "Products".

* Using W3Schools, try out a a) select statement a) where clause and upload screenshots of the results.
* Explain how SQL injections are a security threat and what can be done to reduce the issue.

# Ethical and Legal Implications of Information Systems
## Code of Ethics
* Explain the purpose of a "code of ethics" and why the ACM created a code for the computing discipline.

It is a formal document that outlines a set of acceptable behaviors for a professional group detailing different actions that are considered acceptable by the group. It is a code pf personal reponsibility identifying the elements of the commitment including fundamental ethical considerations and guidance of professional behavior. ACM also wanted to enforce more specific admonitions that relate directly to information technology.

* Explain the difference between a code of ethics and AUP (acceptable use policies.)

These policies relate to a group of constituents and/or a public agreement that some basic rules be followed and are based on the trust that some basic rules be followed. 

* Pick a site of your choice and read the AUP. Select a policy of interest and report your findings (include a link to the site in your report.)

I chose to go to Sesame Street, and there is a whole page of smaller type explaining the cans and cannots about how outside sources can work with Sesame Street. https://www.sesamestreet.org/termsofuse ## Intellectual Property

* From the chapter follow the link to the WIPO. What is the purpose and importance of the WIPO?

For over 100 years The World Intellectual Property Organization makes IT work for everyone. It allows innovation and creativity to flourish by handling and organizing things like patents and trademarks, and when disagreements occur they offer services like arbitration and mediation. It builds the rules alongside technology improvements as they happen.

* Using links in the chapter explain how a copyright is obtained and the benefit of registering for a copyright with the US Copyright Office. Explain why it might be important to copyright the svg image you created.

In many countries, copyright protection is obtained automatically without the need for formal procedures. Offical registration is voluntary. Copyright protection extends only to expressions. Registration allows for "economic rights, which allow the rights owner to derive financial reward from the use of their works by others; and moral rights, which protect the non-economic interests of the author." If I copyright my svg, then I "own" it and no one else can use it unless I give them permission.

* If the svg image you created became an item that identifies a source of goods or services, explain the role of a trademark in defining the intellectual property.

A Trademark is an official identifier of a particular source of goods or services. It's purpose is to protect the consumers allowing them to know that the product or service is legitimate.

## Information Collection
* Explain how COPPA, FERPA and HIPPA restrict the collection of information on the Internet.

COPPA: Children's Online Privacy and Protction Rule Act imposes certain requirements of operators of websites and/or online services from collecting information from children under 13 years of age. FERPA: The Family Educational Rights and Privacy Act is a US law that protects the privacy of student education records. HIPPA: The Health Insurance Portability and Accountablity Act is a set of laws that protect health care/medical information.

# Conclusion
Include what you have learnt from this lab
