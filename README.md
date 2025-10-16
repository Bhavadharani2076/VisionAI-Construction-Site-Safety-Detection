# 🦺 VisionAI – Construction Site Safety Detection

**VisionAI** is an AI-powered project developed for a hackathon to ensure safety compliance at construction sites.  
The system uses **Deep Learning and Computer Vision** techniques to automatically detect whether employees are **wearing safety equipment** such as **helmets, safety vests, and boots** from video footage or images.

---

## 🎯 Project Objective

Construction sites are among the most hazardous workplaces. Ensuring every worker follows safety protocols is essential to prevent injuries.  
**VisionAI** automates the monitoring process using a camera-based AI system that identifies whether workers are wearing the required safety gear.

### 🧠 Core Goals:
- Detect employees present at a construction site.
- Check if they are **wearing helmets, vests, and other safety gear**.
- Alert or flag instances of non-compliance.
- Provide visual output and analytics for administrators.

---

## 📂 Dataset

**Type:** Custom-built dataset  
**Description:**  
Images and video footage of construction site workers were collected and labeled into multiple categories:
- With Safety Gear  
- Without Safety Gear  

This dataset was preprocessed and augmented to improve accuracy and generalization of the model.

---

## ⚙️ Tech Stack

| Component | Description |
|------------|-------------|
| **Language** | Python 3.8+ |
| **Frameworks** | TensorFlow, Keras, OpenCV |
| **Libraries** | NumPy, Pandas, Matplotlib, Scikit-learn |
| **Environment** | Jupyter Notebook / Google Colab |
| **Output** | Annotated video with detections (`output.mp4`) |

---

## 🚀 How It Works

1. **Data Collection & Preprocessing**  
   - Collected custom video and image data from construction environments.  
   - Labeled safety gear presence using custom annotations.  
   - Applied image augmentation for better training.

2. **Model Development**  
   - Used CNN-based architecture to detect objects and classify worker safety compliance.  
   - Trained using TensorFlow and Keras.

3. **Detection & Output**  
   - Input: Live or recorded construction footage.  
   - Output: Annotated video (`output.mp4`) marking workers with and without safety gear.

---

## 🧾 Notebook

You can view and run the main notebook file:
```bash
VisionAI (1).ipynb
```

The notebook covers:
- Dataset preprocessing  
- Model building and training  
- Evaluation and visualization of predictions  
- Exporting detection results as video output

---

## 👩‍💻 Author

**S Bhavadharani**  
GitHub: [@Bhavadharani2076](https://github.com/Bhavadharani2076)  
AI & Computer Vision | Safety Monitoring System  

---

## 📚 References

- [TensorFlow Documentation](https://www.tensorflow.org/)  
- [OpenCV Documentation](https://docs.opencv.org/)  
- [Keras API Reference](https://keras.io/api/)

---

## ⚠️ Disclaimer

This project is for **research and hackathon demonstration purposes only**.  
It should not be deployed for real-world monitoring without further validation and regulatory compliance.

---
