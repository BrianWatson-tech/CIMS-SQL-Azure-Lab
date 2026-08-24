# CIMS — Career Information Management System

## Project Overview

CIMS stands for **Career Information Management System**.

I started CIMS as a personal project to organize the large amount of career, education, training, technical, project, and life-experience information I have accumulated over many years.

A traditional resume only contains a small portion of that information.  When applying for a particular position, the challenge is remembering everything I have done and determining which experience, skills, training, accomplishments, and projects are actually relevant to that position.

Instead of trying to maintain one extremely large master resume, I began developing CIMS as a structured database that can eventually maintain this information and help me retrieve the parts that are relevant to a particular need.

At the same time, I wanted to improve my SQL Server and Microsoft Azure skills through hands-on work.

CIMS gives me a practical project where I can learn database design, SQL, cloud technology, networking, security, troubleshooting, and related technologies while building something that has an actual purpose for me.

## The Problem I Wanted to Solve

Career information tends to accumulate in many different places over time.

It can include:

- Employment history
- Positions and assignments
- Skills
- Projects
- Accomplishments
- Awards
- Certifications
- Education
- Training
- Technical experience
- Military experience
- Professional references
- Specialized experience
- Problems solved
- Lessons learned
- Results and outcomes

A normal resume cannot contain everything.

The information that matters for one position may also be very different from the information that matters for another.

My long-term goal for CIMS is to maintain the larger career and skills inventory as structured information and eventually use that information to help identify the experience most relevant to a particular position or resume.

Instead of asking:

**What can I remember that might belong on this resume?**

I want to eventually be able to ask:

**What information in CIMS is relevant to this position?**

## Why I Chose a Database

I could maintain this information in a large document or spreadsheet, but I wanted to learn how to structure related information in a relational database.

Career information naturally contains relationships.

A position can involve multiple projects.

A project can demonstrate multiple skills.

A person can have multiple certifications, awards, training records, positions, and accomplishments.

An accomplishment may relate to a particular position or project.

Those relationships made CIMS a useful project for learning relational database concepts.

Instead of creating unrelated practice tables only to learn SQL syntax, I can apply what I learn to a database that has a real purpose and can continue growing as my skills improve.

## Previous Database Experience

My experience with computers and databases goes back many years.

I previously worked with older database systems including dBASE and Vulcan.  That experience gave me some familiarity with storing, organizing, and retrieving structured information.

Modern SQL Server and relational database design are different from the database systems I originally learned.

Rather than assuming that older experience automatically translated into modern SQL skills, I decided to start working through SQL Server from the fundamentals and learn the differences by actually building a database.

CIMS became the project I could use to do that.

## How the Technical Project Started

My first CIMS environment was built on a virtual machine hosted by Linode.

I worked from the Linux command line, installed Docker, and then installed Microsoft SQL Server inside a Docker container.

The environment gave me hands-on exposure to several technologies:

**Virtual Machine → Linux → Docker → Container → SQL Server**

The environment worked, and building it was useful experience.

However, I eventually realized that I was spending a significant amount of my learning time working with Linux and the container environment when my primary goal was to become more comfortable with Microsoft SQL Server and eventually Microsoft Azure.

That caused me to reconsider the environment I was using.

## Moving to SQL Server Express and SSMS

I decided to simplify the environment so I could concentrate more directly on learning SQL Server.

I installed Microsoft SQL Server Express on my Windows laptop and installed Microsoft SQL Server Management Studio (SSMS) to manage and work with the database.

This became my primary local CIMS development and learning environment.

The change allowed me to concentrate on SQL concepts such as:

- Databases
- Tables
- Columns and rows
- Data types
- Primary keys
- Identity columns
- NULL and NOT NULL
- Default values
- Relationships
- Foreign keys
- Inserting data
- Querying data
- Updating data
- Safely modifying database structures

I am learning these concepts while actually applying them to CIMS.

My goal is not simply to copy a SQL command and make it run.  I want to understand what the command does, why I would use it, and what effect it has on the database.

## Learning Relational Database Design

One of the biggest differences between simply storing information and building CIMS has been learning how to separate information into related tables.

CIMS is not intended to become one giant table containing my entire career history.

Different information represents different things.

For example:

**Position → Projects → Skills / Accomplishments**

Other information such as education, certifications, awards, training, military service, and professional references can also be maintained in structures appropriate to that information.

These relationships allow me to begin learning how relational databases are designed rather than treating SQL Server as another spreadsheet.

CIMS is still being developed, so the database structure will continue to change as I learn more about SQL and determine how the information should relate.

## Projects and Skills

Projects are an important part of the CIMS design.

A job title by itself does not always explain what someone actually did.

Projects can provide more detailed information about problems I worked on, solutions I implemented, technologies or skills I used, results, lessons learned, and other experience that may be useful later.

This also gives me a way to document hands-on technical work as I continue learning.

The goal is eventually to be able to connect projects and accomplishments with the skills they demonstrate rather than simply maintaining a list of technologies.

## Resume and Career Use

One of the long-term goals for CIMS is to help support resume development.

I do not want CIMS to automatically exaggerate or invent qualifications.

The database should contain information about things I have actually done.

Eventually, I want to be able to compare the requirements of a position with the information maintained in CIMS and identify the experience most relevant to that position.

That could help support different types of resumes without requiring me to rewrite decades of career history from memory every time.

The long-term concept is:

**Career and Experience Inventory → Position Requirements → Relevant Experience → Resume**

I also want the ability to review or override selections rather than allowing an automated process to decide what should appear on a final resume.

CIMS is still being developed toward that goal.

## Expanding Into Microsoft Azure

After becoming more comfortable working with SQL Server locally, I wanted to expand my learning into Microsoft Azure.

