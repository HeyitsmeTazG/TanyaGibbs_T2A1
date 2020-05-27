## Q1: Describe the architecture of a typical Rails application

Ruby on Rails uses MVC architecture. It is a fundamental part of the framework, and so it's important to understand the structure of a rails app in order to carry out the functions correctly. The MVC stand for Model View Controller, which are the key components for developing with rails. 

The **Model** handles the data objects used. This is executed through object oriented programming, and although anything can be an object in our models, the most common type of object used is data.

The **View** is what is presented to a user, and what they interact with. The view is what developers will put the HTML, CSS and JavaScript code in, which are then deployed, and the user is able to access the features of the project. 

The **Controller** is what processes and responds to the user's interaction, such as submitting forms, clicking on links, and generally navigating the webpage. It controls the interactions between the Models and the Views. The Controller is what the Browser interacts with, and so the controller is in charge of making decisions about what should happen based on the browser's request.

If we need to interact with the database, the Controller will interact with the Model, which will then connect to the database. The Model will then return the results back to the Controller. The Controller and the Model can go back and forth as many times as is necessary, however, when the Controller has decided that it has sufficient knowledge of the data, it will send the results to the View, which is the presentation layer of the framework.

# INSERT IMAGE HERE

---
## Q2: Identify a database management system (DBMS) commonly used in web applications (including Rails) and discuss the pros and cons of this database

A popular DBMS used in Web Applications (particularly Rails) is Postgres. It is a free database that uses SQL. There are many pros to using Postgres, with limited cons.

**Pros:**

-	Open source meaning anyone can contribute to the development of Postgres
-	It supports JSON
-	Postgres is scalable and can handle terabytes of data, as well as allowing developers to handle data on a micro level, as well as building as the application grows
-	Postgres allows setting of local parameters, so developers can apply changes to the database on a small level without affecting the entire database
-	Postgres gives the option to control actions of the database, such as auto-creating, joining and dropping tables as the application is being developed
-	There are many predefined functions
-	There are multiple interfaces available
-	Transactions allow error handling to be smooth and efficient, and will commit any transaction immediately, which is useful for complex relational applications
-	Postgres allows you to use comments unlike other database applications
-	Postgres is highly extensible, meaning developers can add additional features, allowing developers to add functions, data types, and languages and install them to the database server
-	There are security features within Postgres

**Cons:**
-	Configuration of Postgres can be confusing
-	For large operations such as read queries, the speed may not be optimal
-	There are strict requirements for data developers can store in the database table
-	Being open source, any developer can contribute to it. This means there is no liability or indemnity protection, and may lack user-friendly interfaces
-	Postgres has slower performance than other DBMS

---
## Q3: Discuss the implementation of Agile project management methodology
Agile project management is used in order to complete projects by breaking it up into small sections called iterations. After each iteration is completeed, the project is re-evaluated, and then the next step of the project is determined based on the outcome of each iteration. 

This allows developers to assess any issues that come up throughout the project, and make changes accordingly. This also allows developers to release sections as they are completed, rather than having an entire release be delayed due to disorganisation and potential bugs throughout different areas of the project.

Iterations are also useful, as it allows for fixing of issues quickly and efficiently, without having to re-design an entire project near the end due to mis-planning earlier in the project. 

Agile project management allows for continuous adaptation, and is also extremely useful for time management, and is a great way to track projects throughout the entirety of their development. Projects built using APM are often more solid than ones built without. 

APM can be used in teams, or individually as the concepts remain the same. By using APM, work is completed in a more reliable and efficient manner, and there's less risk of code not working toward the end of the development process.

---
## Q4: Provide an overview and description of a standard source control workflow

Source control is a helpful way to keep track of different stages of a project. Another tool that can be utilised either individually or for teams. 

Used individually it is a great way to commit versions of your project to a remote repository. This is particularly useful if your code breaks and is too complicated to fix, you are able to revert back to a previous working version of your code, and try again. Branches help make this more achievable, and is necessary for collaboration.

Branches, when used correctly, allow multiple developers to be working on different sections of the code, which can then be submitted via a pull request, and the project manager is then able to review the branches and merge them with the master branch if the code meets the correct requirements. 

Using branches is also essential, as there could be conflicts with a feature branch and the master branch due to multiple developers working on the same iteration of code, in which case, the conflicts will need to be reviewed and resolved before merging. This ensures the code is streamlined, and the master branch is error-free.

---
## Q5: Provide an overview and description of a standard software testing process (e.g. manual testing)

Standard software testing is used to ensure that the code meets the requirements for the project. It is used effectively when used to identify errors or missing parts of the code. 

Testing might seem arbitrary to new developers, though even if code works locally, testing is used to reduce risk by finding and eliminating errors that may impact a client that uses the software that is being developed.

The process involves identifying the areas of code that are high risk for errors, and then developing a set of tests which ensure that the code runs the way it is supposed to. If the code doesnt run according to it's requirements, the test should alert the developer to the error so that it is able to be fixed.

---
## Q6: Discuss and analyse requirements related to information system security and how they relate to the project

Information System Security is primarily used to prevent unauthorized access to a system. It keeps important information confidential; this includes data, computer information and communication (such as phone calls and emails). 

Risk assessment is a vital part of ISS, as it is necessary to determine which information is the most sensitive in order to allocate more extensive security measures to it. 

### Q7: Discuss common methods of protecting information and data and how you would apply them to the project**

Common methods for protecting information and data in a Rails project are tools such as the Devise and Rolify gems. This ensures that a user of a project has correct authorisation and authentication, so they are only able to access data applicable to them. Devise in particular also uses encryption for secure information, such as passwords, so that even developers are unable to see a users password. 

