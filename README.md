# Driver-Drowsiness-Detection  [![Detecting Driver Drowsiness ...](https://images.openai.com/thumbnails/495a5e4f394ec1c2506d676f44ffbb09.png)](https://www.mdpi.com/2076-3417/11/18/8441)

Certainly! Based on the contents of your GitHub repository [Vishnu-yadav-bot/Driver-Drowsiness-Detection](https://github.com/Vishnu-yadav-bot/Driver-Drowsiness-Detection), here's an enhanced and professional `README.md` description tailored to your project:

---

# Driver Drowsiness Detection

A real-time driver drowsiness detection system designed to enhance road safety by monitoring the driver's facial features and alerting them upon signs of fatigue. This application utilizes computer vision techniques to analyze eye movements and trigger alarms when drowsiness is detected.

## 🚀 Features

* **Real-Time Monitoring**: Continuously analyzes video feed from a webcam to monitor the driver's eyes.
* **Eye Detection**: Employs Haar cascade classifiers to detect eyes and determine their state (open or closed).
* **Drowsiness Alert**: Triggers an audible alarm (`alarm.wav`) when prolonged eye closure is detected, indicating potential drowsiness.
* **Modular Design**: Structured with separate modules (`app.py`, `model.py`) for scalability and maintainability.([GitHub][1])

## 🛠️ Technologies Used

* **Python**: Primary programming language for the application.
* **OpenCV**: Used for image processing and real-time video analysis.
* **Haar Cascade Classifiers**: Pre-trained models for eye detection.
* **Pygame**: Handles the playback of the alarm sound.([GitHub][2])

## 📁 Project Structure

```
Driver-Drowsiness-Detection/
├── haarcascade_eye.xml
├── alarm.wav
├── app.py
├── model.py
├── README.md
└── .gitattributes
```

* `haarcascade_eye.xml`: Haar cascade file for eye detection.
* `alarm.wav`: Sound file played when drowsiness is detected.
* `app.py`: Main application script that initiates the detection process.
* `model.py`: Contains functions related to eye detection and analysis.
* `README.md`: Project documentation.

## 🔧 Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Vishnu-yadav-bot/Driver-Drowsiness-Detection.git
   cd Driver-Drowsiness-Detection
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required packages:

   ```bash
   pip install opencv-python pygame
   ```

3. **Run the Application**:

   ```bash
   python app.py
   ```

## 📌 Usage

* Ensure your webcam is connected and functioning.
* Run the application using the command above.
* The system will start monitoring your eyes in real-time.
* If drowsiness is detected (i.e., eyes closed for a certain duration), an alarm will sound to alert you.

## ⚠️ Note

* Ensure adequate lighting for optimal detection accuracy.
* This system is a prototype and should not replace professional driver assistance systems.

