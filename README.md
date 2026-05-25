# 💵 Indian Currency Recognition Using ESP32-CAM

An AI-powered Indian Currency Recognition system using ESP32-CAM and CircuitDigest Cloud API. The ESP32-CAM captures the image of the currency note, sends it to the cloud AI, and announces the detected denomination through a speaker using Text-to-Speech.

---

## ⚙️ Features

- Real-time Indian currency recognition
- Voice announcement using speaker
- No ML training or dataset collection required
- Uses CircuitDigest Cloud AI API
- Beginner-friendly AI project

---

## 🧰 Components Required

- ESP32-CAM
- PAM8403 Amplifier
- Speaker
- Push Button
- Jumper Wires
- Breadboard

---

## 🚀 How It Works

1. Press the push button.
2. ESP32-CAM captures the image.
3. Image is uploaded to CircuitDigest Cloud API.
4. Cloud AI detects the denomination.
5. ESP32 announces the result through the speaker.

---

## 🔧 Setup

Update your Wi-Fi and API credentials:

```cpp
const char* WIFI_SSID  = "Your_WiFi";
const char* WIFI_PASS  = "Your_Password";
const char* API_KEY    = "Your_API_Key";
```

Upload the code to ESP32-CAM and open Serial Monitor at **115200 baud**.

---

## ✅ Advantages

- Easy to build
- Low-cost setup
- No TensorFlow or Edge Impulse needed
- Helps visually impaired users
- Fast cloud-based AI detection

---

## ⚠️ Limitations

- Requires internet connection
- Poor lighting may affect accuracy
- Folded notes may reduce detection quality
- Depends on cloud API availability

---

## 🛠️ Troubleshooting

### Camera Not Working
Check power supply and camera connections.

### API Timeout
Ensure stable Wi-Fi connection.

### No Audio Output
Verify PAM8403 and speaker wiring.

### Poor Detection
Use proper lighting and clear currency images.

---

## ❓ FAQ

### Does it work offline?
No, internet is required for cloud AI processing.

### Can it detect fake notes?
No, it only recognizes denominations.

### Can it detect damaged notes?
Slightly damaged notes may work if visible properly.

---

## 🔗 Links

- CircuitDigest Cloud: https://circuitdigest.cloud
- GitHub Repository: https://github.com/Circuit-Digest/Currency-Detection-Using-ESP32-Cam

---

Made with ❤️ using ESP32-CAM and CircuitDigest Cloud AI
