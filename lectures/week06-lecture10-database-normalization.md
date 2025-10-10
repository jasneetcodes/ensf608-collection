# Normalization


Process of structuring a relational database

Purpose:

- Minimize Redundancy
- Minimize Dependency

** Ensures data is stored ONLY ONCE to avoid DATA ANOMALIES **


## Common Normal Forms

Normalization is done in STAGES, called NORMAL FORMS (NF)

The Three Forms are 1NF, 2NF, 3NF


### 1NF: Atomicity

Focus: Atomicity of Values

Goal: Eliminate repeating groups

Key characteristics:

- All attributes myst contain ATOMIC values
- No multivalued attribues
- Each record is unique

Ensure atomic values, eliminate repeating groups

### 2NF: Partial Dependencies

Focus: Eliminate Partial Dependencies

Goal: All non key attributes must depend on the WHOLE primary key

Key characteristics:

- Must be in 1NF
- No partial dependencies
- Tables with a composite with a primary key

Remove partial dependencies by splitting into separate tables


### 3NF: Transitive Dependencies

Focus: Eliminate Transitive Dependencies

Goal: Ensuring that non key attributes don't depend on other non key attributes

Key characteristics:

- Must first be in 2NF
- There should be no transitive 

Eliminate transitive dependencies by creating additional tables for attributes that depend on non-key attributes

## Advanced Normal Forms

1. BCNF - Boyce - Codd Normal Form

Focus: Make sure every dependency in a table is based on a key

For every dependency X ->: X must be a superkey(uniquely identifies rows)

** If something determines other columns, that something better be a KEY

** Fixes 3NF overlap where a table has MULTIPLE CNADIATE KEYS

2. 4NF

Focus: Remove multi valued dependencies

Goal: Make sure that no table contains two or more independent multi valued facts about an entity

If one record can have multiple A and multiple of B, AND those two DONT depend on each other THEN SEPERATE THEM INTO TWO TABLES

Example. Student | Hobby | Language

Student can have MANY Hobbies AND MANY Langues. They are not related so they can be split into 2 different tables.

3. 5NF

Focus: Remove Join dependencies

Goal: Make sure you can't break a table into a smaller one, and then lose or duplicate information when joining them back together

** Only keep tables that can't be split further without losing meaning. Most atomic possible design

Prevents hidden redundancy from complex many to many relationships


