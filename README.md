# 📷 ESP32-CAM Object Detection using Edge Impulse & OLED Display

This project uses the ESP32-CAM and a pre-trained Edge Impulse model to perform real-time object detection. The results are displayed on a connected OLED screen and printed to the Serial Monitor.

---

## 🔧 Hardware Required

- ESP32-CAM (AI Thinker module)
- SSD1306 OLED Display (I2C, 128x64)
- Jumper wires
- FTDI USB to Serial Programmer
- Breadboard (optional)

---

## 🔌 OLED Wiring (I2C)

| OLED Pin | ESP32-CAM Pin |
|----------|---------------|
| VCC      | 3.3V          |
| GND      | GND           |
| SCL      | GPIO 14       |
| SDA      | GPIO 15       |

> You can modify the I2C pins in the code if needed.

---

## 🧠 Edge Impulse Model

1. Create an object detection project on Edge Impulse
2. Collect and label your dataset
3. Train the model
4. Export as `C++ Arduino Library`
5. Import it into your Arduino IDE or PlatformIO project

---

## 📦 Required Libraries

- `esp_camera`
- `Adafruit_GFX`
- `Adafruit_SSD1306`
- Edge Impulse Inference Library (`your_ml_model.h`)

---

## ⚙️ Features

- Captures image using ESP32-CAM
- Runs inference on the captured image using Edge Impulse model
- Displays detected object names and confidence on OLED
- Logs results on Serial Monitor

---

## ▶️ How to Use

1. Connect your hardware as per the wiring diagram
2. Upload the code using Arduino IDE or PlatformIO
3. Open Serial Monitor at 115200 baud
4. The camera will capture images and run real-time object detection

---

## 🖥️ Output Example

** OLED Display:*like esp=95% , TTL= 78% **

