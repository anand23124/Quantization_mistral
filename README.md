# Quantizing Mistral Models to 4-bit Precision  

This project focuses on quantizing **Mistral models** (7B and 8B parameters) into **4-bit precision**, enabling more efficient deployment without compromising accuracy. The quantization was performed using Google Colab, but steps and configurations for local deployment are also outlined.  

---

## 📌 **Features**  
- Quantized **Mistral 7B and 8B** parameter models.  
- Achieved a **4-bit representation** to optimize memory and computation.  
- Supports both **Colab-based and local deployment**.  
- Reduced **resource requirements** for effective deployment.  

---

## 💻 **Local Deployment Requirements**  

For quantizing the **Mistral 7B/8B model** locally:  
- **GPU:** At least 6 GB VRAM (8 GB recommended).  
- **RAM:** 16 GB System Memory.  
- **Storage:** 15 GB SSD for models and dependencies.  
- **Cloud Instances:**  
  - AWS g4dn.xlarge  
  - Equivalent Azure and GCP configurations.  

---

## 🚀 **How to Run**  

### **In Google Colab**  
1. Open the Colab notebook (link provided below).  
2. Upload the Mistral model files.  
3. Follow the quantization steps provided in the notebook.  
