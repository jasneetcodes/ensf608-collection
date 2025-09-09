# Introduction to databases

## Data

Raw form of knowledge, comes from a variety of sources.

Can be processed and analyzed to produce information.

Three types of data discussed:

- Structured Data: Data follows a fixed format, easily organized in tables.
  Ex. Time, Price.

- Unstructured Data: Data does not have a fixed format, harder to organize.
  Ex. Emails, Social media posts, Images.

- Semi structured Data: Data has some consistency with its format, but has flexible fields.
  Ex. JSON log files, XML files.

## Why data storage is important?

Need to store data in order to be analyzed and processed to produce more information.

Type of data influences the storage solution, management techniques, and analytical methods.

- Complexity: Varies depending on data type and structure used to store and manage data.
  Ex. Storing customer records (name, age, email) vs mixed social media interactions (text, images, reactions).

- Scalability: Ability to handle increasing volume of data. Both vertically (hardware) and horizontally (distributed nodes).
  Ex. Transactions of an e-commerce platform.

- Flexibility: Ability to adapt to change in structure or requirements.
  Ex. Store new type of data
  NoSQL databases are usually chosen for their flexibility.

## What is a database?

Used to store, maintain, and access data.

- Store: Keep data persistently.

- Querying: Retrieve specific data efficiently.

- Handling: Mechanisms to manage, update, secure and maintain data integrity.

## What can go wrong with Databases?

Cause major outages, retrieve and store incorrect data, etc.

Factors to consider:

- Validation: Ensure data stored follows rules. Without validation it can result in corrupted data.
  Ex. Student record system accepting negative values for ages.

- Security: Protect data from cyber attacks, and unauthorized access.
  Ex. Encryption, firewalls.

- Recovery: Restore databases after crashes, disasters.

- Performance: Speed at which data can be retrived and updated.
  Ex. E-commerce platform handling traffic spikes during sale events.

## Types of Databases

1. Hierarchical Database

   - Organized in a tree like structure (parent, child).
   - Each child has only one parent.
   - Ex. File System: Root -> Folders -> Files.

2. Relational Database

   - Data stored in tables with rows and columns (relations).
   - Keys define the relationships:
   - Primary Key: The unique identifier (ex. ID).
   - Foreign Key: Connects rows in different tables.
   - Used in apps requiring complex queries and transactional concistency.
   - Ex. Banking systems, inventory management, academic records.

3. NoSQL Database
   - Handles large scale, unstructured or semi structured data.
   - Supports multiple models:
   - Key-Value
   - Document
   - Graph
   - Column
   - Prioritizes availability and partition tolerance, at the cost of strict consistency.
   - Ex. Facebook feed (posts, and comments).

## Database Management System (DBMS)

Software that provides an interface for users to interact with a database.

- Definition: Tools for storage, retrieval, security and updates.
- Updating: Insertion, deletion and modification of data safely.
- Management: Access control, backups, monitoring.

Ex. MySQL, PostgreSQL, Oracle DB, Microsoft SQL Server.
