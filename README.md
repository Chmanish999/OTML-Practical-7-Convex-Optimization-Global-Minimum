# OTML Practical 7: Convex Optimization and Global Minimum

## 1. Aim

The aim of this practical is to understand convex optimization and the concept of a global minimum using cost-function visualization.

In this practical, students visualize a simple convex function and observe why convex optimization is important in machine learning. The practical helps students understand that in convex optimization, every local minimum is also a global minimum.

---

## 2. Course and Module Mapping

**Course:** A8751 – Optimization Techniques in Machine Learning  
**Module:** Module 1 – Model Fitting and Error Measurement  
**Practical Topic:** Convex Optimization and Global Minimum

This practical is mapped with Module 1 of OTML, where students study model fitting, error measurement, cost functions, optimization behaviour, and the role of convexity in machine learning.

---

## 3. Theory Background

Convex optimization refers to optimization problems where the objective function is convex and the feasible region is convex.

A function is called convex if the line segment joining any two points on the curve lies above or on the curve.

In simple terms, a convex function has a bowl-shaped structure. This shape is very useful in optimization because it avoids multiple misleading local minima.

A very simple convex function is:

```text
f(x) = x²
