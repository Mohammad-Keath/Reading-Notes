- ## SQL and noSQL   .  [<sub>    Reference </sub>](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

 1. What type of database is the best fit for the complex query intensive environment?
    - SQL

 2. What type of database is the best fit for hierarchical data storage?
    - noSQL
 3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
    - noSQL is a huge ware house that contain what ever you want inside it and every box has all what you need inside it with no need to search about each tool alone.
    - SQL is a small wareshop 

 4. Among data tables, what is a one-to-many relationship and how do we “relate” them?
    - First it must be SQL DB
    - the one to many relation is a relation between one thing to more than one for example:
       - if you have a student inside the school he is in the first grade, and the first grade has many student not just one

 5. Prior to designing your relational database, it might be useful to create a new table of the database tables and their relationships.

 6. Explain the difference between a primary and foreign key.
    - the primary key is the id of the table's content 
    - the foreign key is the id od other table's inside different table to make relation between them
 7. How do we treat keywords and parameters differently in SQL syntax?
    - key words: are special words in SQL that do specific things like (SELECT,FROM,....)
    - parameters: flexible quiers that acting values while runtime
 8. Define normalization within the context of schemas and data.
    - to minimise the data and not allowing to blank spots and do relations between data
 9. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
    - one to one: is simple relation for example : one student with one tutor (privet studing)
    - one to many: is abit more complex but still no need to add table for relation for example : group of student with one tutor 
    - many to many: a complex relation that needs to add specifice table just for relations for example:
    a school of many student that are teached by many teachers and those teachers teach other student
