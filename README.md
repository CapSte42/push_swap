![push_swap](https://github.com/user-attachments/assets/a466889d-823a-42b8-a965-1fda47239564)



# **push_swap**
Because Swap_push isn’t as natural

## **Project overview**
The **push_swap** project is a crucial part of the **42 curriculum**.
It challenges students to sort a stack of integers using a limited set of operations, with the goal of achieving the smallest possible number of moves.
This project aims to improve understanding of algorithms, data structures, and efficient coding practices in C.

#### **Objective**
- **Sort a Stack**: Implement a sorting algorithm to sort a stack of integers with the fewest moves possible.
- **Use Defined Operations**: Utilize only the allowed operations (`sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, `rrr`) to sort the stack.
- **Algorithm Optimization**: Develop an efficient algorithm that minimizes the number of operations.
- **Error Handling**: Ensure robust error handling for invalid input and edge cases.
- **Checker Bonus**: Implement a checker program to verify the correctness of the sorting algorithm.

#### **Key features**
- **Sorting Algorithm**: Efficient implementation of a sorting algorithm using the defined set of operations.
- **Operation Functions**: Implementation of the allowed operations to manipulate the stack.
- **Input Validation**: Comprehensive input validation to handle various edge cases and invalid inputs.
- **Checker Program**: A separate program to check if a given sequence of operations sorts the stack correctly.
- **Custom Tester**: A utility to test the program, located in the `utility` folder.

#### **Compiling the project
- `make` for the mandatory part (push_swap).
- `make bonus` to compile the bonus part (checker).

#### **Example Usage**
```bash
./push_swap 3 2 1
./checker 3 2 1
```

# **Input custom tester**
A custom tester is provided in the utility folder. To use it, follow these steps:
- Download the files to the root of the project.
- Give execution permissions:
  ```bash
  chmod 500 *sh
  ```
- Run the tester:
  ```bash
  ./test.sh "push_swap"
  ```  
  or for the bonus checker:
  ```bash
  ./test.sh "checker"
  ```
This tester checks the input in various ways and tests for memory leaks, but does not verify the correctness of the output.

#### 🛠 Skills
- c
- Algorithms
- Data structures
- Optimization

#
💬 **Ask Me About:**
- Anything you need related to this project!

#
📫 **How to Reach Me:**
- **42 Students:** Contact me on Slack (smontuor)
- **Others:** Email me at smontuor@student.42firenze.it
