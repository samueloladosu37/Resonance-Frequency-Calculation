# Resonance-Frequency-Calculator
A user-friendly Python code that can compute the resonance frequency of a Piezoelectric Transducer. 
Piezoelectric Micromachined Ultrasonic Transducers (PMUTs) are widely used in medical imaging, non-destructive testing, and wearable sensors due to their ability to generate and receive ultrasonic waves. The resonance frequency of a PMUT determines its operational efficiency and is influenced by various parameters such as:  

- **Membrane material properties** (density, Young’s modulus, Poisson’s ratio)  
- **Membrane dimensions** (thickness, radius)  
- **Piezoelectric layer properties**  
- **Residual stress and boundary conditions**  

I used COMSOL Multphysics in m Master's thesis to design circular PMUTs and to estimate the opertional frequency. The results are similar to the results from this calculator. Note that the experimental results may vary sligthly from this calculator because of fabrication and measurements defects.
 
**Challenges:**  
1. **Complexity of Analytical Calculations** – The resonance frequency depends on multiple physical and material properties, making manual calculations time-consuming and error-prone.  
2. **Lack of User-Friendly Tools** – Existing solutions often require advanced simulation software (COMSOL, ANSYS), which are expensive and complex. 
3. **Need for Quick Prototyping** – Engineers and researchers need a fast and accurate way to estimate PMUT resonance frequency during the design phase.  

---

### **Proposed Solution**  
To address these challenges, I developed a **user-friendly Python code** that can compute the resonance frequency of a PMUT based your design and material parameters. 
This solution will significantly reduce the time required for **PMUT design optimization** and enable researchers to make **data-driven decisions efficiently**. 
