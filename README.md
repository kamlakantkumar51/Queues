# Queues
# Queue in Java

## What is a Queue?
A **Queue** in Java is a **linear data structure** that follows the **FIFO principle**:

> **FIFO – First In, First Out**

This means:
- The element added **first** is removed **first**
- Similar to a real-life queue (line) at a ticket counter

---

## Queue Interface in Java
In Java, **Queue** is an **interface** present in:
##----------------------------------------------------------------------------------------------------------------------------------

#circular queue
# Circular Queue in Java

## What is a Circular Queue?
A **Circular Queue** is a **linear data structure** where the **last position is connected back to the first position**, forming a **circle**.

It follows the **FIFO (First In First Out)** principle like a normal queue, but **reuses empty spaces** efficiently.

---

## Why Circular Queue?
In a **normal queue (array-based)**:
- After deletions, empty spaces at the front **cannot be reused**
- Leads to **memory wastage**

👉 **Circular Queue solves this problem** by wrapping around.

---

## Circular Queue Representation
- Uses an **array**
- Two pointers:
  - `front` → points to first element
  - `rear` → points to last element
- Next position is calculated using:
  
