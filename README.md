
# 🚀 **Breadth-First Search Pathfinding Visualizer 
(Python + Pygame)**

A clean, interactive, and visually appealing implementation of the **Breadth-First Search (BFS)** pathfinding algorithm using **Python** and **Pygame**.
Draw obstacles, set your start & end points, and watch the algorithm explore the grid in real time.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pygame](https://img.shields.io/badge/Pygame-Latest-green)
![License](https://img.shields.io/badge/License-MIT-yellow)



---

## 🌟 **Preview**

![Preview](preview.png)

---

## 🔥 **Features**

* 🧭 Visual BFS algorithm (queue-based exploration)
* 🎮 Fully interactive grid
* 🧱 Draw walls with mouse
* 🎯 Set start & target positions
* 🎨 Smooth animations + color-coded states
* 📐 Accurate shortest-path reconstruction
* 🪟 Clean UI with instructions displayed inside the app

---

## 🧠 **How It Works (Algorithm Overview)**

BFS explores the grid **level by level**, using a **queue**, guaranteeing the **shortest path** in an unweighted grid.

### Pathfinding Flow:

1. Select a **start point**
2. Add it to the BFS queue
3. Visit neighbors (up/down/left/right)
4. Stop when the target is found
5. Backtrack using `prior` pointers to reconstruct the shortest path
6. Display the solution visually

### Color Legend:

| Color     | Meaning                  |
| --------- | ------------------------ |
| 🟦 Blue   | Final shortest path      |
| 🟥 Red    | In queue (to be visited) |
| 🟩 Green  | Visited node             |
| 🟨 Yellow | Target node              |
| 🟧 Cyan   | Start node               |
| ⬛ Black   | Wall / Obstacle          |
| ⬜ Grey    | Unvisited open cell      |

---

## 🛠️ **Tech Stack**

* **Python 3.x**
* **Pygame** for rendering
* **Tkinter** for “No Solution” popup
* **BFS Graph Algorithm**

---

## 📦 **Installation**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/KrVikashGupta/bfs-pathfinding-visualizer.git
cd breadth-first-search

```

### 2️⃣ Create & Activate Virtual Environment

```bash
python -m venv venv
```

#### Windows:

```bash
venv\Scripts\activate
```

#### Mac/Linux:

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
python pathfinding.py
```

---

## 🎮 **Controls**

| Action        | Input           |
| ------------- | --------------- |
| 🟧 Set Start  | Left-click once |
| ⬛ Draw Walls  | Hold left-click |
| 🟨 Set Target | Right-click     |
| ▶️ Run BFS    | Press **SPACE** |

---

## 📚 **Project Structure**

```
📦 BFS-Pathfinder
├── pathfinding.py        # Main logic + rendering
├── requirements.txt      # Required libraries
├── preview.png           # Demo screenshot
└── README.md             # Documentation
```

---

## 🧩 **Key Concepts Visualized**

* **Grid-Based Graph Traversal**
* **Queue (FIFO) Mechanics**
* **Parent Tracking for Path Reconstruction**
* **Obstacle Handling**
* **Real-time Visualization**

---

## 🤝 **Contributing**

Contributions are welcome! Feel free to fork the repository, open issues, and submit pull requests.

---

## 🪪 License

This project is licensed under the **MIT License**.

---

## 📫 Contact

**Vikash Kumar Gupta**  
📍 Bokaro Steel City, Jharkhand  
✉️ [vikashkumargupta907@gmail.com](mailto:vikashkumargupta907@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/vikash1995) | [GitHub](https://github.com/KrVikashGupta)

---

⭐ If you find this project useful, please consider giving it a star to support the work!
