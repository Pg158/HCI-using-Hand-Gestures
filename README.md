
# 🖐️ Human-Computer Interaction Using Hand Gestures

This project presents a real-time hand gesture recognition system for Human-Computer Interaction (HCI). It enables touchless control of a computer through simple finger gestures detected using a webcam. Users can move the mouse cursor, scroll pages, adjust system volume, and even control screen brightness — all using natural hand movements.

---

## 🚀 Features

### ✋ Hand Detection
Detects and tracks hand landmarks in real time using the MediaPipe framework.

### 🖱️ Cursor Control
Moves the mouse cursor according to the index finger's position on screen.

### 🔊 Volume Control
Adjusts system volume by changing the distance between specific fingers (e.g., thumb and index).

### 🧭 Scrolling
Performs scrolling actions using defined finger gestures.

### 💡 Brightness Control
(If supported) Allows screen brightness control using gesture inputs.

---

## 🛠️ Technologies Used

- **Python 3.x** – Base programming language  
- **OpenCV** – For real-time video capture and processing  
- **MediaPipe** – For hand landmark detection  
- **PyAutoGUI** – For controlling the mouse, volume, etc.  
- **Autopy** – Alternative for cursor and keyboard control  
- **NumPy** – For coordinate and math calculations

---

## 📦 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/Pg158/HCI-using-Hand-Gestures.git
cd HCI-using-Hand-Gestures
```

---

### 2. Install Dependencies

``pip install -r requirements.txt``

If requirements.txt is not available, install manually:

``pip install opencv-python mediapipe pyautogui autopy``

---

### ▶️ Usage
Make sure your webcam is connected. Then run:

``python Main.py``
You’ll see a webcam window showing hand landmarks in real-time. Try using different gestures to move the cursor or adjust volume.

Interactions:
Move Cursor – Use your index finger

Adjust Volume – Move thumb and index finger closer/farther

Scroll – Perform scroll gestures with two fingers

Adjust Brightness –  Trigger brightness gestures

You should see a real-time webcam window with hand landmarks drawn on your hand.

---

### 🖼️ Screenshots
![Cursor Control](<WhatsApp Image 2025-04-18 at 22.25.16_c44bd426.jpg>)
![Scroll up](<WhatsApp Image 2025-04-18 at 22.25.16_a47f557c.jpg>)
![Scroll down](<WhatsApp Image 2025-04-18 at 22.25.16_004f4280.jpg>)
![Reset](<WhatsApp Image 2025-04-18 at 22.25.17_36a936eb.jpg>)
![Volume Control](<WhatsApp Image 2025-05-02 at 20.35.54_5e97b7fe.jpg>)
![Brightness Control](<WhatsApp Image 2025-05-02 at 20.36.08_82c8f766.jpg>)

---

### 📁 Project Structure
HCI-using-Hand-Gestures/
├── Main.py                 # Main script to run the application
├── HandTrackingModule.py  # Reusable hand tracking module
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies

---

### 🤝 Contribution
Contributions are welcome!
If you'd like to contribute, feel free to:

Fork the repository

Make your changes

Submit a pull request

You can also open issues to suggest features or report bugs.

---

### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

---
