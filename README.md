# RealWaste Image Classifier

This project develops a machine learning model that classifies waste images into **nine predefined categories**:

- Cardboard  
- Food Organics  
- Glass  
- Metal  
- Miscellaneous Trash  
- Paper  
- Plastic  
- Textile Trash  
- Vegetation  

The model is trained on the **RealWaste dataset**, a collection of authentic, labeled images of waste items provided by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/908/realwaste).  
Accurate waste classification can improve recycling and disposal efficiency, contributing to more sustainable waste management practices.

The notebook includes **step-by-step code with comments and visualizations** to make the workflow easy to follow.

---

## 📊 Sample Results

### Model Training Progress
Below is an example of the model’s **training accuracy and loss curves**:
<img width="930" height="378" alt="images:accuracy_loss" src="https://github.com/user-attachments/assets/07812cdf-cb35-4ea5-b0ca-447b5cb7424e" />



### Prediction Examples
Sample predictions from the trained model:
<img width="966" height="633" alt="images:sample_predictions" src="https://github.com/user-attachments/assets/8103e809-175f-4980-9b5f-aa3a192f66ca" />


### Robustness testing 
Testing the model's robustness by uploading your own waste image:
<img width="1005" height="651" alt="images:robustnesstest" src="https://github.com/user-attachments/assets/d6110f6c-5f67-48ee-aae4-d17ccd86a7db" />


---

## 📂 Project Structure

The main notebook (`wasteclassifier514.ipynb`) is organized into the following sections:

1. **Data Preparation & Exploratory Analysis**  
2. **Training Preparation**  
3. **Model Building**  
4. **Model Training**  
5. **Evaluation**  
6. **Robustness Testing**

---

## 📑 Dataset

The dataset is not included in this repository due to size constraints, but it can be downloaded directly from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/908/realwaste).  
