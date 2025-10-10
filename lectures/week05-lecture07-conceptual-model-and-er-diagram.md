# ER Diagram Part 2


## Relationships

Defines the connections between entities

Represented as a diamon in ER Diagram

Different types of relationships:

- One to One
- One to Many
- Many to One
- Many to Many


![Relationship](/assets/er-diagram-relationships.png)


## Generalization and Specialization

In real life, entities relate to each other in hierarchical ways.

In ER Diagrams, we use specialization and generalization to represent this hierarchy


- Generalization: Using shared characteristics or features of two or more entities  to form a higher level, generalized entity

Ex. Student and Professor entities, -> Person Entity


- Specialization: Creating specific sub entities based on a higher level generalized entity

Ex. 1.Student entity -> 1a. Undergrad student, 1.b Grad student


## Types of Specialization

### Disjoint Specialization (Mutually exclusive)

An entity can only belong to one specialized category. No parent entity can be classified as more than one of the specialized entities. 

Represented as 'd' in an ER Diagram

Ex. Student -> Full time student OR Part time student


### Overlapping specialization (Simultaneously Existing)

An entity can belong to more than one specialized category. Instance of parent entity can fit into multuple specialized entities at the same time.

Represented as 'o' in an ER Diagram

Ex. Student -> Online Student AND In-person Student


## ANALYSIS

Help make sure that we use the proper classification of entities within a system.

- Improve clarity and structure of the ER Diagram
- Using DS, we can prevent improper categorization
- Using OS, we can allow more flexibility
