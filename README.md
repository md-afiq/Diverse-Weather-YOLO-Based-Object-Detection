# Diverse-Weather-YOLO-Based-Object-Detection

This project implements a **YOLO-based object detection system** designed to operate in **diverse weather conditions** for autonomous vehicle applications.  
It can detect multiple object classes, including:

- **Vehicle**
- **Car**
- **Truck**
- **Person**
- **Motorcycle**
- **Traffic Light**

The system is trained and evaluated to ensure robust performance in challenging scenarios such as foggy, rainy, and clear weather conditions.

---

## 📌 Key Features
- **YOLO Model**: Fast and accurate object detection.
- **Multi-Weather Robustness**: Handles fog, rain, and normal conditions.
- **Multi-Class Detection**: Identifies vehicles, people, motorcycles, trucks, and traffic lights.
- **Real-World Autonomous Driving Relevance**: Ideal for traffic monitoring, smart transport, and safety applications.

---

## 📊 Example Results

### Rainy Weather
![Rainy Detection 01](Results%20Output/detected_rainy%20weather%2001.jpg)
![Rainy Detection 02](Results%20Output/detected_rainy%20weather%2002.jpg)

### Foggy Weather
![Foggy Detection 01](Results%20Output/detected_foggy%20weather%2001.jpg)
![Foggy Detection 02](Results%20Output/detected_foggy%20weather%2002.webp)




### Training and Evaluation Results.
![Results Graph](Results%20Output/results.png)


## 🎥 Sample Video Output.
[Click here to watch the video](Results%20Output/output_first_1000.mp4)

---

## 🚀 How It Works
1. **Data Preparation**  
   - Dataset contains annotated images from multiple weather conditions.
2. **Model Training**  
   - YOLO model trained with custom datasets.
3. **Inference**  
   - Detects multiple object classes in real-time video frames.
4. **Output**  
   - Annotated images & videos with bounding boxes and class labels.

---

## 💡 Applications
- Autonomous driving
- Traffic monitoring
- Road safety enhancement
- Smart city infrastructure

---

## 🛠 Tech Stack
- **Python**
- **YOLOv8/YOLOv9** (Ultralytics)
- **OpenCV**
- **Google Colab** / **Kaggle**
- **PyTorch**

---

## 📄 License
This project is released under the MIT License.
