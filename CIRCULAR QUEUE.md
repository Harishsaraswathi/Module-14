Skip to content
Jothivanan07
Module-14
Repository navigation
Code
Pull requests
Actions
Projects
Security
Insights
You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork Harishsaraswathi/Module-14, so you can send a pull request.
Module-14
/
CIRCULAR QUEUE.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing CIRCULAR QUEUE.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
# Exp No: 14b  
## Circular Queue 
---

### AIM  
To write a Python program with a function to insert float values into a Circular Queue.

---

### ALGORITHM

1. Start  
2. Check if the Circular Queue is full  
   - If `size == max_size`, print `"Queue is full"` and exit the function  
3. If the queue is not full:  
   - Read the element to be inserted  
   - Convert it to float  
   - Insert the element at the `tail` position  
   - Update tail using: `tail = (tail + 1) % max_size` (circular increment)  
   - Increment `size` by 1  
4. End

---

### PROGRAM

```python
class Queue:
    def __init__(self, size):
        self.items = [0] * size
        self.max_size = size
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
