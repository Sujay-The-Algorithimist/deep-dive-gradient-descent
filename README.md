🧠 Gradient Descent – From Scratch to 3D Mastery
This notebook is the result of 7+ hours of dedicated coding, math, and visualization. It’s more than just implementation — it’s an educational journey built from the ground up.

🚀 Project Summary
This project explores the Gradient Descent Algorithm in-depth — from basic math to multi-dimensional visualization. It doesn't rely on pre-built libraries for the algorithm, but implements everything from scratch using Python, NumPy, SymPy, and Matplotlib.

This work was inspired by the desire to not just use gradient descent — but to truly understand how it works by building it step-by-step.

📌 Key Highlights
🔢 Started with Simple Cost Functions like:

𝑓
(
𝑥
)
=
𝑥
2
+
𝑥
+
1
f(x)=x 
2
 +x+1
🔁 5 Custom Gradient Descent Implementations:

Includes constant learning rate

Divergence demonstration

Adaptive updates

Manual slope calculations

Tuple-based iterations

⚠️ Explored Edge Cases:

Multiple minima

Overflow and divergence conditions

Effects of bad initial guesses

🔍 Mathematical Derivatives:

Used SymPy to symbolically calculate partial derivatives

Implemented equations manually to understand chain rule and gradient flow

📉 Final Two Functions:

Work with two variables (θ₀ and θ₁)

Uses real-world cost function:

𝑓
(
𝑥
,
𝑦
)
=
∑
(
𝑦
−
𝜃
0
−
𝜃
1
𝑥
)
2
f(x,y)=∑(y−θ 
0
​
 −θ 
1
​
 x) 
2
 
Computes gradients manually

Visualizes the gradient path on both surface and contour plots

📊 Visualizations
🔷 3D Surface of Cost Function
<img src="surface_plot.png" width="600">
🔻 Contour Plot with Gradient Descent Path
<img src="contour_plot.png" width="600">
📁 File Structure
bash
Copy
Edit
📦Gradient-Descent-From-Scratch
 ┣ 📜 03 Gradient Descent.ipynb   ← All code, logic, and math
 ┣ 🖼️ surface_plot.png            ← 3D cost surface
 ┣ 🖼️ contour_plot.png            ← 2D contour with gradient steps
 ┗ 📄 README.md                   ← You're reading it!
🔧 Technologies Used
Python 3

NumPy

Matplotlib (2D & 3D plots)

SymPy (symbolic differentiation)

Scikit-learn (only for validation at the end)

🙌 Why This Matters
If you're learning machine learning and want to:

Understand what actually happens under the hood

Visualize how parameters get updated

Get better at math + code synergy

This notebook will guide you visually and mathematically.

💬 Author Note
This isn’t just a coding exercise — it’s a 7-hour exploration of the math, logic, and beauty behind gradient descent.
Proudly written line by line. 💙
