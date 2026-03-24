# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

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
~~~
queue = []

queue.append('a')
queue.append('b')
queue.append('c')

print('Queue after elements are inserted:')
print(queue)

print('Deleting the first element inserted:')
print(queue.pop(0))

print('Queue after the first elements is deleted:')
print(queue)
~~~

## Output
<img width="843" height="246" alt="image" src="https://github.com/user-attachments/assets/d06be383-a06e-42a5-8f4b-3bd5623cbdbc" />


## Result
Thus the output is verified.
