# Skin-Disease-Classification
A Machine Learning model built for **"Classifying 21 Skin Diseases"**

---

### **👥 Team Members**  

| Name | GitHub Handle | Contribution |  
|------|-------------|--------------|  


---

## **🎯 Project Highlights**  

- Utilized **ResNet** with **Transfer Learning** and **CNN techniques** to build a robust classification model.  
- Achieved an **F1 score of 42%** and ranked **26th** on the **Kaggle Leaderboard**.  
- Used **Python, TensorFlow, NumPy, Pandas** to interpret model decisions and analyze results.  
- Implemented **data augmentation** to improve generalization and overcome class imbalances.  

📚 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)  

---

## **👩‍💻 Setup & Execution**  

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/Skin-Disease-Classification.git
   cd Skin-Disease-Classification
   ```  

2. **Access the Dataset:**  
   - Download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/bttai-ajl-2025/data).  
   - Place it inside the `data/` directory.  
---

## **🏰 Project Overview**  

- This project was part of the **Break Through Tech AI Program**, aiming to build AI models for real-world problems.  
- The challenge involved classifying 21 different skin diseases from medical images.  
- The goal was to develop an accurate model while ensuring **fairness across different skin tones**.  

---

## **📊 Data Exploration**  

- **Dataset:** Used the provided Kaggle dataset consisting of thousands of labeled skin disease images.  
- **Preprocessing Techniques:**
  - Image resizing and normalization.  
  - Data augmentation (flipping, rotation, brightness adjustments).  
  - Handling class imbalances with **weighted sampling**.  

**Visualizations:**  
- Sample images from the dataset.  
- Distribution of classes and skin tones.  
- Heatmaps to analyze model focus areas.  

---

## **🧐 Model Development**  

- **Model:** ResNet50-based CNN with Transfer Learning.  
- **Training Setup:**
  - 80% training, 10% validation, 10% test split.  
  - **Optimizer:** Adam, Learning rate scheduling.  
  - **Loss Function:** Categorical Crossentropy.  
- **Hyperparameter Tuning:**
  - Batch size experiments (16, 32, 64).  
  - Data augmentation tuning.  

---

## **📈 Results & Key Findings**  

- **Final Model Performance:** Achieved an **F1-score of 42%**.  
- **Kaggle Ranking:** Ranked **26th** out of **73** teams.  
- **Fairness Evaluation:** Model performance was analyzed across different skin tones to assess bias.  

**Key Insights:**  
- Data augmentation significantly improved performance.  
- Model struggled with **underrepresented skin disease classes**.  
- Further fairness evaluations needed for **balanced classification across skin tones**.  

---

## **🎨 Impact Narrative**  

- Addressed fairness concerns using **data augmentation** and bias mitigation techniques.  
- Potential impact on **AI-driven dermatology**, especially for underrepresented communities.  
- Ensuring AI models are **equitable and generalizable** in real-world medical applications.  

---

## **🚀 Next Steps & Future Improvements**  

- Improve model fairness by **curating a more diverse dataset**.  
- Implement **attention mechanisms** to better localize disease patterns.  
- Explore **multi-modal approaches** (e.g., combining images with patient metadata).  
- Fine-tune the model using **larger pre-trained networks** like EfficientNet.  

---

## **📜 References & Additional Resources**  

- [TensorFlow Documentation](https://www.tensorflow.org/)  
- [AJL Fairness Guide](https://haas.berkeley.edu/wp-content/uploads/What-is-fairness_-EGAL2.pdf)  
- [Break Through Tech AI Program](https://breakthroughtech.org/)  

---
