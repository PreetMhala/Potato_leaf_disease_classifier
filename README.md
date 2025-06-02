# 🥔 Potato Leaf Disease Classifier  
## *Enhancing crop productivity with fine-tuned deep convolution neural network for Potato leaf disease detection*

A deep learning-based system to classify six major potato leaf diseases using transfer learning (DenseNet201, ResNet152V2, NasNetMobile), strategic data augmentation, and L2 regularization.

📄 **Published in:** *Expert Systems with Applications* (Impact Factor: **7.5**)  
🔗 **DOI:** [10.1016/j.eswa.2024.126066](https://doi.org/10.1016/j.eswa.2024.126066)

---

### 🔍 **Abstract**

Potato plants (*Solanum tuberosum*) are prone to various diseases that result in substantial economic losses for farmers.  
This research presents a **deep learning-based approach** to accurately detect and classify **six distinct diseases** affecting potato leaves:
- Bacteria
- Viruses
- Fungi
- Phytophthora
- Pests
- Nematodes

To address **class imbalance**, we employed:
- 🎨 Strategic Data Augmentation  
- 🔒 L2 Regularization  
- 🧠 Transfer Learning  

Three pre-trained CNNs were fine-tuned on a **diverse real-world dataset of 3,076 leaf images**.  
📂 **Dataset Access:** [https://doi.org/10.17632/ptz377bwb8.1](https://doi.org/10.17632/ptz377bwb8.1)

🚀 **Results:**
- DenseNet201 achieved **77.14%** accuracy on the original dataset.
- With augmentation + k-fold cross-validation, accuracy improved to **81.31%**
  - 📈 4.17% boost over baseline  
  - 🔬 7.68% better than prior work

⚠️ NasNetMobile and ResNet152V2 showed performance degradation due to overfitting and low generalization.

✅ **Conclusion:**  
This approach provides a **scalable, field-deployable** solution for agricultural diagnostics—supporting **sustainable farming** and minimizing crop loss.

---

### 🌟 **Key Contributions**

- ✅ Deep learning framework for classifying six major potato leaf diseases with **improved accuracy, scalability**, and **class balance**.
- 🌀 **Strategic data augmentation** (basic + combinational) simulating real-world image capture conditions.
- 📊 Evaluation using **Precision, Recall, F1-score, Accuracy** for robust performance measurement.
- 🛠️ **Hyperparameter tuning** for optimization in agricultural settings.
- 🔍 Comparative study of **DenseNet201, ResNet152V2, NasNetMobile** across **3 training configurations**.
- 🧱 Applied **L2 regularization** and **early stopping** to reduce overfitting.
- 🌾 Broader disease spectrum than prior works—enhancing **generalizability** across diverse leaf conditions.

---

### 🧠 **Methodology Flowchart**

*(Image to be uploaded in repository)*  
`📌 Placeholder: Methodology_Flowchart.png`
