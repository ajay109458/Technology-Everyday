# Redis

## What is Redis?
Redis is what is called a key-value store, often referred to as a NoSQL database and an apt solution for building highperformance, scalable web applications.

Redis has three main peculiarities that sets it apart.
* Redis holds its database entirely in the memory, using the disk only for persistence.
* Redis has a relatively rich set of data types when compared to many key-value data stores.
* Redis can replicate data to any number of slaves.

Think of it as a small fast database or cache where you can store/retrieve data quickly. Plus the data will still be available when you rerun your program.

## How to install Redis on ubuntu?
Run following commands to install redis on ubuntu
```
sudo apt-get update 
sudo apt-get install redis-server
```
