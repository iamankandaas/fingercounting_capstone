# 🖐️ Finger Counting using OpenCV

This is a beginner-level computer vision project that counts the number of fingers held up in front of a webcam. I applied the concepts and frameworks learned in my course to design and implement this **naive but functional finger counting system** using OpenCV and Python.

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **NumPy**
- **Scikit-learn (pairwise distance module)**

---

## 🎯 Features

- Real-time video capture from webcam
- Region of Interest (ROI) setup for hand detection
- Background averaging to isolate the hand from the scene
- Image thresholding and contour extraction
- Convex hull analysis to detect and count extended fingers
- Visual feedback with live contour drawing and finger count display

---

## 💡 What I Learned

- How to model static backgrounds using running averages
- Image preprocessing techniques (blurring, grayscale conversion, thresholding)
- Contour detection and analysis in OpenCV
- Convex hull and basic geometry for object recognition
- Structuring an end-to-end OpenCV application pipeline

---

## ⚠️ Limitations

- Sensitive to lighting and background changes  
- ROI is hardcoded and works best in a fixed setup  
- Cannot detect certain hand gestures (e.g. spread-apart fingers like Spock 🖖)  
- Assumes only one hand/object in the ROI  

---

## 🚀 Future Improvements

- Use of dynamic ROI detection or hand tracking modules  
- Integration with **MediaPipe** or **Deep Learning** models for more accurate gesture recognition  
- Make the UI adaptive for different screen sizes and positions  
- Add support for multi-hand detection and gesture classification  

---

## 🧠 Conclusion

This project served as a solid foundation to practice core computer vision concepts. While simple in its current form, it has a lot of potential to evolve into a robust gesture recognition tool.

---

## ✨ Author

**Ankan**  
M.Tech | Robotics & AI | IIT Guwahati
