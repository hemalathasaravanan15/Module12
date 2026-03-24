# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 4 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 4 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 4 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
~~~
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
~~~

## Output
<img width="913" height="300" alt="image" src="https://github.com/user-attachments/assets/752b22f5-d40b-436e-b131-2024ffc30aed" />


## Result
Thus the output is verified.
