# ✋ Sign Language to Text and Audio Conversion  

## 📌 Overview  
This project converts **hand gestures (sign language)** into **text** and **audio speech** in real-time.  
It is designed to help bridge the communication gap between people with hearing or speech impairments and others.  

---

## 🚀 Features  
- Real-time **hand gesture detection** using a camera.  
- **CNN model** for gesture classification.  
- **UNet model** for hand segmentation.  
- Converts recognized gestures into **text**.  
- Converts text into **audio** using Text-to-Speech.  
- **Flask-based web interface** for interaction.  
- Application in **first aid assistance during natural disasters**.  

---

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - OpenCV (image processing)  
  - Mediapipe (hand tracking)  
  - TensorFlow / Keras (CNN & UNet models)  
  - NLTK (natural language processing)  
  - Flask (web framework)  
  - Pyttsx3 / gTTS (text-to-speech)  

---

## 📂 Project Workflow  
1. **Data Collection & Preprocessing**  
   - Captured hand gesture images using a camera.  
   - Annotated and augmented the dataset.  

2. **Model Design & Training**  
   - Built a **CNN model** for gesture classification.  
   - Used **UNet model** for hand segmentation.  
   - Fine-tuned hyperparameters for accuracy.  

3. **Gesture Recognition & Interpretation**  
   - Real-time recognition with OpenCV & Mediapipe.  
   - Converted recognized gestures to **text**.  
   - Applied **Levenshtein distance algorithm** for database query matching.  

4. **Output Generation**  
   - Converted text into **audio speech**.  
   - Displayed results via **Flask web interface**.  

---

## ⚙️ Installation  

Clone the repository:  
```bash
git clone https://github.com/Sharath12357/Hand_gesture_Detection.git
cd Hand_gesture_Detection
