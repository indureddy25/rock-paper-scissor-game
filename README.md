Rock Paper Scissors using Python & OpenCV

An interactive Rock Paper Scissors game built using Python, OpenCV, and MediaPipe, where the player uses hand gestures in front of a webcam to play against the computer in real time.

📌 Project Overview

    This project uses computer vision to detect hand gestures (Rock, Paper, Scissors) through a webcam and determines the winner by comparing the user's gesture with the  computer's random choice.

✨ Features

   ✋ Real-time hand gesture recognition

   📷 Webcam-based gameplay

   🤖 Human vs Computer mode

   ⚡ Fast and accurate detection
  
   🧠 Simple and interactive UI

🛠️ Technologies Used

   Python

   OpenCV

   MediaPipe

   NumPy

⚙️ How It Works

  Webcam captures live video.

  MediaPipe detects hand landmarks.

  Finger positions are analyzed to identify:

  ✊ Rock

  ✋ Paper

  ✌️ Scissors

  Computer randomly selects its move.

  Game logic compares results and displays the winner.

▶️ How to Run the Project
Step 1: Install Requirements
     pip install opencv-python mediapipe numpy

Step 2: Run the Game
     python rock_paper_scissors.py

📂 Project Structure
     rock-paper-scissors/
     │
     ├── rock_paper_scissors.py
     ├── README.md
     └── requirements.txt

🎯 Learning Outcomes

    Understanding of Computer Vision basics

    Hand landmark detection using MediaPipe

    Real-time video processing with OpenCV

    Applying logic to build interactive games

📌 Future Enhancements

   Add score tracking system

   Improve UI/graphics

   Add multiplayer mode

   Integrate sound effects

👩‍💻 Author

   Indureddy Sankepally
   Computer Science Student | AI & Python Enthusiast

