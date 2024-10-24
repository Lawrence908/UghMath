# Integral Techniques: Step-by-Step Guide

This document outlines the steps to solve various types of integrals. Follow these steps as you practice and complete your homework to improve your understanding of integral calculus.

## 1. **Definite Integrals: The Basics**

### Steps:
1. **Identify the integral bounds**: Check the limits of integration.
2. **Find the antiderivative**: Use basic rules of integration (power rule, constant rule, etc.) to find the antiderivative.
3. **Evaluate at the upper bound**: Substitute the upper bound into the antiderivative.
4. **Evaluate at the lower bound**: Substitute the lower bound into the antiderivative.
5. **Subtract**: Subtract the lower bound evaluation from the upper bound evaluation.

### Example:
\[
\int_0^1 x^2 \, dx = \left[ \frac{x^3}{3} \right]_0^1 = \frac{1}{3} - 0 = \frac{1}{3}
\]

---

## 2. **Definite Integrals via Riemann Sums**

### Steps:
1. **Set up the partition**: Divide the interval \([a, b]\) into \(n\) subintervals.
2. **Choose sample points**: Use left, right, or midpoint for evaluation.
3. **Evaluate the function at each point**: Plug the sample points into the function.
4. **Sum the areas**: Multiply each function evaluation by the width of the subinterval \(\Delta x = \frac{b - a}{n}\).
5. **Take the limit**: As \(n\) approaches infinity, the Riemann sum approximates the integral.

### Example:
For \(\int_0^1 x^2 \, dx\), use the midpoint Riemann sum and calculate the area under the curve.

---

## 3. **The Evaluation Theorem**

### Steps:
1. **Find the antiderivative**: Compute the indefinite integral of the function.
2. **Evaluate the definite integral**: Apply the Fundamental Theorem of Calculus by evaluating the antiderivative at the upper and lower bounds, and subtracting.

### Example:
\[
\int_0^2 (2x) \, dx = \left[ x^2 \right]_0^2 = 4 - 0 = 4
\]

---

## 4. **Net and Total Change as Integrals**

### Steps:
1. **Set up the integral**: Identify the rate of change function and the limits.
2. **Interpret the integral**: Recognize that the definite integral represents the net or total change over the interval.
3. **Evaluate the integral**: Compute the definite integral.

### Example:
To compute total distance, use the integral of velocity over time.

---

## 5. **Fundamental Theorem of Calculus**

### Steps:
1. **Apply Part 1**: The derivative of the integral of a function returns the original function: 
   \[
   \frac{d}{dx} \left( \int_a^x f(t) \, dt \right) = f(x)
   \]
2. **Apply Part 2**: The definite integral of a function is the difference of the antiderivative evaluated at the bounds: 
   \[
   \int_a^b f(x) \, dx = F(b) - F(a)
   \]

---

## 6. **The Substitution Rule**

### Steps:
1. **Choose a substitution**: Identify an expression inside the integral to substitute (e.g., let \( u = g(x) \)).
2. **Find \( du \)**: Differentiate \( u \) to find \( du \).
3. **Substitute into the integral**: Replace all \( x \)-terms with \( u \)-terms.
4. **Integrate with respect to \( u \)**.
5. **Back-substitute \( u = g(x) \)**: Return to the original variable.
6. **Evaluate**: If it’s a definite integral, adjust the limits for \( u \).

### Example:
\[
\int 2x \sqrt{1 + x^2} \, dx
\]
Substitute \( u = 1 + x^2 \), then \( du = 2x \, dx \).

---

## 7. **Integration by Parts (IBP)**

### Steps:
1. **Identify \( u \) and \( dv \)**: Choose parts of the function for \( u \) and \( dv \) using the LIATE rule (Logarithmic, Inverse, Algebraic, Trigonometric, Exponential).
2. **Differentiate \( u \)**: Find \( du \).
3. **Integrate \( dv \)**: Find \( v \).
4. **Apply the formula**: Use the integration by parts formula:
   \[
   \int u \, dv = uv - \int v \, du
   \]
5. **Simplify and solve**: Continue solving the remaining integral.

### Example:
\[
\int x e^x \, dx
\]
Let \( u = x \), \( dv = e^x \, dx \).

---

## 8. **Trigonometric Substitution Method**

### Steps:
1. **Recognize a trigonometric form**: Identify the form \(\sqrt{a^2 - x^2}\), \(\sqrt{x^2 - a^2}\), or \(\sqrt{x^2 + a^2}\).
2. **Make the substitution**: Substitute using trigonometric identities (e.g., \( x = a \sin(\theta) \)).
3. **Simplify the integral**: Use trigonometric identities to simplify the integral.
4. **Integrate**: Solve the integral.
5. **Back-substitute**: Return to the original variable.

### Example:
\[
\int \sqrt{1 - x^2} \, dx
\]
Substitute \( x = \sin(\theta) \).

---

## 9. **Partial Fraction Decomposition (PFD)**

### Steps:
1. **Decompose the fraction**: Break down the rational function into simpler fractions.
2. **Solve for constants**: Use algebra to find the constants for each fraction.
3. **Integrate each fraction**: Integrate the simpler fractions.
4. **Sum the results**.

### Example:
\[
\int \frac{1}{x(x+1)} \, dx
\]
Decompose into partial fractions.

---

## 10. **Approximate Integration**

### Steps:
1. **Choose an approximation method**: Select the trapezoidal rule or Simpson’s rule.
2. **Set up the partition**: Divide the interval \([a, b]\) into subintervals.
3. **Apply the rule**: Use the chosen rule to approximate the integral.

---

## 11. **Improper Integrals**

### Steps:
1. **Identify the improper behavior**: Determine if the integral has an infinite limit or a discontinuity.
2. **Set up the limit**: Replace the improper part with a limit.
3. **Evaluate the limit**: Compute the integral and evaluate the limit as it approaches infinity or the discontinuity.

---

## 12. **Areas Between Curves**

### Steps:
1. **Identify the curves**: Determine the functions for the upper and lower curves.
2. **Set up the integral**: Integrate the difference \( f(x) - g(x) \) over the interval.
3. **Evaluate the definite integral**.

---

## 13. **Volumes of Solids of Revolution**

### Steps:
1. **Set up the integral**: Use the disk, washer, or shell method depending on the solid.
2. **Integrate**: Find the volume by integrating the cross-sectional area.
3. **Evaluate the bounds**: For definite integrals, evaluate the bounds.
