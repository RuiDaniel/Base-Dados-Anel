# Distributed Database Management System

This project was developed as part of the **Computer Networks and Internet** course. 
It consists of a distributed database where a large number of objects are partitioned across a small number of nodes. Each object is stored on a single node.

## Features

The database supports the following core operations:

1. **Lookup Operation**  
   A node can query to determine which node is responsible for storing a specific object.

2. **Node Join Operation**  
   A new node can join the database, taking responsibility for storing a subset of objects previously stored on other nodes.

3. **Node Leave Operation**  
   A node can leave the database, transferring its objects to other nodes to maintain data availability.
