# Knowledge Graphs

## **Graphs** are collections of *nodes* and *relationships*.

**Nodes** are objects, usually labeled to facilitate classification and search.
- Nodes can exist on their own
- They can have relationships to themselves
- Can have multiple labels

**Relationships** represent connections between nodes.
- They have a single direction and type
- Can have only one label


**Properties** are key-value pairs that can be assigned to a node or a relationship.
- They can be booleans, strings, numbers, points(geometric 2D or 3D points, or coordinates), timestamps, lists (of the same data type)
- Can't be nested

## Neo4j and Cypher

[**Neo4j**](https://neo4j.com/docs/) is a graph database, useful for data and queries that are extremely large, complex and highly interconnected. 

I will use the [Neo4j Sandbox](https://sandbox.neo4j.com/) to test it.

- **Cypher** is the language we use to query Neo4j. 