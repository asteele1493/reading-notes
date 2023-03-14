# Hash Tables

[Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

[Watch: What is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)

[Basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

[Wiki: Hash Tables](https://en.wikipedia.org/wiki/Hash_table)

Hash - Result of an algorithm taking an inputted string and converting it into a _______ that could be used for security.

Buckets - Contains whatever is in each index of the array of the hash table.

Collisions - Instance of more than one key getting hashed to same _______ in hash table.

Hash tables:

  - Key value pairs
  - Node === Bucket?
  - Lookup value action has an O(1) time complexity
  - Hash code: Turks a key into an integer.

Creating a Hash: step-by-step introductory algorithm

- Add or multiply all the ASCII values together.
- Multiply it by a ______ number such as 599.
- Use modulo to get the remainder of the result, when divided by the total size of the array.
- Insert ______ into the array at that index

If more than one key hashes to the same index in an array, that is called a __________.

  - You'd solve this by changing the initial state of the bucket.

The ______ in a hash table tells us how full it actually is.

## Methods associated with hash tables

```get()``` - input: key, using the key, gets the hash, and goes to the specific index location.

```has()``` - input: key, return: boolean, will tell you if the hashtable contains that specific key. Best way to handle this is to have th econtains call the ```hash()``` method and check if the key exists.

```keys()``` - returns: collection aka array of unique hash keys

```hash()``` - input: key, as a string, returns the index of the array where the key/value should be