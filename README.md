
# 🧍‍♂️ Posture Detection using MediaPipe and OpenCV

This project demonstrates a real-time posture detection system using **MediaPipe Holistic**, **OpenCV**, and **Scikit-Learn** to analyze and classify a person's posture via webcam.

---

## 📦 Features

- Real-time posture tracking using webcam feed.
- Uses `MediaPipe Holistic` to detect key landmarks (pose, face, hands).
- Captures and processes landmark data for posture classification.
- Supports saving training data and training a simple ML model.
- Highlights posture classification results visually on video feed.

---

## 🛠️ Requirements

Install dependencies via:

```bash
pip install mediapipe opencv-python pandas scikit-learn
```

---

## 🚀 How to Use

1. **Open the notebook** `posture_detection.ipynb` in Jupyter or Google Colab.
2. **Step-by-step execution**:
   - 📦 **Install & import dependencies**
   - 🎥 **Capture webcam feed and run MediaPipe Holistic**
   - 🧠 **Extract keypoint data for model training**
   - 📊 **Train a classifier (e.g., Random Forest) on labeled posture data**
   - 📌 **Run live posture prediction using the trained model**

3. **Label your own data**: Adjust labels like "good", "bad", "slouching", etc., while collecting data.

4. **Train your model** using the collected dataset and evaluate performance.

5. **Run the detection live** using the webcam and get instant feedback on posture.

---

## 📸 Sample Output

_Include a screenshot of your posture detection interface here:_

<b> Normal Position </b> <br>
![image](https://github.com/user-attachments/assets/5a693653-8487-4ebc-8a77-f452fc94b9d0)

<b> Surrender Position </b> <br>
![image](https://github.com/user-attachments/assets/a43274a5-5d95-4af4-b4a9-d26bc71745ae)



## 📁 Project Structure

```
posture_detection.ipynb    # Main Notebook
data/                      # (Optional) Collected posture CSVs
model.pkl                  # (Optional) Saved ML model
```

---

## 🧠 Tech Stack

- [MediaPipe Holistic](https://google.github.io/mediapipe/solutions/holistic)
- OpenCV
- Pandas / Scikit-learn
- Jupyter / Colab

---

## 🙋‍♂️ Author

Ashner Gerald Novilla
