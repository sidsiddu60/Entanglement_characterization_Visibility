# 🌟 Quantum Entanglement Characterization using Visibility Analysis 🚀

## 📚 **Overview**  
This repository provides a framework to **characterize quantum entanglement** using **visibility analysis** from measurement results across two bases:  
- **Computational Basis:** HH, HV, VH, VV  
- **Diagonal Basis:** DD, DA, AD, AA  

The entanglement generated in this study corresponds to the **Bell State:**  
\[
|\Psi\rangle = |HH\rangle + |VV\rangle
\]

In this entangled state:  
- The **visibility results will be maximum** for **HH and VV** states in the **computational basis**.  
- Similarly, visibility will peak for **DD and AA** states in the **diagonal basis**.

---

## 📊 **Dummy Data Disclaimer**  
The data provided in this repository is **dummy/example data** designed to demonstrate how the code functions.  

### 🛠️ **Using Your Own Data**  
1. Replace the `.txt` files in the `data/` folder with your **real experimental data**.  
2. Ensure your files follow the **same naming conventions**:
   - `HH.txt` → HH
   - `HV.txt` → HV
   - `VV.txt` → VV
   - `VH.txt` → VH  
   - (and so on for DD, DA, AA, AD)  

The analysis code will automatically process your data and generate results.

---

## 🔬 **Theoretical Background: Visibility and Entanglement Characterization**

### 🧠 **What is Visibility?**  
**Visibility** measures the contrast of interference fringes observed in quantum systems. It is mathematically expressed as:

\[
V = \frac{I_{\text{max}} - I_{\text{min}}}{I_{\text{max}} + I_{\text{min}}}
\]

Where:  
- \( I_{\text{max}} \): Maximum intensity observed in the interference pattern.  
- \( I_{\text{min}} \): Minimum intensity observed.

A **high visibility** value indicates:
- **Strong quantum coherence** between entangled particles.  
- Minimal decoherence or noise in the system.

---

### 🧠 **Why Visibility for Entanglement Characterization?**  
1. **Indicator of Quantum Coherence:**  
   - Visibility directly reflects the coherence properties of the quantum state.  

2. **Entangled States and Bell Inequalities:**  
   - Entangled states like the **Bell state (HH + VV)** produce distinct visibility patterns in both **computational** and **diagonal bases**.

3. **Practical Measure:**  
   - Visibility offers an experimentally accessible parameter to **quantify the "quality" of entanglement**.  

4. **Threshold for Entanglement:**  
   - For visibility greater than a certain threshold (typically \( V > 0.7 \)), the state can be considered entangled.

---

## 🛠️ **How to Use This Repository**

1. Clone the repository:
    ```bash
    git clone https://github.com/sidsiddu60/Entanglement_characterization_Visibility.git
    cd Entanglement_characterization_Visibility
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Place your data files in the `data/` folder.

4. Open the Jupyter notebook:
    ```bash
    jupyter notebook notebooks/visibility_analysis.ipynb
    ```

5. Run the analysis and check results in the `results/` folder.

---

## 📂 **Repository Structure**


