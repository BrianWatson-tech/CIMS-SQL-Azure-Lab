# Project Origin and Environment

## Overview

CIMS began as a personal project to help me learn modern database technology while building something that has a practical purpose.

CIMS stands for **Career Information Management System**.  The long-term purpose is to organize career history, experience, projects, skills, training, education, certifications, accomplishments, and other information that can eventually help me identify relevant information for different resume or career needs.

The technical side of the project also gives me a practical way to update my database knowledge and develop hands-on experience with SQL Server and Microsoft Azure.

The environment I use today is not the environment where the project started.

I experimented with several technologies before deciding which environment best supported what I was actually trying to learn.

## Starting With Previous Computer and Database Experience

My experience with computers goes back approximately 40 years, including experience with older database systems such as dBASE and Vulcan.

That early experience gave me familiarity with storing, organizing, and retrieving structured information.  However, modern relational databases such as Microsoft SQL Server are very different from the database systems I originally learned.

I did not want to assume that experience with older database technology automatically meant I understood modern SQL Server.

I decided to approach SQL Server from the fundamentals while using my previous experience as a foundation.

Instead of limiting the learning process to isolated exercises, I wanted a database project that could grow as my knowledge increased.

CIMS became that project.

## Moving From Older Database Systems to Modern SQL

One of the things I am learning through CIMS is how modern relational database design differs from the older database environments I worked with years ago.

With older systems such as dBASE, much of my experience involved working with individual database files and navigating or manipulating records.  With SQL Server, I am learning to think more in terms of related sets of data and relationships that are defined within the database.

Two concepts that have particularly changed how I think about the database are relationships and how information is retrieved.

In CIMS, I am learning to use primary keys and foreign keys to define relationships between tables.  For example, a project can have its own ProjectID, and a task can reference that ProjectID.  This allows the database structure itself to define and help protect the relationship between the records.

I am also learning the difference between working through individual records and using SQL to request a set of information.  Instead of thinking primarily about moving from one record to another, I can describe the information I want and allow SQL Server to retrieve the matching rows.

These are not just new commands for me to learn.  They represent a different way of thinking about how information should be structured, related, and retrieved.

My previous database experience gives me a foundation for understanding why organized data matters.  Building CIMS is helping me update that foundation with modern relational database concepts.

## First Environment - Linode Virtual Machine

My first CIMS environment was built using a virtual machine hosted by Linode.

This gave me a remote server where I could experiment without depending on my local Windows environment.

I worked with the server through the Linux command line and began learning how to configure and manage the environment.

The basic environment was:

**Linode → Virtual Machine → Linux**

This was useful because it gave me hands-on experience working with a remote Linux system instead of only working through a graphical Windows interface.

## Installing Docker

I installed Docker on the Linux virtual machine.

This introduced me to running an application inside a container instead of installing everything directly into the operating system.

The environment then became:

**Linode → Linux Virtual Machine → Docker**

I was learning several things at the same time.

I was working with a cloud-hosted virtual machine, using the Linux command line, installing and configuring Docker, and learning how containers operate.

## Running SQL Server in a Container

After installing Docker, I installed Microsoft SQL Server inside a Docker container.

The complete environment became:

**Linode → Linux → Docker → SQL Server Container**

This environment worked and gave me hands-on exposure to technologies I had not previously used together.

I had successfully created a remote Linux environment, installed Docker, and deployed SQL Server inside a container.

That was useful experience, but it also caused me to evaluate what I was actually trying to accomplish.

## Reassessing the Environment

As I continued working with the Linode environment, I realized I was learning several technologies at the same time.

That was not necessarily a bad thing, but Linux and Docker were beginning to take attention away from my primary learning objective.

My main goal was to become more comfortable with Microsoft SQL Server, relational database design, and eventually Microsoft Azure.

I did not want the complexity of the environment to become more important than understanding the database itself.

Instead of continuing with an environment simply because I had already built it, I decided to change direction.

The Linode environment had already accomplished something useful.  It introduced me to Linux, command-line administration, Docker, containers, and running SQL Server inside a container.

I did not consider that work wasted.

It helped me determine what I wanted the next phase of the project to focus on.

## Moving to a Local Windows Environment

