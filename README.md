# 🚖 Riding Tracker (Ride Dispatch System)

---

## 📌 Overview  
A **simulation-based riding tracker** that matches riders with the nearest available drivers.  
Built with **Flask** (for web simulation) and **Python classes** (for drivers, riders, and dispatching logic).  
Implements **object-oriented design, nearest driver selection, random location generation**, and a simple dispatch algorithm.  

---

## 🛠️ Features  
- Create multiple **drivers** with random starting locations  
- Generate riders with **origin and destination points**  
- Automatically assign the **nearest available driver**  
- Handle cases when **no drivers are available**  
- Update driver status & location after each ride  
- Web-based simulation using **Flask**  

---

## 📂 Data Structures & Concepts Used  
- **Classes & Objects** → `Driver`, `Rider`, `DispatchSystem` encapsulate ride logic  
- **Arrays (Lists)** → Store collections of drivers and riders  
- **Searching** → Find available drivers using list comprehension  
- **Filtering** → Select only available drivers  
- **Sorting / Optimization** → Select nearest driver using `min()` with custom distance function  
- **Mathematics** → Euclidean distance calculation with `math.hypot`  
- **Flask** → Render ride assignment results via a web route  
