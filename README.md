# Gesture-control

Welcome to**GESTURE-CONTROL**
This is a ✨gesture-controlled interface✨ powered by **MediaPipe**, where you wave at your webcam and the page actually *gets you*. It’s like magic, but with JavaScript.


Imagine controlling a webpage using just ✋ your hand. No mouse. No keyboard. Just you, your webcam, and your ✌️ victory sign or maybe even a 🖕 (yes, it reacts to that too).


 🎯 What Can You Do?

* ✌️ Show a **Victory sign** and get recognized
* 👍 Thumbs Up? Yup, we see you.
* 👆 Point? Sure, boss.
* 🖕 Middle finger? *BEEP!* Sound effect triggered. 😅
*  ✋ Palm too? Of course.


 
⚙️ Tech Behind This:

* **HTML + CSS + JavaScript** for frontend wizardry
* **MediaPipe Hands** for real-time hand landmark tracking 🧠
* **CameraUtils + DrawingUtils** to show the cool hand skeleton
* 🔊 **Sound feedback** when detected 



 🧪 Try It Live!

🔗 Just open the `index.html` in your browser (Chrome preferred)

Give it camera access and hold up your hand — boom, it’s alive! ⚡



 🎮 Gesture Guide

 Gesture:    Response:                                       
 ✌️          “Victory” detected                            
 👍          “Thumbs Up”                                   
 👆          “Pointing”                                    
                                     
 ✋          “Open Palm”                                   
 🖕            “Middle Finger” 
       






 📂 Files Overview

```
Gesture-control
│
├── index.html       ← html file + script file
├── style.css        ←  for styling
└── sounds
    └── sounds.mp3     ← sound effects 
```



 🧠 How It Works

MediaPipe detects **21 points on your hand**, tracks your finger movements, and based on position logic, it recognize gestures.

Simple, sweet, and surprisingly powerful!

 🙌 Acknowledgements

* Made  using [MediaPipe Hands](https://mediapipe.readthedocs.io/en/latest/solutions/hands.html)
* sound [google]
* Big thanks to your ✋ hand for being the real Most Valuable Player here.



 