I decided to move my primary CIMS development environment to my Windows laptop.

I installed **Microsoft SQL Server Express** locally.

I then installed **Microsoft SQL Server Management Studio (SSMS)** so I could administer SQL Server and work directly with the database.

The primary environment became:

**Windows Laptop → SQL Server Express → SSMS**

This removed several additional layers between me and the database.

Instead of concentrating on Linux and container administration, I could concentrate directly on SQL Server and relational database development.

## Creating CIMS_LOCAL

I created my primary local learning database as:

**CIMS_LOCAL**

CIMS_LOCAL became the environment where I could begin building the actual database structure while learning SQL Server.

I could create tables, enter test information, run queries, test changes, troubleshoot problems, and see the results directly.

This gave me a controlled environment where I could learn without depending on a cloud service or creating unnecessary cloud costs.

The local database also made it easier for me to separate two different learning objectives:

**Learn SQL locally first.**

**Use Azure to expand that knowledge into the cloud.**

## Learning SQL From the Fundamentals

Moving to SQL Server Express allowed me to concentrate more directly on understanding SQL.

I began working through concepts such as:

- Databases
- Tables
- Columns
- Rows
- Data types
- Primary keys
- Identity columns
- NULL and NOT NULL
- Default values
- Creating tables
- Adding fields
- Inserting records
- Selecting information
- Updating information
- Relationships between tables

Some concepts were familiar because of my previous database experience, while others required me to change how I thought about organizing information.

For example, I began learning why information should be separated into related tables rather than simply creating one large table containing everything.

As I develop CIMS, I am learning how SQL commands work, why they are used, and how they affect the database.  Understanding the purpose behind each step helps me apply what I learn as the database becomes more complex.

## Understanding the Tools

One of the concepts I needed to understand was the difference between SQL Server and SQL Server Management Studio.

**SQL Server Express** is the database server running on my laptop.

**SSMS** is the management application I use to connect to SQL Server and work with the databases.

Understanding that distinction became more important later when I began working with Azure SQL.

SSMS is not limited to the SQL Server running on my laptop.  I can use the same management application to connect to different SQL environments.

That helped me understand the difference between the database service and the tool being used to manage it.

## Why I Kept the Local Environment

Even after beginning my Azure learning, I decided to keep CIMS_LOCAL as my primary development and learning database.

The local environment gives me a place to experiment without worrying about cloud consumption or cost.

It also allows me to concentrate on learning SQL without introducing networking, authentication, firewall rules, and other cloud components every time I want to work with the database.

Azure can then be used when the learning objective actually involves Azure.

This keeps the environment appropriate to what I am trying to learn.

## Expanding Into Azure

After becoming more comfortable with SQL Server locally, I began expanding my learning into Microsoft Azure.

At the same time, I was studying for the Microsoft Azure Fundamentals (AZ-900) certification.

I created my own Azure account so that I could work with the services and concepts I was studying and gain practical experience with the Azure environment.

I created an Azure SQL logical server and an Azure SQL Database.

I then connected to the Azure SQL environment using SSMS from my laptop.

The environment had now expanded to include:

**Local SQL Environment**

**Windows → SQL Server Express → CIMS_LOCAL**

and

**Cloud SQL Environment**

**Windows → SSMS → Network → Azure SQL**

This helped me begin understanding the difference between managing a database locally and accessing a managed database service in the cloud.

## Learning Azure Through CIMS

CIMS gives me something practical to use while learning Azure.

Rather than creating cloud resources without a specific purpose, I want to understand why I would use them and how they relate to an actual system.

Working with Azure SQL has already introduced practical topics such as:

- Azure resources
- Azure SQL Database
- Logical SQL servers
- Network access
- Public IP addresses
- Azure SQL firewall rules
- Local versus cloud databases
- Authentication and access
- Resource configuration
- Cloud costs and consumption
- Troubleshooting connectivity

The project gives me a reason to continue expanding into additional Azure technologies as my knowledge grows.

## Learning Through Real Problems

Adding Azure also introduced problems that did not exist when everything was running locally.

One example involved network access.

I configured Azure SQL to allow access from my home Internet connection.

Later, I connected my laptop through an iPhone hotspot and discovered that the Azure SQL connection did not behave the same way.

