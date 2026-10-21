# Driver-impairment-detection
# Multimodal AI-Based Driver Impairment Detection and Intelligent Safety Response System

## 📌 Project Overview

This project is a software-based prototype that uses computer vision and AI techniques to identify possible signs of driver drowsiness and demonstrate intelligent safety responses.

The system analyzes driver video to estimate facial indicators such as eye closure and mouth opening. It also includes a simulated alcohol sensor input to demonstrate how multiple indicators can be combined to generate a safety status.

## 🎯 Objectives

- Detect facial landmarks from driver video.
- Estimate Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR).
- Identify possible signs of drowsiness and yawning.
- Simulate alcohol sensor readings.
- Generate driver safety status alerts.
- Provide audio warnings and a web dashboard.

## ✨ Features

- **Face Landmark Detection:** Uses MediaPipe Tasks.
- **Drowsiness Analysis:** Analyzes eye and mouth movements.
- **Alcohol Input Simulation:** Demonstrates decision-making using a simulated sensor value.
- **Intelligent Safety Status:** Displays a prototype status based on configured thresholds.
- **Voice Alerts:** Generates audio warnings.
- **Interactive Dashboard:** Uses Gradio to display the results.

## 🛠️ Technologies Used

- Python
- Google Colab
- OpenCV
- MediaPipe
- NumPy
- Pandas
- Matplotlib
- Gradio
- gTTS (Google Text-to-Speech)

## ⚙️ How It Works

1. Load a driver video.
2. Process sampled video frames using face landmark detection.
3. Calculate facial indicators such as EAR and MAR.
4. Compare the indicators with configurable demonstration thresholds.
5. Combine the results with a simulated alcohol input.
6. Display the resulting status and generate a warning when appropriate.

## 🚀 How to Run

1. Open the project notebook in Google Colab.
2. Install the required Python libraries.
3. Upload a suitable driver video when prompted.
4. Run the notebook cells in order.
5. Open the Gradio dashboard and test the simulated inputs.

## ⚠️ Limitations and Safety

This project is an educational software prototype, not a certified driver-monitoring or medical system. Alcohol readings are simulated and are not measured by a physical sensor. Facial indicators alone cannot confirm impairment. The system has not been validated for real-world driving and does not control a vehicle or perform an actual emergency stop.

## 🔮 Future Improvements

- Integrate data from a real sensor in a properly tested setup.
- Improve detection using diverse video datasets.
- Evaluate accuracy using labeled test data.
- Add configurable alert thresholds and more robust temporal analysis.
- Explore deployment as a web application.

## 👨‍💻 Project Type

Academic / Educational Prototype

## Open in Colab


