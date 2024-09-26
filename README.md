# 🌳 Binary Tree & Stack Implementation

This project implements a binary tree structure with basic operations (such as pre-order, in-order, and post-order traversals) and a stack to assist with tree-related functionalities. The project was developed as part of an academic exercise and includes a command-line interface (CLI) for user interaction.

## 📂 Project Structure

- **`main.c`**: Contains the main logic and a CLI that allows users to interact with the binary tree and stack.
- **`binary_tree.c`**: Implements the binary tree structure and its associated operations, such as insertion, search, and traversal methods.
- **`binary_tree.h`**: Header file for the binary tree functions and structure definitions.
- **`pilha.c`**: Implements a stack used to help in managing the nodes of the binary tree.
- **`pilha.h`**: Header file for the stack (pilha) definitions and function declarations.
- **`MAKEFILE`**: Script to compile the project and manage build tasks.

## 🔧 How to Compile

To compile the project, run the following command in the terminal:

```
make
```

This will generate the executable binary_tree_program.

## 🚀 How to Run
After compilation, execute the program with:

```
./binary_tree_program
```

Once running, you can use the following commands to interact with the 
binary tree:

## Available Commands

```
insert X: Inserts node X into the binary tree.
pre: Prints the tree in pre-order traversal.
in: Prints the tree in in-order traversal.
post: Prints the tree in post-order traversal.
height X: Displays the height of the node X.
print: Prints the hierarchy of the entire tree.
exit: Exits the program.
```

## Example of Usage
```
insert A
insert B
insert C
in
pre
height A
print
exit
```

## 🛠️ Cleaning Up
To remove object files and the executable, run:

```
make clean
```