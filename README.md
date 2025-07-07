# 🎥 Motion Detection & Alert System

A real-time motion detector built with OpenCV —  
it watches your surroundings, catches movement, sounds an alarm, and even emails you the evidence.

---

## 🧠 What It Does

- 📷 Captures live video from your camera  
- 🎯 Compares frames to detect motion  
- 🔊 Sounds a beep alarm when movement is detected  
- 📩 Sends an email with the captured image(s) as proof  
- 🖥️ Simple GUI to turn alerts on/off

---

## 💡 Use Case

Perfect for home security, basic surveillance setups, or just catching whoever keeps stealing your snacks.

---

## 🛠 Built With

- **OpenCV** for video processing & frame differencing  
- **smtplib** for email notifications  
- **Tkinter** for a lightweight GUI  
- **Pygame** or **winsound** for the alarm (depending on your OS)

---

## 🧪 How it Works (Quick Breakdown)

1. Starts webcam feed  
2. Continuously compares current frame with previous one  
3. If significant change is detected → triggers  
    - Beep sound (optional toggle)  
    - Email alert with snapshot  
4. Keeps running until manually stopped

---

## 📦 To Use This, You’ll Need:

- Python 3.x  
- OpenCV (`pip install opencv-python`)  
- Email credentials (preferably a throwaway Gmail with app password)  
- Tkinter (included with Python)  
- OS-compatible audio lib (`winsound` on Windows / `pygame` otherwise)

---

## 📸 Demo / Screenshot

> *(You can add a screenshot here of the UI or detection feed)*

---

## ⚠️ Note

Make sure to:
- Allow less secure apps or use an app password if you're using Gmail  
- Adjust sensitivity thresholds in code if it’s too noisy or too strict  
- Disable the beep if you're running it at 3AM and want to keep your roommates

---

> *This project doesn't just watch — it warns. Built because I got tired of guessing what moved in the background.*
