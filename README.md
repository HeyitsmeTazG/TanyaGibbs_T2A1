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

Agile project management allows for continuous adaptation, and projects built using APM are often more solid than ones built without. 

APM is also extremely useful for time management, and is a great way to track projects throughout the entirety of their development. 

APM can be used in teams, or individually. 

---
## Q4: Provide an overview and description of a standard source control workflow

Source control is a helpful way to keep track of different stages of a project. Another tool that can be utilised either individually or for teams. 

Used individually it is a great way to commit versions of your project to a remote repository. This is particularly useful if your code breaks and is too complicated to fix, you are able to revert back to a previous working version of your code, and try again. Branches help make this more achievable, and is necessary for collaboration.

Branches, when used correctly, allow multiple developers to be working on different sections of the code, which can then be submitted via a pull request, and the project manager is then able to review the branches and merge them with the master branch if the code meets the correct requirements. 

Using branches is also essential, as there could be conflicts with a feature branch and the master branch due to multiple developers working on the same iteration of code, in which case, the conflicts will need to be reviewed and resolved before merging. This ensures the code is streamlined, and the master branch is error-free.

---
## Q5: Provide an overview and description of a standard software testing process (e.g. manual testing)

---
## Q6: Discuss and analyse requirements related to information system security and how they relate to the project

---
## Q7: Discuss common methods of protecting information and data and how you would apply them to the project

---
## Q8: Research what your legal obligations are in relation to handling user data and how they can be met for the project

---
## Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

---
## Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

---
## Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

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