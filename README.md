# EX 12 (A) Queue using Linked List - Insert, Display, and Delete

## Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.
---

## Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
```
queue = []

queue.append('a')
queue.append('b')
queue.append('c')

print("Queue after elements are inserted:")
print(queue)

print("Deleting the first element inserted:")
print(queue.pop(0))

print("Queue after the first elements is deleted:")
print(queue)
```
## Output
<img width="886" height="223" alt="image" src="https://github.com/user-attachments/assets/6d201d55-91fb-4236-9861-f8dd5344e5aa" />

## Result
  Thus, the python program to insert, display and delete the elements in the queue using linked list has been executed successfully.

# EX 12 (B) Queue using Linked List: Display Front and Rear Elements of a Queue

## Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---
## Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
```
queue = []

queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

print('Initial Queue: ' + str(queue))

front = queue[0]

print("\nElement at the front of the queue is .... ", front)

rear = queue[3]

print("\nElement at the rear of the queue is .... ", rear)
```
## Output
<img width="939" height="194" alt="image" src="https://github.com/user-attachments/assets/0c756432-06f6-41cc-a1a1-ac84c6cfc63c" />

## Result
  Thus, the python program to display front and rear elements of a queue using a linked list is executed successfully.

## EX 12 (C) Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## Aim
To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## Program
```
from queue import LifoQueue

stack = LifoQueue(maxsize=4)

stack.put('a')
stack.put('b')
stack.put('c')
if stack.full():
    print("Stack is full")
else:
    print("Stack is not full")
```
## Output
<img width="656" height="179" alt="image" src="https://github.com/user-attachments/assets/7e3ee1d4-99b3-4ef6-b7aa-9e13887f400f" />

## Result
  Thus, the python program to check and display whether the stack is full or not using linked list has been executed successfully.

# EX 12 (D) Stack using Linked List: Check and Print the Index Value of the Elements Stored in the Stack

This Python program demonstrates how to:
1. Create a stack using a list.
2. Add elements to the stack.
3. Print the index and corresponding value of each element in the stack.

## Aim
To write a Python program that:
- Creates a stack using a list.
- Adds elements to the stack.
- Prints the index values of the stack elements along with the corresponding values.

## Algorithm

1. **Create an Empty Stack**:
   - Initialize an empty list `stack` to store elements.

2. **Add Elements to the Stack**:
   - Append elements (e.g., 'a', 'b', 'c') to the stack using the `append()` method.

3. **Print the Initial Stack**:
   - Print the contents of the stack with a message "Initial stack: ".

4. **Iterate through the Stack**:
   - Use a `for` loop with `range()` to iterate through the stack.
   - Print the index value and corresponding element at that index.

5. **Print Index and Value**:
   - For each element in the stack, print the index and the value at that index.

## Program
```
stack = []
stack.append('a')
stack.append('b')
stack.append('c')

print('Initial stack: ' + str(stack))

for i in range(len(stack)):
    print(i, stack[i])
```
## Output
<img width="1150" height="246" alt="image" src="https://github.com/user-attachments/assets/3cd3799a-0328-4fca-8b38-7e75ef656dcb" />

## Result
 Thus, the python program to check and print the index values of the elements stored in the stack using linked list is executed successfully.

# EX 12 (E) Stack using Linked List: Stack Implementation (Top Element Display)

## Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## Algorithm
1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## Program
```
stack = []

stack.append('a')
stack.append('b')
stack.append('c')
stack.append('d')

print('Initial stack: ' + str(stack))

for i in range(len(stack)):
    top = stack[i]

print("\nElement at the top of the stack is .... ", top)

stack.pop()

for i in range(len(stack)):
    top = stack[i]

print("\nAfter removing an element from the stack.")
print("\nElement at the top of the stack is .... ", top)
```
## Output
<img width="913" height="300" alt="image" src="https://github.com/user-attachments/assets/0b4de084-17b6-4a9e-98ae-f7826af5fbd3" />

## Result
  Thus, the python program to print the top element of the stack is executed successfully.
