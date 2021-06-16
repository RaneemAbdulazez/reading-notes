# Hash Tables

> What Is Hash Tables?


*Hash Table is a data structure which stores data in an associative manner. In a hash table, data is stored in an array format, where each data value has its own unique index value. Access of data becomes very fast if we know the index of the desired data.*

**Hashing**
*Hashing is a technique to convert a range of key values into a range of indexes of an array. We're going to use modulo operator to get a range of key values. Consider an example of hash table of size 20, and the following items are to be stored. Item are in the (key,value) format.*

![hash_function](images/hash_function.jpg)

| Sr.No | Key |   Hash   | Array Index |
|:-----:|-----|:--------:|-------------|
|   1   | 1   |  1%20=1  | 1           |
|   2   | 2   |  2%20=2  | 2           |
|   3   | 42  |  42%20=2 | 2           |
|   4   | 4   |  4%20=4  | 4           |
|   5   | 12  | 12%20=12 | 12          |

**Linear Probing**

*As we can see, it may happen that the hashing technique is used to create an already used index of the array. In such a case, we can search the next empty location in the array by looking into the next cell until we find an empty cell. This technique is called linear probing.*

| Sr.No | Key |   Hash   | Array Index | After Liner Probing |
|:-----:|-----|:--------:|-------------|---------------------|
|   1   | 1   |  1%20=1  | 1           | 1                   |
|   2   | 2   |  2%20=2  | 2           | 2                   |
|   3   | 42  |  42%20=2 | 2           | 3                   |
|   4   | 4   |  4%20=4  | 4           | 4                   |
|   5   | 12  | 12%20=12 | 12          | 12                  |


**Basic Operations**

`Search` − Searches an element in a hash table.

`Insert` − inserts an element in a hash table.

`delete` − Deletes an element from a hash table.

