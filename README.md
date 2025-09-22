# Transfer Learning Project 🎯

## Overview 📚
This project demonstrates the concept of **Transfer Learning** using TensorFlow and Keras. The main focus is to leverage pretrained models such as **MobileNetV2**, then modify, save, and reload them for custom tasks. The project contains Jupyter Notebooks that walk through building, saving, and loading models, making it easier to reuse and adapt models for different datasets.

## Methods 🖥️
1. **Model Building:**  
   Utilizes pretrained architecture (MobileNetV2) as a base model for transfer learning. The top layers are modified to fit custom classification tasks.  

2. **Training & Fine-Tuning:**  
   - Freeze early layers of the pretrained model to prevent overfitting on small datasets.  
   - Fine-tune upper layers to adapt the model to a new dataset.  

3. **Saving Model:**  
   Demonstrates how to save trained models for later use in `[W3][TF][Self Model] Save Model.ipynb`.  

4. **Loading Model:**  
   Shows how to reload saved models for inference or further training in `[W3][TF][Self Model] Load Model.ipynb`.  

---

## Installations 🛠️
Before running the notebooks, make sure the following libraries are installed:

* `tensorflow`
* `keras`
* `numpy`
* `matplotlib`
* `jupyter`

---

## Results 📈

- Successful implementation of MobileNetV2 transfer learning.
- Demonstrated how to save and load models effectively.
- Provided a reusable workflow for applying transfer learning on custom datasets.

---

## Contributions 🤝

Contributions and suggestions are highly appreciated.
