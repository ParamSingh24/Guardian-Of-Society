🚨 Harassment Detection System
A real-time AI-based harassment detection system using YOLOv8 Pose Estimation. It detects aggressive behavior through hand movements and triggers an alarm while sending an email alert 🚨📧.

🔹 Features
✅ Real-time detection using OpenCV
✅ YOLOv8 Pose Estimation for aggression recognition
✅ Plays an alarm sound when aggression is detected
✅ Sends an email alert with location details
✅ Easy to use with simple setup

🔧 Installation
1️⃣ Clone the Repository

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
2️⃣ Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Download & Place Model and Assets

Place yolov8n-pose.pt inside the project folder.
Place alarm.mp3 in the root folder.
4️⃣ Run the Program

bash
Copy
Edit
python pPp.py
⚡ How It Works
📌 The system continuously monitors live video.
📌 If aggressive behavior (e.g., raised hands in an attack position) is detected:

It plays an alarm 🚨
It sends an email alert 📧
📜 Requirements
Python 3.8+
OpenCV
Pygame (for alarm sound)
Ultralytics YOLOv8
NumPy
smtplib (for email notifications)
🛠 Configuration
Modify pPp.py to set your email credentials and location details.
Adjust detection sensitivity if needed.
📬 Contact
If you have any questions, feel free to reach out! 🚀
