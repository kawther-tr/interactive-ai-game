# 🎮 Interactive Game — AI & Computer Vision

> 🎓 Final Thesis Project – Kawther Trabelsi

---

## 🌟 Presentation
Interactive game based on **computer vision** and **artificial intelligence**.
It's a tic-tac-toe game where the player throws a ball at a projected wall; the system detects the impact in real time and updates the game.
The game combines ball detection and real-time impact detection. Moreover, it offers a pleasant and immersive user experience through a fluid interface.
--

## 🎯 Objectives
- Detect the ball's position
- Detect the ball's impact position in real time.
- Synchronize the detection with the projected game.
- Provide immersive and responsive interaction.

---

## ⚙️ Technologies
- **YOLOv8**, **PyTorch**, **OpenCV**, **NumPy**
- **OpenCV** (BackgroundSubtractorMOG, image processing)
- **ESP32-CAM**, **USB Cam**, **balls of different shapes and colors**
- **Pygame** for the projected game interface
- **Epson video projector**
- Environment: Debian ARM64, Python 3.9+

---

## 🧩 How it works (simplified)
1. The camera captures the scene.
2. YOLOv8 detects the ball and calculates its coordinates.
3. Esp32cam detects the moment of contact.
4. The coordinates are sent to the Pygame engine at the moment of contact.
4. The projection is updated (X or O mark on the grid).

---

## 📸 Demonstration
Video: *(unlisted YouTube link / GIF / screenshots to be added)*

---

## ✅ Results
- Stable detection in motion.
- Good impact point accuracy.
- Acceptable latency for an interactive experience.

---

## 🚀 Possible Improvements
- Lighter models to reduce latency (e.g., YOLOv8-nano).
- Use of Jetson nano to detect ball position and impact from depth.
- Multiplayer modes.
- Web/tablet interface for remote control.

---

## 🔒 Code Confidentiality
The full source code is not public for academic/confidential reasons.
Access upon request (contact below).

---

## 👩‍💻 Author
**Kawther Trabelsi**
Student — Artificial Intelligence & Computer Vision
📧 ktrabelsi64@gmail.com
🌐 https://github.com/kawther-tr
