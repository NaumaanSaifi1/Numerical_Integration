<h1 align="center" style="font-size:2.8em; color:#e67e22;">🔢 Numerical Integration Methods in C</h1>
<p align="center">
  <img src="https://img.shields.io/badge/language-C-blue.svg" />
  <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg" />
</p>

<p align="center" style="font-size:1.2em; color:#555;">
  Efficient and accurate C implementations of widely-used numerical integration techniques, designed for engineers, mathematicians, and students.
</p>

<hr style="border:1px solid #ccc;"/>

<h2 style="color:#2c3e50;">📘 What is Numerical Integration?</h2>

<p style="font-size:1em; color:#333;">
  Numerical integration is a fundamental tool in computational mathematics used to estimate the definite integral of functions where analytical integration is difficult or impossible. It's essential in physics simulations, engineering analysis, and real-time systems where accuracy and speed are critical.
</p>

<h2 style="color:#2c3e50;">🧮 Implemented Methods</h2>

<ul style="font-size: 1em; line-height: 1.6;">
  <li>Trapezoidal Rule</li>
  <li>Simpson's 1/3 Rule</li>
  <li>Simpson's 3/8 Rule</li>
  <li>Gauss-Legendre Quadrature</li>
  <li>Romberg Integration</li>
</ul>

<h2 style="color:#2c3e50;">📊 Method Comparison</h2>

<table align="center" style="border-collapse: collapse; width: 100%;">
  <tr style="background-color:#f4f4f4;">
    <th style="padding: 8px; border: 1px solid #ddd;">Method</th>
    <th style="padding: 8px; border: 1px solid #ddd;">Accuracy</th>
    <th style="padding: 8px; border: 1px solid #ddd;">Speed</th>
    <th style="padding: 8px; border: 1px solid #ddd;">Best Use Case</th>
  </tr>
  <tr>
    <td style="padding: 8px; border: 1px solid #ddd;">Trapezoidal Rule</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Low–Moderate</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Fast</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Rough approximations</td>
  </tr>
  <tr>
    <td style="padding: 8px; border: 1px solid #ddd;">Simpson’s 1/3 Rule</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Moderate–High</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Fast</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Smooth functions</td>
  </tr>
  <tr>
    <td style="padding: 8px; border: 1px solid #ddd;">Simpson’s 3/8 Rule</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Moderate–High</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Moderate</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Odd intervals, polynomials</td>
  </tr>
  <tr>
    <td style="padding: 8px; border: 1px solid #ddd;">Gauss-Legendre</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Very High</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Fast</td>
    <td style="padding: 8px; border: 1px solid #ddd;">High-precision needs</td>
  </tr>
  <tr>
    <td style="padding: 8px; border: 1px solid #ddd;">Romberg Integration</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Very High</td>
    <td style="padding: 8px; border: 1px solid #ddd;">Slower</td>
    <td style="padding: 8px; border: 1px solid #ddd;">When extreme accuracy is required</td>
  </tr>
</table>

<h2 style="color:#2c3e50;">⚙️ Clone the Repository</h2>

<pre style="background-color:#f8f8f8; padding:10px; border-radius:6px;">
git clone https://github.com/NaumaanSaifi1/Numerical_Integration.git
cd Numerical_Integration

# Compile and run any method
gcc simpson13.c -o simpson13
./simpson13
</pre>

<h2 style="color:#2c3e50;">📂 Folder Structure</h2>

<pre style="background-color:#f8f8f8; padding:10px; border-radius:6px;">
Numerical_Integration/
├── trapezoidal.c
├── simpson13.c
├── simpson38.c
├── gauss_legendre.c
├── romberg.c
└── README.md
</pre>

<h2 style="color:#2c3e50;">📩 Contact</h2>

<p style="font-size: 1em;">
  📧 <strong>Email:</strong> naumaansaifi7@gmail.com
</p>

<hr style="border: 1px solid #ccc;"/>

<p align="center" style="color: gray;">
  Made by using C, for accurate and efficient numerical analysis.
</p>
