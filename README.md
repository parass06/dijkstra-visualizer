# 🔍 Shortest Path Spotlight: Dijkstra's Comparison

An interactive web-based visualizer that compares **Dijkstra’s Algorithm**, **A\*** Search, and **Breadth-First Search (BFS)** in finding the shortest path between nodes in a graph.  
Built entirely with **HTML, CSS (Tailwind)**, and **JavaScript**, this app demonstrates how different graph traversal algorithms behave and perform in real time.

---

## 🌐 Live Demo  
👉 [**Click here to try it out**](https://parass06.github.io/dijkstra-visualizer/)  

---

## 📸 Preview  
### Dijkstra’s Algorithm in Action  
<img width="1440" height="799" alt="image" src="https://github.com/user-attachments/assets/ede45784-6e38-4ad8-a35d-a28de2e7f3eb" />


### Path Comparison Results  
<img width="453" height="881" alt="image" src="https://github.com/user-attachments/assets/717a828c-73ad-42b0-9638-4cf82dfb6d21" />



---

## 🧠 Features
- 🧩 Load custom graphs (via JSON adjacency list)
- ⚡ Visualize **Dijkstra**, **BFS**, and **A\*** step-by-step
- 🕹️ Interactive node selection on canvas
- 🎨 Adjustable visualization speed
- 📊 Compare all algorithms instantly with total weight and edge count
- 📱 Responsive design with **Tailwind CSS**
- 🟢 Live path highlighting, edge weights, and node legends

---

## 🧩 Tech Stack
| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, Tailwind CSS, JavaScript (ES6) |
| **Visualization** | HTML5 Canvas |
| **Hosting** | GitHub Pages |

---

## ⚙️ How to Use
1. **Load Graph:** Enter a custom adjacency list JSON in the text area (or use the default one).  
   Example:
   ```json
   {
     "A": {"B": 4, "C": 2, "G": 5},
     "B": {"A": 4, "E": 3},
     "C": {"A": 2, "D": 2, "F": 4}
   }
