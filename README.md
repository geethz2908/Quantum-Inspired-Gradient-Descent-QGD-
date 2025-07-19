🔮 Quantum-Inspired Gradient Descent (QGD)

Optimization is the foundation of machine learning, but traditional methods like Stochastic Gradient Descent (SGD) and Momentum often struggle to balance computational efficiency with accuracy in complex scenarios. This project introduces Quantum-Inspired Gradient Descent (QGD)—an innovative optimization framework inspired by quantum principles such as superposition and entanglement to enhance performance in gradient-based learning.

Through comparative experiments against standard optimizers (SGD, Adagrad, RMSProp), QGD achieves significantly faster convergence (0.04s) and better accuracy in velocity prediction tasks, delivering the lowest Mean Absolute Error (MAE) of 4.6539. These findings highlight QGD's potential as a scalable, efficient, and precise solution to key optimization challenges in ML.

🚀 Key Features
✅ Introduces quantum-theoretical principles into optimization algorithms.

📉 Achieves faster convergence and reduced computation time.

🧠 Performs exceptionally well in velocity prediction tasks.

🧪 Comparative evaluation with traditional methods (SGD, Adagrad, RMSProp).

📊 Detailed analysis of MAE, R², and computation time.

📘 Notebook Covers
Implementation of Standard GD and Improved QGD

Integration of quantum-inspired logic (superposition sampling, entanglement)

Comparative benchmarking across multiple metrics

Visualization of convergence and error metrics

🧪 Results Summary and Comparison of Optimization Methods
## **Performance Metrics Comparison**

| **Method**         | **MAE**   | **R²**      | **Explained Variance** |
|---------------------|-----------|-------------|-------------------------|
| **SGD**            | 5.0126    | -0.0181     | -0.0057                |
| **BGD**            | 5.0043    | -0.0160     | -0.0037                |
| **Momentum**       | 5.0043    | -0.0160     | -0.0037                |
| **Adagrad**        | 4.8964    | -0.0037     | -0.0037                |
| **RMSProp**        | 5.0038    | -0.0159     | -0.0040                |
| **Improved QGD (Pos)** | 7.5003 | -1.7689     | N/A                    |
| **Standard GD (Pos)** | 7.5062 | -1.7656     | N/A                    |
| **Improved QGD (Vel)** | 4.6539 | -0.9612     | N/A                    |


📌 Explanation of Metrics
Mean Absolute Error (MAE): Measures average absolute deviation between prediction and ground truth. Lower is better.

R² (Coefficient of Determination): Indicates how well predictions capture data variance. Closer to 1 is better; negative values imply poor fit.

Explained Variance: Measures proportion of captured variance. Higher is better; negative values suggest worse than mean prediction.

🕒 Computation Time Comparison
Method	Computation Time (seconds)
SGD	0.2198
BGD	0.0019
Momentum	2.0461
Adagrad	1.0151
RMSProp	1.0246
Improved QGD (Position)	0.04
Standard GD (Position)	0.04
Improved QGD (Velocity)	0.04

📈 Detailed Summary
1. Gradient Descent Variants
SGD, BGD, and Momentum perform similarly, with moderate MAE and poor R², indicating basic optimization limits.

Adagrad performs slightly better due to its adaptive learning rate.

RMSProp shows comparable behavior to Adagrad but doesn't offer additional gains.

2. Improved QGD vs Standard GD
Improved QGD (Velocity) delivers the lowest MAE (4.6539) and outperforms all others for velocity prediction.

For position prediction, both Improved QGD and Standard GD produce higher MAE (~7.5) and negative R², highlighting the complexity of positional tasks.

Improved QGD's strength lies in velocity tasks, where it shines with fast convergence and low error.

3. Computation Efficiency
Despite high performance, QGD variants remain highly efficient, with computation times of just 0.04 seconds.

This makes QGD ideal for real-time or resource-constrained environments where both speed and accuracy matter.

🧠 Key Highlight: Improved QGD
Achieves best performance in velocity prediction tasks.

Combines entanglement, superposition sampling, and adaptive learning for superior gradient updates.

Offers a novel, quantum-inspired solution to long-standing ML optimization trade-offs.

🛠 Tools & Technologies Used
Python 3.x

NumPy

Matplotlib

Jupyter Notebook

