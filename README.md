## 🏗️ Workflow

1. Dataset Creation  
   - Captured hand landmarks using MediaPipe  
   - Stored labeled gesture data  

2. Model Training  
   - Trained classification model using extracted features  
   - Saved model as `.pkl` file  

3. Real-Time Inference  
   - Live webcam input  
   - MediaPipe hand tracking  
   - Gesture prediction using trained model  

4. Output  
   - Recognized gestures displayed in real-time
   
⚙️ System Requirements

- Python >= 3.8  
- Webcam (for real-time gesture detection)  
- OS: Windows / Linux / macOS  

📦 Dependencies

Install required libraries:

```bash
pip install -r requirements.txt
