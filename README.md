🥔 Potato Leaf Disease Classifier :- Enhancing crop productivity with fined-tuned deep convolution neural network for Potato leaf disease detection

Deep learning-based classification of six potato leaf diseases using transfer learning (DenseNet201, ResNet152V2, NasNetMobile), data augmentation, and regularization.
📄 Published in: Expert Systems with Applications (Impact Factor: 7.5)
🔗 DOI: 10.1016/j.eswa.2024.126066

🔍 Abstract
Potato plants (Solanum tuberosum) are prone to various diseases that result in substantial economic losses for farmers. This research presents a deep learning-based approach to accurately detect and classify six distinct diseases affecting potato leaves: bacteria, viruses, fungi, phytophthora, pests, and nematodes.

To address class imbalance, we employed strategic data augmentation, L2 regularization, and transfer learning. Three pre-trained CNNs—DenseNet201, ResNet152V2, and NasNetMobile—were fine-tuned on a diverse real-world dataset of 3,076 leaf images.
📂 Access the dataset here: https://doi.org/10.17632/ptz377bwb8.1

DenseNet201 achieved the highest accuracy of 77.14% on the original dataset.

With data augmentation and k-fold cross-validation, it reached 81.31%—a 4.17% improvement over baseline and 7.68% better than prior work.

NasNetMobile and ResNet152V2 showed performance degradation due to overfitting and poor generalization.

This approach offers a scalable, field-deployable solution for real-world agricultural diagnostics, helping reduce crop losses and promote sustainable farming.

🌟 Key Contributions
Deep learning framework for classifying six major potato leaf diseases with improved accuracy, scalability, and class balance.

Strategic data augmentation (Basic + Combinational) simulating real-world image capturing.

Use of precision, recall, F1-score, and accuracy for robust evaluation.

Hyperparameter tuning for model optimization in agricultural settings.

Comparative study of DenseNet201, ResNet152V2, and NasNetMobile under 3 training configurations.

Application of L2 regularization and early stopping to reduce overfitting.

A broader disease spectrum compared to prior works, enhancing generalizability across diverse leaf conditions.

🧠 Methodology Flowchart


