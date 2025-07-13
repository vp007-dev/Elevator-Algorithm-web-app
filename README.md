
---

# 🚀 Elevator Simulation Web App

A **dynamic elevator simulation web application** that visually demonstrates how an elevator processes floor requests efficiently, using realistic animation and scheduling logic.

---

## ✨ Features

* **Interactive user interface** with:

  * Elevator visual moving up and down floors.
  * Buttons to request specific floors at any time.
* **Dynamic request handling**:

  * Users can add new requests **mid-journey**.
  * Elevator intelligently decides the optimal path based on current direction.
* **Smooth animations** to depict elevator movement.
* **Responsive design** for desktop and mobile views.

---

## 💻 Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling and layout
* **JavaScript (ES6)** – Elevator logic, event handling, and animations

---

## 🔧 How It Works

1. **User clicks** on floor buttons to make requests.
2. The elevator maintains:

   * `currentFloor` – elevator's current floor.
   * `direction` – moving "up" or "down".
   * `requests` – queue of pending floor requests.
3. Processes requests in the current direction:

   * Moves to **requested floors only**, avoiding unnecessary stops.
   * Reverses direction if no further requests exist in the current direction.
4. New floor requests can be added **while the elevator is moving**, and they will be integrated into the optimal path dynamically.

---

## 🚀 Getting Started

### 🔨 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/elevator-simulation-webapp.git
cd elevator-simulation-webapp
```

2. **Open `index.html`** in your browser:

```bash
start index.html
```

or

Simply **deploy it using GitHub Pages**, Netlify, or Vercel for live simulation.

---

## 📝 Usage

* Click any **floor button** to request the elevator to stop at that floor.
* Observe the elevator moving with smooth CSS transitions.
* Try adding multiple requests mid-journey to see **dynamic scheduling** in action.

---

## 📂 Project Structure

```
elevator-simulation-webapp/
├── index.html
└── README.md
```

---

## 🧠 Concepts Demonstrated

* **Event-driven programming**
* **Queue and scheduling algorithms**
* **DOM manipulation**
* **CSS animations & transitions**
* Real-world simulation logic adapted to web apps

---

## 🚧 Future Enhancements

* Multiple elevators with optimal car assignment (like real building systems).
* Sound and door animations for realism.
* Backend integration with **Java Spring Boot or Node.js** for smart building systems.
* User authentication for personalized requests in co-working or apartment setups.

---

## 📜 License

This project is licensed under **MIT License** and is open for educational, demonstration, and portfolio use.

---

## 👨‍💻 Author

**Vansh Pandey**
*BTech CSE | AI-ML | Space & Research Enthusiast*

> **“Making algorithms come alive visually helps understand their beauty and practicality.”**

---

## 🌐 Demo

➡️ [Live Demo Link](https://vp007-dev.github.io/Elevator-Algorithm-web-app/)

---