The hotspot used a different public IP address.

That meant the Azure SQL firewall configuration that allowed my home connection did not automatically allow the hotspot connection.

Troubleshooting that problem helped me understand several concepts that had previously been mostly definitions:

- Public IP addresses
- Changing network connections
- Azure SQL firewall rules
- Selected network access
- Why a connection can work from one network and fail from another

That experience helped turn the networking concepts into something practical.

I had a real connectivity problem, identified the reason, adjusted the appropriate configuration, and verified the connection.

Experiences like this help me understand how the different parts of the environment actually work together.

I want CIMS to document both successful implementation and the troubleshooting that occurs as the project develops.

## AZ-900

While building the Azure portion of the CIMS learning environment, I continued studying for the Microsoft Azure Fundamentals (AZ-900) exam.

I passed the AZ-900 exam and earned my first Microsoft certification.

The certification and the CIMS project serve different purposes.

AZ-900 validates my understanding of fundamental Azure concepts.

CIMS gives me a place to apply those concepts, work with the technology, troubleshoot problems, and continue developing practical skills.

Passing AZ-900 was not the end of my Azure learning.  It established a foundation that I can continue building on through hands-on work.

## Why the Architecture Changed

The CIMS environment has changed because my learning objectives became clearer.

The original environment introduced me to:

**Linux → Command Line → Docker → Containers → SQL Server**

The local Windows environment allows me to concentrate on:

**SQL Server Express → SSMS → SQL → Relational Database Design**

The Azure environment allows me to expand into:

**Azure SQL → Networking → Security → Monitoring → Cloud Administration**

Each environment has served a purpose.

Changing environments was not about abandoning previous work.

It was about recognizing what I needed to learn next and choosing an environment that supported that objective.

I chose to build the environment in stages so I could develop a solid understanding of each technology before adding additional complexity.

## Current Environment

My current primary CIMS database is:

**CIMS_LOCAL**

It runs on Microsoft SQL Server Express on my Windows laptop and is managed using SQL Server Management Studio.

I also have an Azure SQL environment that I use for Azure learning and testing.

The local database remains my primary SQL development environment while I continue learning database design.

Azure provides a separate environment where I can learn cloud concepts when those concepts become relevant to the project.

## Current Status

CIMS is still an active learning and development project.

The database is not being presented as a finished production application.

I am continuing to build the database structure, learn SQL concepts, enter test information, work with relationships, and determine how the different parts of the Career Information Management System should fit together.

The Azure environment is also a learning environment rather than a production deployment of CIMS.

Future development will be documented as I actually complete and understand the work.

## What I Learned

The biggest lesson from the original CIMS environment was that successfully building something does not necessarily mean it is the best environment for the objective.

I successfully created a Linux virtual machine, installed Docker, and ran SQL Server inside a container.

That environment worked.

I still chose to change it because I realized that my primary objective was learning SQL Server and Azure rather than spending most of my available learning time managing Linux and containers.

Moving to SQL Server Express and SSMS allowed me to concentrate on SQL.

Adding Azure later allowed me to introduce cloud technology after I had become more comfortable with the database itself.

I also learned that approximately 40 years of experience working with computers gives me a useful foundation, but it does not eliminate the need to learn modern technologies from the fundamentals.

Technology has changed considerably since I first began working with computers and older database systems.  Part of this project is taking that earlier experience and building modern skills on top of it.

One of the more important changes has been learning to think about data relationally.  Primary keys, foreign keys, relationships between tables, and set-based queries give me different ways to structure and retrieve information than the older database environments I previously used.

CIMS gives me a way to connect that previous experience with the technologies I am learning now.

The project has also reinforced how I prefer to learn technical subjects:

**Build it.**

**Understand how and why it works.**

**Test it.**

**Troubleshoot problems when they occur.**

**Understand what caused the problem.**

**Document what I learned.**

**Continue building.**

## Data and Security Notice

CIMS is a personal learning and portfolio project.

This repository does not contain employer operational information, law-enforcement records, confidential business information, passwords, account credentials, private Azure connection information, or other restricted data.

Any examples or screenshots added to this repository will be reviewed and sanitized before being published.
