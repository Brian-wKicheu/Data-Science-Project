# Data-Science-Project
This is a data science simple projects
Use an external library to simplify tasks from earlier ORM lessons.
Use SQLAlchemy to create, read, update and delete records in a SQL database.

# Key Vocab
Schema: the blueprint of a database. Describes how data relates to other data in tables, columns, and relationships between them.
Persist: save a schema in a database.
Engine: a Python object that translates SQL to Python and vice-versa.
Session: a Python object that uses an engine to allow us to programmatically interact with a database.
Transaction: a strategy for executing database statements such that the group succeeds or fails as a unit.
Migration: the process of moving data from one or more databases to one or more target databases.

# Introduction
In the previous lesson, we created and persisted a database schema using SQLAlchemy. This required us to define classes that inherited from a common declarative_base object and that possessed certain attributes that would be used to assign a table name, columns, primary keys, and more.

In this lesson, we'll be building on the same schema. The code from last lesson's code-along can be found in app/sqlalchemy_sandbox.py. Run chmod +x app/sqlalchemy_sandbox.py to make it executable.

Note: we are using a SQLite database in memory now instead of a students.db file. This will allow us to make changes to our schema without running into issues. We will learn how to address changing a schema when we discuss migrations later in this module.
