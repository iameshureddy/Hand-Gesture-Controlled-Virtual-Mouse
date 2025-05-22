# Hand-Gesture-Controlled-Virtual-Mouse

 
This project allows you to control the mouse cursor using **hand gestures** via a webcam. It utilizes **OpenCV, Mediapipe, and PyAutoGUI** for hand tracking and mouse control. Use PyCharm Platform. 
![Uploading Screenshot (1).jpg…]()



## **Installation Steps (For PyCharm)**
### **1️⃣ Install Python**  
Ensure you have **Python 3.11.9** installed. You can download it from [Python Official Website](https://www.python.org/downloads/).  



### **3️⃣ Install Required Packages**  
Open PyCharm and follow these steps:  


#### **Using PyCharm GUI:**  
1. Go to **File → Settings → Project: YourProjectName → Python Interpreter**  
2. Click on **"+" (Add Package)**  
3. Search for **opencv-python**, **mediapipe**, and **pyautogui**  
4. Click **Install Package**  

### **4️⃣ Run the Project**  
1. Open **PyCharm**  
2. Load the project folder  
3. Open `virtual_mouse.py` (or whatever your main file is named)  
4. Run the script using **Run → Run 'virtual_mouse'**  

### **5️⃣ How It Works**  
- **Move Cursor**: Move your index finger to move the mouse.  
- **Click**: Touch your thumb and index finger together to click.  
- **Exit**: Press **'q'** to quit the program.  

---

## **Requirements**
- Python **3.11.9**  
- OpenCV  
- Mediapipe  
- PyAutoGUI  
 

## **Troubleshooting**
❓ **ModuleNotFoundError: No module named 'cv2'**  
👉 Run `pip install opencv-python`  

❓ **Hand gestures not detected?**  
👉 Ensure the webcam is working properly. Try increasing `min_detection_confidence` in the code.  

---

💡 **Contributions are welcome!** Feel free to fork and improve the project. 🚀  
🔗 **GitHub Repo:** [https://github.com/iameshureddy/Hand-Gesture-Controlled-Virtual-Mouse]  

