# Logical Model Mapping


![Logical Model One](/assets/logical-model-recap-one.png)

![Logical Model Two](/assets/logical-model-recap-two.png)



## Key things to keep in mind when mapping

- Try to keep the number of tables low
- Get rid of optional non-relevant attributes
- Avoid reference dependencies
- Control INTEGRITY and RESTRICTIONS

**These rules try to ensure normalization**


## STEP 1: Strong Entities

1. Create a table for the strong entities
2. Attributes become fields
3. Declare primary keys (underline them)


## STEP 2: Relationships

1. Create a table for each relationship between entities
2. Bring the Primary key from the entities as a foreign key (#)
3. Declare primary keys 


## STEP 3: Weak Entities

1. Create a table for the weak entities
2. Attributes become fields
3. Bring the primary key from the strong entity as a foreign key

## STEP 3.5: Special Attributes

1. Create a table for each composite and multivalued attribute
2. Composition becomes fields.
3. Bring the primary key from the strong entity in which it belongs as a foreign key
4. Define primary keys