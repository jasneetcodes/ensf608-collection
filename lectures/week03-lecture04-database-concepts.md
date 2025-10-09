Format : Question - Evidence - Answer

# Database Concepts

## What is a database system?

- Contains ORGANIZED collection of data
- Has SOFTWARE and HARDWARE that manage data, and provide services to users
- HAS Data, Information, DBMS


## Different Data Types


### What are the two types of data?

- Quantitative: Numerical and measurable
- Qualitative: Descriptive and categorical, provdies insights into char and qualities

### What is the difference and link between Data, Information, and Decision?

- Data is raw. No context.
- Information is data with context and meaning. Processed.

Through giving data CONTEXT and MEANING, we derive information, WHICH then can be used to make DECISIONS.


## What are the different types of information?

Categorized based on the type of knowledge given to support a decision.

- Descriptive: Provides a snapshot of a situation. Good for understanding present situations. Ex. This month's sales numbers.

- Preditictive: Forecasts future events based on HISTORICAL data. Helps anticipate future scenerios. Ex. This year's expected sales figures estimated on past performance.

- Prescriptive: Uses ANALYSIS and PREDICTIVE models to recommend ACTIONS or SOLUTIONS. Ex. Ways to increase sales based on analyzing top performer's behaviour and or actions.


## What is a database architecture?

It is the design of the database system. How data is STORED, MANAGED, and RETRIEVED.

Layers of the architectures:

- External Level - How data is viewed by users
- Conceptual Level - Structure of the database. Entities, relationships, constraints, data types
- Internal Level - How data is stored physically on storage media. Data structuring, file organization, data indexing
- Database - The actual database.

### What are the differnt types of database architectures?

- Centralized - Components reside on a single system. Good for small to medium sized apps with low concurrency (Simultanous Actions) needs. 1 Machine holds the database.
- Client Server - Splits the database. Runs on a server while the users interact with it through a network. Better for high concurrency and multiple users. 1 Machine holds the database, yet many machines can look at the database.
- Distributed - Distributed across locations. Needs databases to be synchronized. High fault tolerability tho
- Cloud Based - Through Platforms (AWS, Azure). Scalablity and flexibility, reduced operational costs but need to use tools provided by platform.


## What are the database core components?

Store manager: 
- Manages the physical storage
- Includes buffer manager, file manager, disk space manager

Query Processor:
- Translates the queries into low level instructions, that machine can understand
- Includes data interpreter, the data compiler, the query optimizer

Transaction Manager:
- Makes sure there is reliability for the data transactions.
- Manages ACID (Atomicitiy, Consistency, Isolation, Durability)

Integrity Manager:
- Enforces security and integrity constraints
- Access control for data based on USER ROLES, and PRIVILAGES