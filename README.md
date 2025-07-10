# IoT_Data_Analytics
**Meta-learning project – Prof. Caruccio**  
**Student: Leonardo Falanga – Matricola [0522502019]**

In this experiment, I built a real **meta-dataset** from ECG (electrocardiogram) time series blocks. I extracted features using the **tsfresh** library, compared anomaly detection models (such as **K-Nearest Neighbors** and **Isolation Forest**), and trained a **meta-classifier** capable of selecting the most suitable model based on the characteristics of the signal.

## Key aspects of the project:
- The dataset was constructed from real ECG data.
- Classification was balanced through block-level segmentation.
- Evaluation was realistic, using a proper train/test split.
- Performance was also measured in terms of **runtime efficiency**.

## Results
The meta-classifier successfully selected the best anomaly detection model for each case. It showed good generalization performance, maintaining high accuracy even on unseen data.

In addition, I included the **AIfES (Artificial Intelligence for Embedded Systems)** library, developed by Fraunhofer IMS – Institute for Microelectronic Circuits and Systems, Germany.
AIfES® is a registered trademark of Fraunhofer-Gesellschaft. It enables deployment of machine learning models on embedded hardware. This opens the door to future applications of this work in **IoT (Internet of Things)** and **Edge AI** scenarios.

## Libraries used (installation)
```bash
pip install tsfresh pyod scikit-learn pandas matplotlib seaborn
```
