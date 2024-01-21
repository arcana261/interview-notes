# interview-notes
interview-notes

## CAP Theorem
Link to [wikipedia](https://en.wikipedia.org/wiki/CAP_theorem).

* Consistency
* Availability
* Partition Tolerance

## Poison Pill Message

Poison pills are special messages that can be received, but not processed.
They are a mechanism used in order to signal a consumer to end its work so it
is no longer waiting for new inputs, and is similar to closing a socket in a client/server model.


## ETL Jobs

An extract, transform and load (ETL) developer is a type of software engineer who
helps businesses obtain and copy their data into another database.

## Long Polling vs Short Polling Communication Pattern

Short polling is a simpler form of asynchronous communication, where the client sends
periodic requests to the server at fixed intervals, checking for updates.
This method is less efficient compared to long polling, as it often results in frequent unnecessary requests.

The difference between polling and long polling is that the server keeps the connection
open and finishes the request only when there's an update or the timeout is reached.
This way, fewer resources are wasted on chatty communication between the client and server.

## ACID vs BASE

A [good article from AWS](https://aws.amazon.com/compare/the-difference-between-acid-and-base-database/#:~:text=ACID%20databases%20prioritize%20consistency%20over,can%20access%20inconsistent%20data%20temporarily.).

**ACID**:
- Atomicity
- Consistency
- Isolation
- Durability

**BASE**:
- Basically Available
- Soft State
- Eventually consistent

