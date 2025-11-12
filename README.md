# 📦 Fractional Knapsack – Shipping Optimization System

A Python-based program that applies the **Fractional Knapsack Algorithm** to maximize profit in a **shipping scenario** where a truck has a limited capacity.  
Users can add parcels, define capacity, and compute the **maximum profit** using a **greedy approach**.

---

## 🚀 Features

- 🧮 Implements the **Fractional Knapsack Algorithm**
- 📊 Allows **adding multiple parcels** with weight and profit
- ⚙️ Lets you **set truck capacity**
- 💰 Computes **maximum possible profit**
- 📦 Supports **partial loading** of parcels (fractional selection)
- 🖥️ Interactive **menu-driven interface**

---

## 🧠 Algorithm Overview

### 🔸 Concept
The **Fractional Knapsack Algorithm** is a **greedy algorithm** that selects items (or parcels) based on the **highest profit-to-weight ratio** until the capacity is full.  
Unlike the 0/1 Knapsack problem, you can take **fractions of parcels**.

### 🔹 Steps
1. Compute the **profit/weight ratio** for each parcel.  
2. Sort parcels in descending order of ratio.  
3. Pick parcels fully until the capacity is filled.  
4. If remaining capacity is smaller than the next parcel’s weight, take a **fraction** of it.

