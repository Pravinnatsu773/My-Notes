Reasons to build Distributed systems
-------------
- Parallelism (High performance)
- Fault tolerance 
- Physical (example: Bank A and bank B systems to communicate with each other.)
- Security / isolated


Challenges
----------
- concurrency
- partial failure
- performance

Infrastructure
--------------
- Storage
- Communication
- Computation

Implementation
--------------
- RPC (Remote procrdure call),
- Threads, 
- Concurrency

Performance
-----------
- Scalability (2 x computers -> 2 x througput)


If you have a HTTP website

For few user:
- users -> website -> serever -> database


For millions of user:

we can reduce the load on one server by distributing the users to different servers.

- 25% users -> websites -> server 1 -> database

- 25% users -> websites -> server 2 -> database

- 25% users -> websites -> server 3 -> database

- 25% users -> websites -> server 4 -> database

Now the servers are not a bottleneck any more but we are still using one common database.
Thus the performance between all servers and common database decreases by huge factor.

To reduce the load on one database, we need to replicate the data from the database to another database.

Fault Tolerance
---------------
- Availability (one system fails  and if it is not repaired even than all of the other systems must be able to serve)
- Recoverability (A system gets failed and after been repaired it must work the same way it was before failure without any loss of performance.)
    
- Tools used for fault tolerance
    1. Non-volatile storage to store a checkpoint or log or state of the system. 
    2. Replication of servers and databases.



Consistency
-----------

Suppose we build a distributed system 
It supports two operation:
- Put(key/value) (Store key value pair)
- Get (key) -> value (get value by key)

1. Then the system must be able to perform this operation request consistently not matter if few server are failed or few replicated databases are failed.

2. After a succesful operation on one databse. On all the other databases same peration must be execute.

3. Placing both the replicated database at one machine room is worst idea because if power goes down all the database turn down.

4. Instead place all replicated databases at different location as far as possible.



Now problem is what if a user want to use this distributed system how they will be able to use it without neing a specialist at this system.

For this problem to be solved engineers designed a framework called MapReduce.

MapReduce
---------
- MapReduce is a software framework that enables you to write applications that process vast amounts of data, in-parallel on large clusters of commodity hardware in a reliable and fault-tolerant manner.

- ![alt Mapreduce example](https://cdn.guru99.com/images/Big_Data/061114_0930_Introductio1.png)