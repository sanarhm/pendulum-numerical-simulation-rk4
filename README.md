# Numerical Simulation of a Non-Linear Pendulum using Runge-Kutta (RK4) Method

This repository contains a high-precision Python implementation for simulating the chaotic/dynamical behavior of a non-linear pendulum. The project bridges theoretical principles of analytical mechanics with modern computational physics tools.

## 🎓 Academic Context
- **Institution:** Imam Khomeini International University (IKIU), Qazvin, Iran
- **Department:** Department of Physics (Engineering Physics Program)
- **Project Type:** Part of B.Sc. Capstone Project / Advanced Coursework
- **Supervisor:** Dr. Soltansaraei

## 🔬 Physics & Numerical Method
The motion of a simple pendulum without damping is governed by the second-order non-linear differential equation:
$$\frac{d^2\theta}{dt^2} + \frac{g}{L}\sin(\theta) = 0$$

To solve this numerically, the equation is decomposed into a system of two first-order Ordinary Differential Equations (ODEs). We implement the **4th-order Runge-Kutta (RK4)** integration technique, which offers a robust balance between computational efficiency and local truncation error ($O(\Delta t^5)$).

## 🛠️ Tech Stack & Dependencies
- **Language:** Python 3.x
- **Libraries:** - `NumPy` (for vectorization and numerical arrays)
  - `Matplotlib` (for dynamic visualization and animation rendering)
  - `Pillow` (for exporting time-series frames into high-quality GIFs)

## 📊 Dynamic Visualization
Below is the real-time, physically accurate animation of the pendulum's angular displacement generated dynamically using the `matplotlib.animation` module:

<p align="center">
  <img width="600" height="600" alt="pendulum_simulation" src="https://github.com/user-attachments/assets/49e71520-eda9-40d4-95ef-36fcba17b39f" />
</p>

## 🚀 How to Run the Simulation
1. Clone the repository:
   ```bash
   git clone [https://github.com/sanarhm/pendulum-numerical-simulation-rk4.git](https://github.com/sanarhm/pendulum-numerical-simulation-rk4.git)
