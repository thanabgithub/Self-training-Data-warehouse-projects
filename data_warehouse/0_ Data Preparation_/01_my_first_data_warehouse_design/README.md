
## Background

This sub-project is part of my large project to become a data scientist with independent end-to-end (in the term of data lifecycle) capabilities. 

At the moment (2022-01-30), My study plan is to study from datawarehouse (SQL), ETL (PySpark), Machine Learning Theory (Numpy, Numba, cuPy) and Machine Learning Model Implementation (PyTorch). If you have any suggestion, please feel free to open an issue and share your opinion.

This sub-project is my fist step. Since data warehouse (dimentaional modeling) is convinient for data analytics, I chose to rather focus on it than OLTP. In the term of SQL, I studied from a book named "Getting Started with SQL A Hands-On Approach for Beginners". In the term of data warehouse development, I studied from a book named "The Data Warehouse Toolkit The Complete Guide to Dimensional Modeling". 

## This Sub-project Problem

Since this is my first time for designing a database, I chose to make it simple. As I studied from the SQL book, there is an example database. I chose to implement my knowledge from the data warehouse book by converting an example data model from the SQL book to dimensional model.

Here is the background of the database from the SQL book

    The SurgeTech Conference
        You are a staff member for the SurgeTech conference, a gathering of tech startup
        companies seeking publicity and investors. The organizer has tasked you with creating
        a database to manage the attendees, companies, presentations, rooms, and presentation
        attendance. How should this database be designed?
        First, review the different entities and start thinking about how they will be structured
        into tables. This may seem like a large number of business asks to capture, but any
        complex problem can be broken down into simple components.

![Original data model](conference_OLTP_BEFORE.png)

## Result

Actually, I'm not sure whether I designed correctly or not but this is my dimensional data modeling design.

![Original data model](conference_OLAP_AFTER.png)