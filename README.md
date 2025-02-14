# **IR-Spectroscopy-Py-Reader** 🔬  

A **Python-based infrared (IR) spectroscopy spectrum reader** that processes spectral data from **4000 cm⁻¹ to 400 cm⁻¹**. This tool helps identify IR peaks by calibrating wave numbers and detecting functional groups from an IR spectrum image.  

---

## 🚧 **Current Development Status** 🚧  
This project is still under modification! It works, but it’s not perfect yet.  

### ⚠️ **Missing Features:**  
❌ **Peak strength detection** – The script doesn’t yet classify peaks as **strong, medium, or weak**.  
❌ **Full functional group identification** – Right now, at **3300 cm⁻¹**, for example, it might suggest **either** an alcohol **or** an alkyne stretch, but not both at the same time.  

### 🔄 **What’s Coming Next?**  
**Peak intensity detection** – Peaks will soon be categorized by strength.  
**Expanded functional group database** – The program will identify **all** possible functional groups for each peak instead of just one.  

---

## 📖 **How to Use**  

### 1️⃣ **Setup**  
1. Download the folder.  
2. **Delete the provided spectrum example** and replace it with your own spectrum image.  
3. Make sure your file is named **exactly** as `spectrum.jpg`.  

### 2️⃣ **Running the Script**  
1. Launch the script.  
2. Define key **wave numbers** by clicking on the image:  
   - **4000 cm⁻¹, 3000 cm⁻¹, 2000 cm⁻¹, 1500 cm⁻¹, 1000 cm⁻¹, 600 cm⁻¹**.  
3. The program will use these points to **calibrate distances** and improve peak detection accuracy.  

### 3️⃣ **Peak Identification**  
- Click on peaks to analyze them.  
- The script will return the **functional group** based on the wavenumber.  

### 4️⃣ **Exit**  
To exit the program, press **Ctrl + C**.  

---

## 📜 **License - GNU AGPL-3.0**  

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.  
- You are **free to use, modify, and share** the software.  
- If you modify and deploy it as a service, **you must release your modifications** under the same AGPL-3.0 license.  
- See the **[LICENSE](LICENSE)** file for full details.  

This ensures the project stays **open-source and accessible** to everyone.  

---
  
