# Logistics-Optimization-Using-Excel-Solver-Transportation-Model-

##  Project Overview

This project demonstrates how Excel Solver can be used to optimize product shipments from multiple warehouses to multiple retail stores while minimizing total transportation distance. The goal was to meet all store demand without exceeding warehouse inventory, using linear optimization techniques.

## Before Optimization
<img width="1913" height="984" alt="Image" src="https://github.com/user-attachments/assets/1fe75ad1-1aad-465f-a305-e53c5bb370f0" />

##  Business Problem

A company operates:

* **3 Warehouses**, each with limited inventory
* **Multiple Retail Stores** with fixed product demand
* **Different shipping distances** between each warehouse and store

The challenge was to determine:

> How many units should be shipped from each warehouse to each store in order to **minimize total shipping miles**, while satisfying:

* All store demand
* All warehouse inventory limits



## 🛠 Tools Used

* Microsoft Excel
* Excel Solver (Optimization Add-in)
* SUMPRODUCT formula for cost calculation


## 📊 Model Structure

### 1. Demand Table

Each store has a required number of units.

### 2. Inventory Table

Each warehouse has a limited number of units available.

### 3. Distance Matrix

Shipping distance from each warehouse to each store.

### 4. Decision Variables (Yellow Cells)

These cells represent how many units are shipped from each warehouse to each store.


##  Solver Configuration

**Objective:**

* Minimize **Total Miles**

**Decision Variables:**

* All yellow shipping cells

**Constraints Applied:**

* Each store’s total shipment = Store demand
* Each warehouse’s total shipments ≤ Available inventory
* All decision variables ≥ 0

Solver was run using the **Simplex LP method**.


##  Results (Optimized Solution)

Solver automatically assigned shipment quantities so that:

* All store demands were fully satisfied
* No warehouse exceeded its inventory
* Total shipping miles were reduced to the minimum possible value

This resulted in a highly efficient distribution plan with **minimum transportation cost**.


##  Key Skills Demonstrated

* Linear optimization modeling
* Transportation problem formulation
* Excel Solver setup and configuration
* Constraint-based decision analysis
* Operations & supply-chain analytics



##  Key Takeaway

This project shows how Excel Solver can be used for ** logistics optimization**, helping businesses cut transportation costs while maintaining service levels.




