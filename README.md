# gesture-driving-control
# 🚗 Hand Gesture Controlled Driving Game (Python + MediaPipe + OpenCV)

Control a game with just your hand gestures using a webcam!  
No keyboard or controller needed — just Python, your hand, and the power of computer vision.

---

## 📸 How It Works

- Uses **MediaPipe** to detect hand landmarks
- Recognizes gestures (like ✌️, ☝️, ✊, 🖐️) with **OpenCV**
- Maps gestures to arrow key presses with **pyautogui**
- Works in real time with ~30 FPS

---

## ✋ Gesture Mapping

| Gesture | Action      |
|--------|-------------|
| ☝️ Index finger up      | Move Up     |
| ✊ Fist                  | Move Down   |
| ✌️ Index + Middle       | Move Left   |
| 🖐️ All fingers          | Move Right  |

---

## 🕹️ Use Cases

- 🎮 Play browser or PC driving games
- 🧑‍🦽 Accessibility tools for touchless control
- 🖥️ Smart kiosks and AR displays

---

## 📦 Requirements

- Python 3.9+
- `opencv-python`
- `mediapipe`
- `pyautogui`

Install with:

```bash
pip install -r requirements.txt