At the same time, I was studying for the Microsoft Azure Fundamentals (AZ-900) certification.

I created my own Azure environment so I could work with the services I was studying instead of learning only from reading and practice questions.

I created an Azure SQL logical server and an Azure SQL Database and connected to the Azure database using SSMS from my laptop.

This introduced another environment into the project:

**Local Computer / SSMS → Network → Azure SQL**

The local SQL Server Express database remains my primary learning and development environment while Azure provides a separate environment where I can learn cloud concepts and eventually determine how parts of CIMS could operate in Azure.

## Learning Azure Through CIMS

CIMS gives me something practical to use while learning Azure.

Instead of creating cloud resources only to see whether I can create them, I want to understand why I would use them and how they relate to an actual system.

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

## Learning Through Troubleshooting

Troubleshooting is intentionally part of the CIMS learning process.

One example occurred when I changed the Internet connection being used by my laptop.

My Azure SQL connection worked through my home Internet connection, but changing to an iPhone hotspot changed the public IP address being presented to Azure.

The existing Azure SQL firewall configuration did not automatically recognize the new connection.

Working through that problem helped reinforce why Azure SQL firewall rules exist and how public IP addressing affects access to a cloud database.

Experiences like this are useful because they require me to understand why something stopped working rather than simply memorizing a definition.

I want CIMS to document both successful implementation and the problems I encounter while learning.

## AZ-900 Certification

While developing CIMS and working with my Azure environment, I continued studying Microsoft Azure fundamentals.

I passed the **Microsoft Azure Fundamentals (AZ-900)** exam and earned my first Microsoft certification.

The certification and this project serve different purposes.

AZ-900 validates my understanding of fundamental Azure concepts.

CIMS gives me a place to apply those concepts, work with the technology, troubleshoot problems, and continue developing practical skills.

Passing AZ-900 was not the end of my Azure learning.  It established a foundation that I can continue building on through hands-on work.

## Why the Environment Changed

The technical environment for CIMS has changed as my learning goals have become clearer.

The original Linode environment gave me experience with:

**Linux → Command Line → Docker → SQL Server Container**

The local Windows environment allows me to concentrate on:

**SQL Server Express → SSMS → SQL → Relational Database Design**

The Azure environment allows me to expand into:

**Azure SQL → Networking → Security → Monitoring → Cloud Administration**

Changing the environment was not about abandoning the work I had already done.

Each environment taught me something different.

I decided to use the environment that best supported what I was trying to learn at each stage rather than making the project unnecessarily complicated.

## Current Environment

My current primary CIMS database is being developed locally using:

- Microsoft SQL Server Express
- Microsoft SQL Server Management Studio
- Windows

I also maintain an Azure environment for cloud learning and testing that includes Azure SQL.

The local and Azure environments serve different learning purposes.

I am intentionally continuing development locally before moving additional CIMS work into Azure so that I can concentrate on the database design without unnecessarily consuming cloud resources.

## Cost Awareness

Because Azure is my personal learning environment, cost is part of the design decision.

I do not want to create cloud resources simply because they are available.

I want to understand what a resource does, why I need it, whether it can create charges, and whether there is a lower-cost way to accomplish the same learning objective.

This has made cost monitoring and resource management part of what I am learning about Azure.

As the project grows, I intend to continue documenting why cloud resources are created and what purpose they serve.

## Development Approach

CIMS is being developed incrementally.

I am intentionally learning the underlying concepts as I build rather than attempting to generate the entire database at once.

My general approach is:

**Learn → Build → Test → Troubleshoot → Understand → Document → Continue**

When I encounter a new SQL or Azure concept, I want to understand both how it works and why I would use it before relying on it as part of the project.

This means development may sometimes be slower than simply generating a finished database, but the purpose of CIMS is not only to produce a database.

The purpose is to develop the knowledge required to understand and support what I build.

## Current Project Status

**Status: Active Development / Learning Lab**

CIMS is not a finished production application.

The local database structure is currently being developed and tested in SQL Server Express.

Several database tables have been created as part of the current design, and I am continuing to work through relationships, data entry, queries, and other SQL concepts.

An Azure SQL environment has also been created for cloud learning and testing.

Future work will be documented as it is actually completed rather than represented as finished in advance.

## Repository History

CIMS was already under development before this GitHub repository was created.

The initial documentation in this repository therefore describes work and learning milestones that occurred before the repository existed.

These initial commits establish the project history up to its current development point.

After that baseline is established, future commits will document additional SQL development, database design, testing, troubleshooting, Azure work, and other learning milestones as they actually occur.

The GitHub commit dates for the initial documentation should therefore not be interpreted as the dates when all of the original technical work was performed.

## Future Direction

CIMS provides a foundation that I can continue using as I learn additional technologies.

Possible future areas include more advanced SQL queries, joins, reporting, Azure administration, identity and access, monitoring, Log Analytics, KQL, Azure CLI, Azure PowerShell, networking, security, automation, backup and recovery, and other technologies that make sense as the project develops.

These are future learning areas and are not being represented as completed features.

They will be added to this repository only as I actually learn, build, test, and document them.

## What I Want This Repository to Show

This repository is not intended to show that I already know everything about SQL Server or Azure.

It is intended to document how I am learning.

I want it to show the problems I am trying to solve, the decisions I make, the environments I build, the mistakes and troubleshooting that occur along the way, what I learn from them, and how the project changes as my understanding improves.

CIMS gives me a practical reason to continue learning while producing something useful from that work.

## Data and Security Notice

CIMS is a personal learning and portfolio environment.

It is not a production system and does not contain employer operational data, law-enforcement records, confidential business information, passwords, account credentials, or other restricted information.

Any examples eventually published in this repository will be reviewed and sanitized before being made public.
