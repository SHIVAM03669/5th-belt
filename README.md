# 5th-belt

### **Easy**  
1. **Sort Colors (Dutch National Flag Problem)**  
   - **Task**: Sort an array of 0s, 1s, and 2s in-place without using library sort.  
   - **Key Challenge**: One-pass algorithm with O(1) space.  
   - **Input**: `[2, 0, 2, 1, 1, 0]`  
   - **Output**: `[0, 0, 1, 1, 2, 2]`  

2. **Assign Cookies (Greedy Algorithm)**  
   - **Task**: Maximize content children by matching cookie sizes to greed factors.  
   - **Key Challenge**: Greedy matching after sorting.  
   - **Input**:  
     - Children: `[1, 2, 3]`  
     - Cookies: `[1, 1]`  
   - **Output**: `1`  
  
3. **Assign Cookies (Greedy Algorithm)**  
   - **Task**: Maximize content children by matching cookie sizes to greed factors.  
   - **Key Challenge**: Greedy matching after sorting.  
   - **Input**:  
     - Children: `[1, 2, 3]`  
     - Cookies: `[1, 1]`  
   - **Output**: `1`  

4. **Stack Operations (Push/Pop/Top)**  
   - **Task**: Simulate stack operations (push, pop, top) with overflow/underflow checks.  
   - **Key Challenge**: Basic stack implementation.  
   - **Input**:  
     ```  
     5 3  // max size = 3, 5 operations  
     push 1  
     push 2  
     top  
     pop  
     push 3  
     ```  
   - **Output**: `2` (top), `2` (pop) 
---

### **Medium**

1. **Reverse a Linked List (In-Place)**  
   - **Task**: Reverse a singly linked list without extra space.  
   - **Key Challenge**: Pointer manipulation.  
   - **Input**: `1 → 2 → 3 → 4`  
   - **Output**: `4 → 3 → 2 → 1`  

2. **Max Consecutive Characters (Sliding Window)**  
   - **Task**: Maximize consecutive 'T's or 'F's in a string by flipping ≤ `k` characters.  
   - **Key Challenge**: Sliding window with two pointers.  
   - **Input**: `"TFFT"`, `k = 2`  
   - **Output**: `4` (flip both 'F's to 'T's → "TTTT")  

3. **Insert into Doubly Linked List**  
   - **Task**: Insert a node at a given position in a doubly linked list.  
   - **Key Challenge**: Managing `prev` and `next` pointers.  
   - **Input**:  
     - Initial list: `8 ↔ 7 ↔ 5 ↔ 3`  
     - Insert `15` at position `0`.  
   - **Output**: `15 ↔ 8 ↔ 7 ↔ 5 ↔ 3`  

4. **Odd-Even Linked List Reorder**  
   - **Task**: Group odd-indexed nodes followed by even-indexed nodes.  
   - **Key Challenge**: Traversal without extra space.  
   - **Input**: `1 → 2 → 3 → 4 → 5`  
   - **Output**: `1 → 3 → 5 → 2 → 4`  

5. **Add Two Numbers (Linked Lists)**  
   - **Task**: Add two numbers represented as reverse-order linked lists.  
   - **Key Challenge**: Handling carry and linked list traversal.  
   - **Input**:  
     - List 1: `2 → 4 → 3` (represents 342)  
     - List 2: `5 → 6 → 4` (represents 465)  
   - **Output**: `7 → 0 → 8` (807)  

6. **Insert into Doubly Linked List**  
   - **Task**: Insert a node at a given position in a doubly linked list.  
   - **Key Challenge**: Managing `prev` and `next` pointers.  
   - **Input**:  
     - Initial list: `8 ↔ 7 ↔ 5 ↔ 3`  
     - Insert `15` at position `0`.  
   - **Output**: `15 ↔ 8 ↔ 7 ↔ 5 ↔ 3`  

7. **Max Consecutive Characters (Sliding Window)**  
   - **Task**: Find max consecutive 'T's or 'F's after flipping ≤ `k` characters.  
   - **Key Challenge**: Sliding window with two pointers.  
   - **Input**: `"TFFT"`, `k = 2`  
   - **Output**: `4` (flip both 'F's to 'T's → "TTTT")  

8. **Detect Cycle in Linked List (Floyd’s Algorithm)**  
   - **Task**: Check if a linked list has a cycle.  
   - **Key Challenge**: Tortoise-and-Hare algorithm (O(1) space).  
   - **Input**: `1 → 3 → 4 → (points back to 3)`  
   - **Output**: `true`  

9. **Rotate Matrix 90 Degrees Clockwise**  
   - **Task**: Rotate an `n x n` matrix in-place.  
   - **Key Challenge**: Layer-by-layer rotation without extra space.  
   - **Input**:  
     ```  
     [1, 2, 3]  
     [4, 5, 6]  
     [7, 8, 9]  
     ```  
   - **Output**:  
     ```  
     [7, 4, 1]  
     [8, 5, 2]  
     [9, 6, 3]  
     ```
Task: Implement two functions for a singly linked list:

Insert: Add a node at a specified 0-based position i.

Delete: Remove a node at a specified 0-based position j.

Constraints:

Use the predefined Node class (no arrays).

Handle edge cases (e.g., invalid positions, empty list).

---

### **Hard**

1. **Detect Cycle in Linked List (Floyd’s Algorithm)**  
   - **Task**: Check if a linked list has a cycle using O(1) space.  
   - **Key Challenge**: Tortoise-and-Hare algorithm.  
   - **Input**: `1 → 3 → 4 → (points back to 3)`  
   - **Output**: `true`  

2. **Rotate Matrix 90 Degrees Clockwise**  
   - **Task**: Rotate an `n x n` matrix in-place.  
   - **Key Challenge**: Layer-by-layer rotation without extra space.  
   - **Input**:  
     ```  
     [1, 2, 3]  
     [4, 5, 6]  
     [7, 8, 9]  
     ```  
   - **Output**:  
     ```  
     [7, 4, 1]  
     [8, 5, 2]  
     [9, 6, 3]  
     ```  
3. **Merge k Sorted Lists (Priority Queue)** *(Implied from skipped challenges)*  
   - **Task**: Merge `k` sorted linked lists into one sorted list.  
   - **Key Challenge**: Efficient merging with O(n log k) time.  

4. **Trapping Rain Water (Two Pointers/Dynamic Programming)** *(Implied from skipped challenges)*  
   - **Task**: Compute how much water can be trapped between bars.  
   - **Key Challenge**: Calculating left/right max arrays or two-pointer approach.  

5. **Longest Valid Parentheses (Stack/Dynamic Programming)** *(Implied from skipped challenges)*  
    - **Task**: Find the longest valid parentheses substring.  
    - **Key Challenge**: Stack-based tracking or DP.  

---
