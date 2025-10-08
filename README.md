# BPNN-Fe: Predicting Properties of BCC Iron with Neural Network Potentials

**Machine Learning for Materials: Behler–Parrinello Neural Network (BPNN) applied to BCC Iron**

---

## **Project Overview**

This project implements a **Behler–Parrinello Neural Network (BPNN)** to predict multiple physical properties of **body-centered cubic (BCC) iron** directly from atomic structures.  
Instead of relying solely on computationally expensive DFT simulations, this approach uses **atom-centered symmetry function descriptors** to train a neural network for **fast, accurate property prediction**.

**Targeted Properties:**

- Thermal Conductivity (W/m·K)  
- Electrical Resistivity (µΩ·cm)  
- Magnetic Moment (µB/atom)  

---

## **Key Features**

- **Atomic Descriptor Generation:** Calculates simple radial symmetry functions inspired by ACSFs for each atom.  
- **Multi-Output Neural Network:** Predicts thermal, electrical, and magnetic properties simultaneously.  
- **Temperature and Lattice Constant Analysis:** Evaluate property trends across small variations in lattice constants and temperatures.  
- **Visualization:** Clear plots for property variations with lattice constant and temperature.  


