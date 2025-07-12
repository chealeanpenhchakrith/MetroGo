# 🚇 MetroGo

**MetroGo** is a modern, interactive web application that helps users compute optimal routes across the Paris metro network.

Built with **Vue.js**, **FastAPI**, and **SQLite**, it combines real-time UI, graph algorithms, and real-world metro data to simulate transit routing, analyze network connectivity, and visualize station relationships.

---

## 🖼️ Preview

![Metro Planner Preview](./MetroGo4.png)
![Metro Planner Preview](./MetroGo3.png)
![Metro Planner Preview](./MetroGo2.png)
![Metro Planner Preview](./MetroGo1.png)

---

## 🚀 Features

- **Shortest Path Computation**  
  Calculate and display the shortest route between two stations using Dijkstra’s algorithm.

- **Minimum Spanning Tree (ACPM)**  
  Visualize the metro network as a tree using Prim or Kruskal algorithms.

- **Network Connectivity Check**  
  Verify whether the entire metro network is connected (i.e., every station can be reached from any other).

- **Real Paris Metro Data Integration**  
  Uses actual 2024 metro data for realistic and accurate path planning.

---

## 🛠 Technologies Used

- ![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
- ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
- ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
- ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

---

## 📦 Getting Started

To run this project locally:

```bash
git clone https://github.com/chealeanpenhchakrith/MetroGo.git
cd Paris-Metro-Route-Planner
cd Back-End
uvicorn main:app --reload
cd ../Front-End
npm install
npm run dev
