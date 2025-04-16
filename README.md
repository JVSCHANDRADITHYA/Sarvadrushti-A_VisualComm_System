
# 🌫️ Sarvadrushti: Beyond the Fog

In the northern states of India, fog and haze often reduce visibility to **5-10 meters** 🚗👀. This creates dangerous driving conditions where the naked eye cannot perceive obstacles or vehicles in time.

**Sarvadrushti** is here to provide a solution! 🚀 We leverage **LiDAR** and advanced **deep learning models** to detect and display objects and vehicles **beyond the visible range** in real-time, ensuring safer navigation in low-visibility environments. 🌐💡

https://github.com/user-attachments/assets/3560964a-40d6-41ee-b952-921f737c1835

### codebase still under development will be adding all of them soon.
---

## 🛠️ Key Features
- **Real-Time Object Detection**: Identifies vehicles and obstacles beyond visual range using LiDAR and deep learning.
- **Enhanced Visibility**: Visualizes objects even in extreme fog or haze conditions.
- **Driver Assistance**: Provides critical information to drivers, helping them make informed decisions in low visibility. 

## 📸 Test Input Samples
Below are some sample input data used for testing:

![LiDAR Input Sample](https://github.com/user-attachments/assets/e18e46d7-7f1b-4e5e-8cbf-f06ea7d02d3b)
<p align="center">Fig: LiDAR scan of the environment</p>

![Car LiDAR Data](https://github.com/user-attachments/assets/e4620290-8e10-4404-9da0-69a3134bb7e5)
<p align="center">Fig: Car detected using LiDAR data</p>

## 🎯 Output Results
These are the real-time outputs after processing the data:

![Output 1](https://github.com/user-attachments/assets/b48d641d-7389-4118-b6b9-c954ec3bad82)
<p align="center">Fig: Detected vehicles beyond fog</p>

![Output 2](https://github.com/user-attachments/assets/c38f0f32-6226-418b-8be5-7d33ea77494f)
<p align="center">Fig: Real-time object detection in action</p>

---

## ⚙️ How It Works
1. **Sensor Setup**: LiDAR sensors are mounted on the vehicle, continuously scanning the surroundings.
2. **Data Acquisition & Preprocessing**: The sensor collects data and converts it into a point cloud.
3. **Object Detection & Classification**: Advanced deep learning models (e.g., Faster R-CNN with ResNet50) classify detected objects.
4. **Real-Time Tracking**: The system tracks the distance and motion of objects, offering real-time feedback to the driver.
5. **Visualization**: The processed data is displayed on the dashboard, enhancing the driver’s visibility and awareness.

---

## 📚 Technical Stack
- **Language**: Python 🐍
- **Framework**: PyTorch 🔥
- **Model**: Faster R-CNN with ResNet50 for object detection 🧠
- **Edge Device**: NVIDIA Jetson Nano Developer Kit

---

## 🚀 Getting Started

### Installation
To set up Sarvadrushti on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/sarvadrushti.git
    cd sarvadrushti
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have a compatible LiDAR sensor connected to your system.

### Usage
Run the main detection script:
```bash
python3 main.py
```

The real-time object detection will start, providing enhanced visibility in low-visibility conditions.

---

## 👥 Contributors

- **J.V.S Chandraditya**
- **Siddharth Verma**
- **Dharaneesh Guttikonda**
- **Anurag Sahu**

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact
For any questions, feel free to open an issue or reach out via email at anuragsahu4328@gmail.com.

Happy Coding! 😄👨‍💻👩‍💻
