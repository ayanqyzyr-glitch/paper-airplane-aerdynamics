# Aerodynamic Analysis and Modeling of Micro-Gliders (NACA 2412)

## 📌 Project Overview
This project focuses on transitioning traditional paper airplane testing into a formal computational engineering workflow. Using **XFLR5 / XFoil**, I simulated and evaluated the aerodynamic performance of the **NACA 2412** cambered airfoil at low Reynolds numbers ($Re = 30,000$ to $1,000,000$).

---

## 🛠 Tools & Methoology
* **Software:** XFLR5 (XFoil-based panel method)
* **Airfoil Profile:** NACA 2412
* **Analysis Type:** Multi-threaded Batch Analysis ($T1$ Polar Analysis across multiple $Re$ values)
* **Key Metrics:** Lift Coefficient ($C_L$), Drag Coefficient ($C_D$), Lift-to-Drag Ratio ($L/D$)

---

## 📊 Results and Simulation Data

### 1. Airfoil Geometry
![NACA 2412 Airfoil Profile](https://github.com/ayanqyzyr-glitch/paper-airplane-aerdynamics/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(9).png)

### 2. Aerodynamic Performance Graphs
![Aerodynamic Performance Graphs](https://github.com/ayanqyzyr-glitch/paper-airplane-aerdynamics/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(7).png)

---

## 💡 Key Engineering Takeaways
1. **Low Speed Performance:** The $2\%$ camber in NACA 2412 generates significant lift even at ultra-low speeds suitable for lightweight paper gliders.
2. **Stall Behavior:** Smooth polar curves confirm predictable gliding characteristics before reaching critical angles of attack.

---

## 🚀 Future Scope
* Comparative analysis with symmetrical profiles (NACA 0012) and flat-plate geometries.
* Physical flight tests using a elastic launch platform (catapult) to correlate CFD simulations with real-world distance data.
*
