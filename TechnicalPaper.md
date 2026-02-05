# NoSQL
- NoSQL is a type of database that doesn’t use the traditional table-and-rows structure you see in SQL databases like MySQL or PostgreSQL.
## Types of NoSQL Databases
There are four major types of NoSQL databases have emerged: 
- document databases
- key-value databases
- wide-column stores
- graph databases
## Document-oriented databases
A document-oriented database stores data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types, including things like strings, numbers, booleans, arrays, or even other objects.
## Key-value databases
A key-value store is a simpler type of database where each item contains keys and values. Each key is unique and associated with a single value. They are used for caching and session management and provide high performance in reads and writes because they tend to store things in memory.
## Wide-column stores
Wide-column stores store data in tables, rows, and dynamic columns. The data is stored in tables. However, unlike traditional SQL databases, wide-column stores are flexible, where different rows can have different sets of columns. These databases can employ column compression techniques to reduce the storage space and enhance performance.
## Graph databases
A graph database stores data in the form of nodes and edges. Nodes typically store information about people, places, and things (like nouns), while edges store information about the relationships between the nodes. They work well for highly connected data, where the relationships or patterns may not be very obvious initially. 

- Source : https://www.mongodb.com/resources/basics/databases/nosql-explained#brief-history-of-nosql-databases
