<h1 align="center">
  AirTune 🐨🔊  
  <br>
  <sub><i>Control Volume with Your Fingertips</i></sub>
</h1>

<p align="center">
  ✋🎚️ Touchless. Futuristic. Functional.  
  <br>
  Adjust volume with just your hand gestures. No clicks, no taps.
</p>

---

## 🔍 Problem Statement

Traditional volume controls require physical interaction — not ideal when your hands are occupied or you're trying to stay germ-free.

**AirTune** changes that by introducing a **gesture-based volume control system**, perfect for:

- 🍳 Cooking  
- 🏋️ Working out  
- 🧑‍🏫 Presenting  
- 💻 Using shared or public devices  

---

## 📌 Project Overview

**AirTune** leverages **Computer Vision** to track your fingers and adjust volume on the fly.  

### 💡 How it works:

- Detects hand landmarks using **MediaPipe**
- Measures distance between your **thumb** and **index finger**
- Converts that distance to a **volume level**
- Updates system audio using **PyCaw**

This creates a **hands-free, intuitive**, and **futuristic** user experience.

---

## 🧰 Tech Stack & Libraries

| 🛠️ Library     | 🔍 Purpose                                 |
|----------------|---------------------------------------------|
| `OpenCV`       | Real-time webcam access & image processing  |
| `MediaPipe`    | Hand tracking & landmark detection          |
| `PyCaw`        | System audio control on Windows             |

---

## 🗂 Code Files

- `VolumeHandGesture_Main.py` – Main script integrating all components  
- `HandTracking_Module.py` – Detects hand & extracts landmarks

📁 **[Access the Code Folder](https://drive.google.com/drive/u/0/folders/1SsX0naYbSHZ02e_6zI18QLKILRrSMgII)**

---

## 🔄 Workflow

> A breakdown of the real-time gesture flow:

1. **📦 Import Libraries**  
   `cv2`, `mediapipe`, `math`, `pycaw`, etc.

2. **🎥 Set Up Webcam**  
   Capture live frames using OpenCV.

3. **🖐 Initialize Hand Detector**  
   Use MediaPipe to detect hand and landmarks.

4. **🔊 Access Audio Device**  
   Connect to system volume using PyCaw.

5. **♻️ Main Loop**
   - Track finger positions  
   - Calculate fingertip distance  
   - Map to volume level  
   - Display real-time feedback on screen

---

## 📽️ Demo

🎬 *Coming Soon* – A quick video showing AirTune in action.

---

## 👩🏻‍💻 Author

**Made with 💡 by Jansi Goswami**  
_M.Tech in AI & Data Science | Gesture Interaction Enthusiast_

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/jansi-goswami-3a63141a5/)

---

## 📣 Note

⚠️ AirTune currently supports **Windows OS only** (due to PyCaw compatibility).  
✨ Pull requests and contributions for **cross-platform** support are welcome!

---

> “The best interface is no interface.” – Golden rule behind AirTune

