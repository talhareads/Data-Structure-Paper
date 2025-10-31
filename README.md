🏥 Hospital Emergency Queue System (Doubly Linked List)
📘 Project Overview
# 🏥 **Hospital Emergency Queue System (Doubly Linked List)**

This project simulates a Hospital Emergency Room (ER) Queue System using a Doubly Linked List in C++.
It helps manage patients based on priority — allowing critical patients to be treated first and others to wait in order.
The system provides efficient insertion and deletion of patients from any position in the list.
---

🎯 Features / Operations
## 📘 **Project Overview**
This project simulates a **Hospital Emergency Room (ER) Queue System** using a **Doubly Linked List** in **C++**.  
It efficiently manages patients based on **priority**, ensuring that **critical patients are treated first**, while normal walk-in patients wait their turn.  
The system allows **fast insertion and deletion** of patients at the beginning, end, or any position in the queue.

insertAtBeginning(patientID) – Adds a critical patient to the start of the list.
---

insertAtEnd(patientID) – Adds a normal walk-in patient to the end of the list.
## 🎯 **Features / Operations**
| Function | Description |
|-----------|-------------|
| 🩺 `insertAtBeginning(patientID)` | Adds a **critical patient** at the start of the list. |
| 🚶 `insertAtEnd(patientID)` | Adds a **normal walk-in patient** at the end of the list. |
| ⚖️ `insertAtPosition(patientID, position)` | Inserts a patient at a specific **priority position** in the list. |
| 🏁 `deleteFromBeginning()` | Removes the **first patient** after treatment. |

insertAtPosition(patientID, position) – Inserts a patient at a specific priority position.
---

deleteFromBeginning() – Removes the first patient after treatment.
## ⚙️ **Data Structure Used**
A **Doubly Linked List** is implemented, where each node contains:
- 🔢 `patientID` — Unique identifier for each patient  
- ⬅️ `prev` — Pointer to the previous patient  
- ➡️ `next` — Pointer to the next patient  

⚙️ Data Structure Used
This structure allows **bi-directional traversal** and efficient real-time queue updates.

Doubly Linked List
---

Each node contains:
## 🧩 **Dry Run / Step-by-Step Example**

patientID (integer)
Starting from an **empty list**, the following operations are performed:

prev pointer (to previous patient)
1️⃣ `insertAtEnd(101)`  
2️⃣ `insertAtEnd(102)`  
3️⃣ `insertAtBeginning(200)` *(Critical patient)*  
4️⃣ `insertAtPosition(150, 2)`  
5️⃣ `deleteFromBeginning()`  
6️⃣ `insertAtEnd(300)`

next pointer (to next patient)
### ✅ **Final Output**
| Property | Value |
|-----------|--------|
| **Head** | 150 |
| **Tail** | 300 |
| **Forward Traversal** | 150 → 101 → 102 → 300 |
| **Backward Traversal** | 300 → 102 → 101 → 150 |

🧩 Dry Run / Example Steps
---

Starting with an empty ER list, the following operations are performed:
## 🧠 **Working Methodology**

insertAtEnd(101)
1. Initialize an **empty ER list**.  
2. Add patients using insertion functions based on their urgency.  
3. Update **head**, **tail**, **prev**, and **next** pointers after each operation.  
4. Remove the first patient once treated.  
5. Ensure the list remains properly linked in both directions.  
6. Continue operations dynamically as new patients arrive.

insertAtEnd(102)
---

insertAtBeginning(200) → Critical patient
## 💻 **Technologies Used**

insertAtPosition(150, 2)
| Component | Description |
|------------|-------------|
| 💬 **Language** | C++ |
| 🧱 **Data Structure** | Doubly Linked List |

deleteFromBeginning()

insertAtEnd(300)
---

Final Output:
## 📚 **Conclusion**
This project demonstrates how a **Doubly Linked List** can effectively handle real-world queue management in hospital emergency systems.  
It ensures **fair, priority-based treatment**, supports **dynamic updates**, and maintains **efficient patient flow** in the ER.

Head: 150
---

Tail: 300
## 👨‍💻 **Author**
**Name:** *Talha Rashid*   

Forward Traversal: 150 → 101 → 102 → 300

Backward Traversal: 300 → 102 → 101 → 150

🧠 Working Methodology

Start with an empty ER list.

Insert patients based on their urgency level.

Update all head, tail, prev, and next pointers after each operation.

Remove patients after treatment.

Maintain the correct order dynamically in real time.

💻 Technologies Used

Language: C++

Data Structure: Doubly Linked List



📚 Conclusion

This project successfully demonstrates how a Doubly Linked List can be used to manage real-world priority queues like hospital ER systems.
It ensures that critical patients are treated first and the queue dynamically updates as patients are added or removed.
## 👨‍💻 **Author**
**Name:** *Talha Rashid* 
