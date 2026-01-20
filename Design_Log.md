# Design Log

## Redesign Objectives 
- Redesign the Impeller of an existing centrifugal pump impeller to be more efficient
- Increase Flow rate without increasing energy input

---

## Laws of Physics Applied

### 1. Conservation of Mass
The flow rate through the impeller is constant along a streamline:

$$
Q = A \cdot V
$$

Where:  
- **Q** = Flow Rate (m³/s)  
- **A** = Cross-Sectional Area of the flow (m²)  
- **V** = Fluid Velocity (m/s)  

---

### 2. Conservation of Momentum
The force applied by the impeller to the fluid is given by:

$$
F = \dot{m} \cdot \Delta V
$$

Where:  
- **F** = Force exerted on the fluid (N)  
- **\(\dot{m}\)** = Mass Flow Rate of the fluid (kg/s)  
- **ΔV** = Change in fluid velocity across the impeller (m/s)  

---

### 3. Bernoulli's Principle
The total energy along a streamline is constant:

$$
P + \frac{1}{2} \rho V^2 + \rho g h = \text{constant}
$$

Where:  
- **P** = Pressure at a point in the fluid (Pa)  
- **ρ** = Fluid density (kg/m³)  
- **V** = Fluid velocity at that point (m/s)  
- **g** = Gravitational acceleration (9.81 m/s²)  
- **h** = Height relative to a reference point (m)  

**Application to Wave-Shaped Blade:**  
- The sinusoidal curvature of the blade gradually accelerates the fluid, reducing sudden pressure drops.  
- Smooth acceleration minimizes cavitation risk at the hub and leading edges.  
- Balances kinetic and pressure energy, improving overall pump efficiency.

---