It is recommended to use a third-party payment system if dealing with transactions on a rails project. A system such as Stripe or Paypal have their own policies and programs that ensure data is kept safe, and they adhere to legal requirements, meaning it isn't necessary to build a new payment system specific to just one project. 

Encryption is important for protective sensitive information such as bank or credit card details, as customers are trusting that their money is safe from theft or fraud. This is why using one of the third-party payment systems is incredibly useful, as encryption is already built into their software.

---
## Q8: Research what your legal obligations are in relation to handling user data and how they can be met for the project
There are certain legal obligations when handling user information. Companies building technologies that require user data need to ensure they adhere to the following:

- Users personal information should be destroyed or re-identified when it is no longer needed. This includes data such as names, email addresses, residential address, date of birth, bank account and/or credit card details, photos etc.

- Adequate procedures are necessary to secure a users information. In Rails, this can be met through using the Devise and Rolify Gems for authentication and authorisation, or using a thir-party payment system when handling payments online.

- It is important to only collect the necessary information from a user that is applicable to the application being built. For example, if there is no need for payments to be made through the project, it would be unnecessary and irresponsible to request a users payment details. 

- Protecting the users information from direct marketing purposes is necessary when possible. A users information shouldn't be shared without the users knowledge or consent, as this would compromise the integrity of the project.

- 


- web pages collect information such as internet domain, IP addresses, where the site was accessed from, type of browser and operating system and the pages visited
- To comply with law, there must be a privacy policy, and users should get notice that their data is being collected
- this data can only be used for its intended purpose
- user data shouldnt be shared without the consent of the user
- passwords and other sensitive information should be kept secure (such as bank and credit card details for online payments)
- users need access to change or rectify inaccurate data

---
## Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

- A relational database model is a collection of data tables
- each table has an id, and has multple rows with values that are related to each other
- most relational databases use SQL
- each table in the database model relates to anoter, and the collection of these tables forms the database schema
- an example of this could be an online dog-walking marketplace. There is a table for Dog owners (who need their dogs to be walked), and Dog walkers (who are available to walk dogs). There is also a table for job listings (created by the Dog owner, that a walker can interact with and apply for). In this case, the Dog owner can have many job listings, and can have many walkers *through* the job listings. Likewise, a walker can have many jobs, and many dog owners *through* jobs. This is a has_many through relational database. In this case, a single job listing belongs to the Dog owner, and upon application for the job, the job also belongs to the dog walker.

Other relationships include, one to many, many to many, one to one, or has many through.

---
## Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

<details>
<summary><strong>Domain Integrity</strong></summary>
All columns that are in a relational database must be in a defined domain. 
</details>

<details>
<summary><strong>Entity Integrity</strong></summary>
Primary keys. Each table must have its own unique primary key, and cannot be null. This means that a row own a table must be identified within this table, such as for a shop user, they must specify an email address. A row such as PO Box wouldnt be used, as some customers may not have a PO Box address.
</details>

<details>
<summary><strong>Referential Integrity</strong></summary>
Foreign keys can hold values in two states, the first being that it would refer to the primary key of another table, or it would be null. The reference to the primary key is to establish the relationship within the database model, and if it is null, it means there either is no relationship, or that it is unknown.
</details>


---
## Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.
- DBMS (database management system) software designed to define, manipulate, retrieve and manage data in a database (CRUD)
- used to manipulate the data itself such as format, field names, record structure and file structure. 
- defines rules to validate and manipulate the data.
- reorganising data
- queries to find certain data and update, such as employee positions
- in a relational database, data is organised into different tables that follow a certain logic through the relationships each table has with each other. Data from one table can reference data from a different table (such as user_ids etc).
- this is referred to as referential integrity
- operations such as select and join can be performed on tables to manipulate the data.

---
## Q12: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O)

---
## Q13: Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O)

---
## Q14: Conduct research into a marketplace website (app) and answer the following parts: 
**a. List and describe the software used by the app.**

Airbnb uses a number of different software in order for the app to funtion. These can be broken down into the following categories:

<details>
<summary><strong>Programming Languages</strong></summary>
<ul>
<li>Ruby</li>
<li>Javascript</li>
</ul>
</details>

<details>
<summary><strong>Frameworks</strong></summary>
<ul>
<li>Ruby on Rails</li>
Speeds up development
<li>React</li>
Used to build sleek interfaces
</ul>
</details>

<details>
<summary><strong>Web Server</strong></summary>
<ul>
<li>Nginx</li>
HTTP and proxy server to speed up content delivery, and help with security and scalability
</ul>
</details>

<details>
<summary><strong>Cloud Storage</strong></summary>
<ul>
<li>Amazon s3</li>
Stores data (pictures)
</ul>
</details>

<details>
<summary><strong>Cloud Hosting</strong></summary>
<ul>
<li>Amazon EC2</li>
distributes incoming traffic so the server doesnt go down during traffic spikes
</ul>
</details>

<details>
<summary><strong>Cloud Database</strong></summary>
<ul>
<li>Amazon RDS</li>
</ul>
</details>

<details>
<summary><strong>Other Tools</strong></summary>
<ul>
<li>Presto</li>
<li>Druid</li>
<li>Airpal</li>
</ul>
</details>


**b. Describe the hardware used to host the app.**
1. Web servers, data servers, application servers

**c. Describe the interaction of technologies within the app.**
**d. Describe the way data is structured within the app.**
**e. Identify entities which must be tracked by the app.**
**f. Identify the relationships and associations between the entities you have identified in part (e)**

**g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)**

![Airbnb ERD](/Pics/airbnbERD.png)

---