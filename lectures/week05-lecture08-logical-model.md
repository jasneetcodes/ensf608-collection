# Logical Model

It has more details about the relationships, as well as defining the data attributes

It adds on to the conceptual model by explicitly defining the details associated to the data scheme

- Organization
- Domain
- Intergrity

## Things it adds on to the conceptual model

- Attribute: The column / field in a database. Represents a piece of data regarding an entity.

Ex. Name, Age, Salary

- Domain: A set of allowable values for an attribute. Includes range, as well as the type of data.

Ex. Age attribute needs to be INTEGER, and between 18 - 65

- Tuple: A row / record in a database. Each tuple contains a set of data by the attributes in the table.

Ex. A person tuple with values for Name, Age, Salary

- Schema: The structure of a database that defines how data is organized.

Ex. Employee database is structured with tables Employees, Department, and Salaries




![Logical Model](/assets/logical-model.png)


## Domain: Data and Semantics

Domain example: Names of Cities in Canada Varchar(20)

In this example the 'Names of Cities in Canada' is semantics, and Varchar(20) is the Data Type.

Domain ensures integrity in various functions of the database.