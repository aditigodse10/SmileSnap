# 😊 Face & Smile Detection using OpenCV

A fun little Python project that uses OpenCV to detect faces and smiles in real-time using your webcam!
Capture smiles and save happy moments automatically. 📸✨

---

## ✨ Features

✅ Real-time **face detection**
✅ Real-time **smile detection**
✅ Automatically **saves images** to your Desktop
✅ Press **q** anytime to quit

---

## 🧰 What You’ll Need

* 🐍 Python 3.x
* 📦 OpenCV → `pip install opencv-python`
* 📦 Numpy → `pip install numpy`

---

## 📁 Project Structure

```
SSCP/
├── datasets/
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_smile.xml
├── main.py
└── README.md
```

⚠️ Download the required `.xml` files from [here](https://github.com/opencv/opencv/tree/master/data/haarcascades) and place them in the `datasets` folder.

---

## 🚀 How to Run

1. Install the required libraries:

   ```bash
   pip install opencv-python numpy
   ```
2. Make sure your **datasets** folder has the Haar cascade XML files.
3. Allow camera permission if you’re on macOS.
4. Run the script:

   ```bash
   python main.py
   ```
5. Smile! 😄 Your images will be saved automatically.
6. Press **q** to stop the app.

---

## 📸 Sample Output

*Here’s what it looks like in action:*

> <img width="124" alt="Screenshot 2025-07-08 at 3 03 46 PM" src="https://github.com/user-attachments/assets/0e646994-3710-4266-baba-94b90f9622d8" />
> <img width="1470" alt="Screenshot 2025-07-08 at 3 10 18 PM" src="https://github.com/user-attachments/assets/6efa7a5d-25c5-45cb-9ace-bfb90e8c40fa" />


---

## 📝 Notes

* Images save to your **Desktop** by default.
* If you see any errors, check:

  * Camera permissions 🎥
  * Missing cascade files 📄

---

💖 Happy Coding & Keep Smiling! 😊

