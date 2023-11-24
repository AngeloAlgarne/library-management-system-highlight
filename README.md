This repository showcases **_Library Management System (LMS)_**, my professional project for [A.M.Yu & Associates](https://www.amyucpas.com/).
# Introduction
The LMS is a web-application built using Django Framework (with jquery) and uses PostgreSQL database, that includes basic CRUD functions. A local server is used to host both the database and the web-app (served by apache2 in Ubuntu).

The main purpose of the LMS is to automate a logbook system for internal purposes. Information such as what item was borrowed, when it was borrowed or returned, and who borrowed it, are all stored to easily track the statuses of each item. 

_Note that the the screenshots below are using sample data only._
# Video Demonstration
For quick reference, a [video demonstration](https://youtu.be/lsCTQvj9PCE) can be watched to highlight the user interface of the LMS.
# Features
The LMS has various features that allow users to view and manage data. It is tailored to the company's standards, and as such, there are additional displayed columns. Some of the features can be seen below in the following subsections.
## Login page
A login function is implemented to authenticate each user session.
![Screenshot of the Login page](images/login.jpg)
## Dashboard
The Dashboard page is present to summarize the recent changes in the logbook.
![Screenshot of the Dashboard page](images/dashboard.jpg)
## CRUD
**Create**: Adding new members that may access the LMS, or even new items that are to be borrowed, can be done by librarians.
![Screenshot of creating a new member](images/create.jpg)

**Read**: Each page reads the most imporant tables to display. For example, the Members page shows all the users that has an account for the LMS.
![Screenshot of viewing the members page](images/members.jpg)

**Update**: A record can be edited via the side panel by librarians.
![Screenshot of editing a member record](images/update.jpg)

**Delete**: Since deleting records is highly discouraged, only the superusers/admins can delete a record using the Django Admin Panel.
![Screenshot of deleting member in admin panel](images/delete.jpg)
## Side Panel
The side panel holds most of the main functions of LMS. Clicking a record from the tables or search results will open the record's details on the side panel. 
![Screenshot of viewing record on side panel](images/sidepanel1.jpg)

And most importantly, functions such as borrowing, returning, editing, or even borrowing/returning in bulk (Basket function), can be done here as well.
![Screenshot of returning in bulk](images/sidepanel2.jpg)
# Obsidian
This repository is handled through [Obsidian](https://obsidian.md/), a note-taking software application that operates on Markdown files. A community plugin called **Obsidian Git** is installed to manage the content of this markdown file. Check out the official plugin on [this page](https://github.com/denolehov/obsidian-git).
# Inquiries
If you wish to contact me regarding this project, you may do so by messaging me at LinkedIn ([in/johnangeloalgarne](https://www.linkedin.com/in/johnangeloalgarne/)).