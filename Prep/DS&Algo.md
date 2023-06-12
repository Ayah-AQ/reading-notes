# DS & Algorithim
## Readings
>1.
The article discusses eight essential data structures for programmers: arrays, linked lists, stacks, queues, trees, graphs, hash tables, and heaps. Each structure has its unique properties and use cases. Understanding these data structures is crucial for efficient problem-solving and algorithm design.

>2.
The article stresses the importance of learning Big O notation for analyzing algorithms. It highlights the significance of efficiency in algorithm design and suggests that understanding Big O notation helps make informed decisions. By grasping the time and space complexities of algorithms, we can optimize our code and avoid inefficient solutions.

## Discussion Questions

> 1.What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?<br/>
```
The key consideration when choosing a data structure is the efficiency of the required operations. Different data structures excel at different operations, such as insertion, deletion, searching, or accessing elements. By analyzing the specific operations needed and their time and space complexity for each data structure, you can select the most suitable one for your problem.
```

>2.How can we ensure that we’ll avoid an infinite recursive call stack?']

To avoid infinite recursive call stacks, follow these steps:
```
1- Define clear termination conditions: Specify when the recursion should stop.
2- Ensure progression towards termination: Make sure each recursive call moves closer to reaching the termination conditions.
3- Validate inputs: Check that the inputs are valid for the recursive calls.
4- Test and debug: Thoroughly test the recursive function with different inputs and use debugging techniques to identify issues.
5- Use proper data structures: Utilize appropriate data structures to prevent revisiting the same elements infinitely.
```
