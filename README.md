# **Enhancing Intrusion Detection Systems with Feature Selection and Hybrid Deep Learning**

## **Overview**
This repository presents a comprehensive study on improving the effectiveness and dependability of Intrusion Detection Systems (IDS) using feature selection techniques combined with a hybrid deep learning model. The study investigates the impact of various feature selection methods and implements a hybrid deep learning architecture that integrates Convolutional Neural Networks (CNN), advanced Recurrent Neural Networks (RNN), and Deep Neural Networks (DNN).  

### **Key Highlights**  
- Analyzed feature selection methods (filter, wrapper, and embedded) on the **NSL-KDD dataset**.  
- Proposed a hybrid deep learning architecture for IDS enhancement.  
- Demonstrated the importance of feature selection in improving model accuracy and robustness.  
- Achieved optimal accuracy of **99.38%** using features selected by **XGBoost**.

---

## **Features**  
- **Comparative Analysis**: Evaluate the effectiveness of filter, wrapper, and embedded feature selection methods.  
- **Hybrid Deep Learning Model**: Combines CNN, RNN, and DNN for robust intrusion detection.  
- **Feature Selection Techniques**: Includes XGBoost, Recursive Feature Elimination (RFE), Mutual Information, and more.  
- **Reproducible Results**: Code and datasets provided to reproduce experimental results.  

---

## **Architecture**

The hybrid deep learning model includes:  
1. **Convolutional Neural Network (CNN)**: For extracting spatial features.  
2. **Recurrent Neural Network (RNN)**: For capturing temporal patterns.  
3. **Fully Connected Deep Neural Network (DNN)**: For classification.  

The selected features from the XGBoost feature selection method were fed into this architecture to achieve high accuracy.  

### **Model Diagram**  
![Model Architecture](images/overall process.png)  
*This diagram illustrates the hybrid deep learning model combining CNN, RNN, and DNN.*

---

## **Dataset**  
We used the **NSL-KDD dataset**, a benchmark dataset for intrusion detection research.  
- Download: [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)  

---

## **Results**  
- Optimal accuracy: **99.38%** using XGBoost-selected features.  
- Demonstrated significant improvement in IDS performance with effective feature selection.  

---

## **Installation**

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/IDS-Feature-Selection-DL.git
   cd IDS-Feature-Selection-DL

