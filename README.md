# DSA Simplified - Designed by Engineers for Engineers, [YouTube Channel](https://www.youtube.com/@rikampalkar)
Goal is not to learn each and every new framework or language out there, the goal is to get better at problem solving! PERIOD.
DSA Simplified is your one-stop shop for all DSA queries! Here you will find implementation of all sorts of data structures and algorithms. 

To get ahead of the curve you need to go through these 3 rules of fight club.
1. **Learning Curve** - Implement algorithms by yourself.
   - Code out data structures, till concepts are clear, Implement Stack with Push() and Pop() operations which run on O(1) time complexity.
2. **Problem Solving** - This is where the real game begins!
   - **The Beginning:** 
      - Initially nothing will make sense, don't worry, this is just a start. 
   - **The Question:**
      - Read the question and try to pick hints, slowly you'd learn to recognise patterns just by reading the question.
   - **The Solution:**
      - Initially your solution won't even pass 5 test cases. Point is it doesn't matter but the good news is now you are able to think based on the problem. 
   - **Steal the code:**
      - Try to solve the problem at least for 30 mins before you jump to the discussion tab. Find the best suitable solution and copy paste their entire logic, No one is judging you. 
   - **Debug the code:**
      - Debug copied the solution and figured out what the missing puzzle was? Guess what!! Next time when you come across the same pattern you'll know what to do because you've seen this pattern. This is how I learned how to use remainder (%) LOL. That's one pattern, slowly you'd be able to figure out when to use **Trie** or **Union-Find**. Stay consistent and code for good.
3. keep your track record on! Consistency is key my friend. You can master anything if you're consistent enough. 

You can make me your leetcode partner [Rikam!](https://leetcode.com/rikam/)

## [Big-O Cheat Sheet](https://www.bigocheatsheet.com/) 
[Know Your Complexities!](https://www.bigocheatsheet.com/) 

## Sorting
|     Code        | Best        | Avg         | Worst       | Space       | Learn Here  |
| ----------------|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|
| [Bubble Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/BubbleSort.cs)     | O(n)        | O(n^2)      | O(n^2)      | O(1)        |[Back To Back SWE](https://www.youtube.com/watch?v=euPlXW7dnlI) |
| [Insertion Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/InsertionSort.cs)  | O(n)        | O(n^2)      | O(n^2)      | O(1)        |[Back To Back SWE](https://www.youtube.com/watch?v=ufIET8dMnus) |  
| [Selection Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/SelectionSort.cs)  | O(n^2)      | O(n^2)      | O(n^2)      | O(1)        |[Mycodeschool](https://www.youtube.com/watch?v=GUDLRan2DWM) |
| [Quick Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/QuickSort.cs)      | O(n Log(n)) | O(n Log(n)) | O(n^2)      | O(n Log(n)) |[Back To Back SWE](https://www.youtube.com/watch?v=uXBnyYuwPe8) |  
| [Heap Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/HeapSort.cs)       | O(n Log(n)) | O(n Log(n)) | O(n Log(n)) | O(1)        |[Back To Back SWE](https://www.youtube.com/watch?v=k72DtCnY4MU&t=1107s) |
| [Merge Sort](https://github.com/RikamPalkar/DSA/blob/main/Sorting/MergeSort%20Optimized.cs)      | O(n Log(n)) | O(n Log(n)) | O(n Log(n)) | O(n)        |[Back To Back SWE](https://www.youtube.com/watch?v=GfRQvf7MB3k) |

## Trie : [Example](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Trie/Trie%20example.PNG)
|  [Trie](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Trie/Trie%20example.PNG)              | Time        | Space       |
| ----------------|:-----------:|:-----------:|
| [Build Trie](https://github.com/RikamPalkar/DSA/blob/main/Trie/SuffixTrie.cs)      | O(n^2)      | O(n^2)      |
| [Lookup](https://github.com/RikamPalkar/DSA/blob/main/Trie/SuffixTrie.cs)          | O(n)        | O(1)        |

## Stack
|                 | Push        | Pop         |
| ----------------|:-----------:|:-----------:|
| [Stack with List](https://github.com/RikamPalkar/DSA/blob/main/Stack/Stack%20with%20list.cs)      | O(1)      | O(1)      |
| [Stack with Array](https://github.com/RikamPalkar/DSA/blob/main/Stack/Stack%20with%20array.cs)          | O(1)        | O(1)        |

## Queue
|                 | Enqueue     | Dequeue     |
| ----------------|:-----------:|:-----------:|
| [Queue with List](https://github.com/RikamPalkar/DSA/blob/main/Queue/Queue.cs)      | O(1)      | O(1)      |

## LinkedList
|                 | Insert      | Delete      |Lookup      |
| ----------------|:-----------:|:-----------:|:-----------:|
| [Doubly Linked List](https://github.com/RikamPalkar/DSA-Simplified/blob/main/LinkedList/DoublyLinkedList.cs)      | O(1)      | O(1)      | O(n)      |


## Graph ||  v = vertices, e = edges in graph
### Graph Traversal Algorithms
1. **DFS**: Depth First Search

|                 | Time        | Space       |
| ----------------|:-----------:|:-----------:|
| [DFS with Recursion](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Graphs/Graph%20Traversal%20Algorithms/DFS/DFS%20Recursion.cs)   |O(v + e)   | O(v)        |
| [DFS with Stack](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Graphs/Graph%20Traversal%20Algorithms/DFS/DFS%20Stack.cs)   |O(v + e)   | O(v)        |

2. **BFS**: Breadth First Search

|                 | Time        | Space       |
| ----------------|:-----------:|:-----------:|
| [BFS with Recursion](https://github.com/RikamPalkar/DSA/blob/main/Graphs/Graph%20Traversal%20Algorithms/BFS/BFS%20Recursion.cs)   |O(v + e)   | O(v)        |
| [BFS with Queue](https://github.com/RikamPalkar/DSA/blob/main/Graphs/Graph%20Traversal%20Algorithms/BFS/BFS%20Queue.cs)   |O(v + e)   | O(v)        |


### Dijkstra’s Shortest Path Algorithm

|                 | Time        | Space       |
| ----------------|:-----------:|:-----------:|
| [Shortest Path](https://github.com/RikamPalkar/DSA/blob/main/Graphs/Dijkstra%20Algorithm/Dijkstra's%20Algorithm.cs)   |O(v^2 + e)   | O(v)        |

### Topological Sort

|                 | Time        | Space       |
| ----------------|:-----------:|:-----------:|
| [Topological Sort](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Graphs/Topological%20Sort/TopologicalSort.cs)   |O(v + e)   | O(v + e)  |

## Heap
|                 | Build Heap  | Insert      |    Remove   | 
| ----------------|:-----------:|:-----------:|:-----------:|
| [MinHeap Iterative](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Heap/MinHeap.cs)      | O(n Log(n))      | O(Log(n))      | O(Log(n))     |
| [MaxHeap Recursive](https://github.com/RikamPalkar/DSA-Simplified/blob/main/Heap/MaxHeap.cs)      | O(n Log(n))      | O(Log(n))      | O(Log(n))     |

## LeetCode
|   Leetcode Question     | Solution  | Time Complexity     |    Space Complexity |    Data Structure  | 
| ----------------|:-----------:|:-----------:|:-----------:|:-----------:|
| [1. Two Sum](https://leetcode.com/problems/two-sum/)  |  [Two Sum](https://github.com/RikamPalkar/DSA-Simplified/blob/main/LeetCode/1.TwoSums.cs)      | O(n)      | O(n)      |  Array |  
