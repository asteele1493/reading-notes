# Data Structures & Algorithms prep

[WATCH: Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

- Recursion is where a function calls itself.

- There is no performance benefit to using recursion.

- Can make code cleaner and easier to understand.

[WATCH: Data structures in 15 minutes](https://www.youtube.com/watch?v=sVxBVvlnJsM)

[WATCH: Big O explained](https://www.youtube.com/watch?v=v4cd1O4zkGw)

[Basic Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

- Data structures are ways of organizing and storing data.

- Arrays & array operations

- Linked lists (REVISIT)

- Stacks (Last in first out): Think push and pop operations. Checking the status of a stack seems v cool.

- Queues (First in first out): enqueue & dequeue.

- Hash tables: Stores values that have keys associated with them. Hash functions.

- Binary Search Trees: Binary tree where data is organized in a hierarchical structure. Stores values in sorted order. Node composition.

- Heaps: Special case of a binary tree where the parent nodes are compared to their children with their values and are arranged accordingly.

- Graphs: Finite set of vertices or nodes and sets of edges that connect these vertices. Directed vs. undirected graphs.

[Complexity cheat sheet from aforementioned article](https://www.bigocheatsheet.com/)

[Why Big O](https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)

- Big O is the name of the notation used to describe the time and space complexity of an algorithm.

- We should care about algorithms because we want to create good code that takes up a reasonable amount of time and a reasonable amount of space.

- "Needless complexity"

- Logarithmic time = "cutting out half the possible options at each decision point.

## Discussion Questions

**What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?**

- Not sure I completely understand the question. Identifying the data type you are working with will determine the types of operations you are able to perform. I would identify the data type and then build out from there-- what does the algorithm look like, and which operation will help in getting there?

**How can we ensure that we’ll avoid an infinite recursive call stack?**

- Break the code down into smaller, more digestable sets and identify the repeating pattern. Decide if there is a more reasonable algorithm to use instead.

- Base case aka a condition to stop the recursion.
