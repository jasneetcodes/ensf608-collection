# ER Diagram - Entity Relationship Diagram


Based on the use of abstraction. Reducing an object till you reach the essential characteristics.

## Data Models

A simplified version that supports the understanding of the STRUCTURES, FORMS, and RELATIONSHIPS among the data


3 types of data models:

- Conceptual Model - Big picture view of the system. How it will be organized, business rules. High level of abstraction.

- Logical Model - Detail about the data. Relationships, attributes, concepts.

- Physical Model - Final schema of how the data will be physically stored within a database.


## what is an entity relationship diagram?

Data model used to define data elements, and their relationships with each other.

### Entities

Object that has data stored about it. 

- Strong entity - Have their own PRIMARY KEY. Not dependent on other entity. Drawn as a rectangle

- Weak entity - Does not have their own PRIMARY KEY. Usually COMPOSITE KEY is formed by using its own attributes and a strong entitys PRIMARY KEY. Drawn as a double lined rectangle.

### Attributes

Describe the property of an entity. Drawn as a circle.

- Key - PRIMARY KEY. Drawn with underlined title.
- Composite - Formed by combining 2 attributes. Drawn as a circle with lines connecting to the 2 attributes.
- Multivalued - Can have multiple values. Drawn as a double circle.
- Derived - Formed by the context of other data. Drawn as a dotted circle.



## Example

![Example](/assets/conceptual-er-diagram-example.png)