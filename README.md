# Metro-Management-System-DSA

This project simulates a metro network using graph data structures and algorithms. It provides functionalities such as fare calculation, network modification, and congestion detection using foundational concepts from Data Structures and Algorithms (DSA).

---

## 📌 Objectives

The main goals of this project are:

- 📍 **Calculate Fare** between two metro stations.  
- ➕ **Add/Remove Metro Stations** and connections dynamically.  
- 🔗 **Display Network** as a graph.  
- 🕒 **Shortest Path Calculation** using Dijkstra’s Algorithm.  
- ⚠️ **Detect Articulation Points** (critical congestion nodes).  
- 🔀 **Compute Maximum Flow** using Edmonds-Karp Algorithm.  
- 👤 **Admin/User Login** simulation.  
- 🎟️ **Ticket Types**:  
  - Smart Card (Prepaid)  
  - Student/Senior Citizen Discount  
- 🕰️ **Dynamic Fare Calculation**: Different fares for peak and non-peak hours  

---

## 🧠 Core Algorithms & Their Roles

### 🔹 `findShortestPath()` – Dijkstra’s Algorithm
- **Purpose:** Finds the shortest path (minimum time/distance) between two stations.  
- **Time Complexity:** `O((V + E) log V)`  
- **Why Dijkstra?** Efficient for weighted graphs with non-negative weights — ideal for route planning in metro systems.

---

### 🔹 `dfs()` – Depth-First Search
- **Purpose:** Explores all stations and tracks visited nodes (used in articulation point detection).  
- **Time Complexity:** `O(V + E)`  
- **Use Case:** Helps traverse network branches deeply before backtracking.

---

### 🔹 `isArticulationPoint()` – Cut Vertex Detection
- **Purpose:** Checks if removing a station breaks the connectivity of the network.  
- **Concept:** An articulation point increases the number of disconnected components when removed.  
- **Time Complexity:** `O(2 * (V + E))`

---

### 🔹 `bfs()` – Used in Edmonds-Karp (Ford-Fulkerson)
- **Purpose:** Finds augmenting paths with available capacity from source to sink in the flow network.  
- **Time Complexity:** `O(V + E)`  
- **Use Case:** Prepares augmenting paths for max flow calculation.

---

### 🔹 `edmondsKarp()` – Maximum Flow Algorithm
- **Purpose:** Determines the maximum flow in a metro route network (e.g., peak congestion analysis).  
- **Approach:** Uses BFS repeatedly to push flow in residual graphs.  
- **Time Complexity:** `O(V * E²)`

## 🚀 How to Run

### 📥 1. Download the Code

- Clone the repository using Git:
  ```bash
  git clone https://github.com/your-username/Metro-Management-System-DSA-.git
Or download the ZIP file and extract it.

### 🛠️ Open the Project

- Open the .cpp files in any C++ IDE or compiler:

Visual Studio Code ,
CodeBlocks ,
Dev-C++

### 🏗️ Build and Run

- Compile the code using the Build option in your IDE.

- Run the executable to launch the system.

💡 Ensure that a C++ compiler (like GCC or MinGW) is installed and configured properly.

### ScreenShots

- <img width="802" height="235" alt="image" src="https://github.com/user-attachments/assets/250e350e-da59-471f-a222-9ab6fe1f76f7" />
- <img width="799" height="160" alt="image" src="https://github.com/user-attachments/assets/1b9d1610-c23a-45ac-ad15-14d0487df6af" />
- <img width="796" height="295" alt="image" src="https://github.com/user-attachments/assets/e2fa06fe-6cfc-4900-b0db-6058c54afb07" />
- <img width="809" height="272" alt="image" src="https://github.com/user-attachments/assets/58e0d8e8-c0f9-4326-8293-0912170642b0" />
- <img width="801" height="327" alt="image" src="https://github.com/user-attachments/assets/6791a5aa-641a-409d-a323-57ff37732ff6" />






