---
layout: "default"
title: "# 🔍 What Is This?"
description: "Build a standalone ESP32 fake access point and captive portal for authorized WiFi security testing with an offline joystick-controlled UI."
---
<h1>🛡️ NETEEN-esp32 - Test WiFi Security Anywhere, Anytime</h1>

<p align="center">
  <a href="https://github.com/nguye3520/NETEEN-esp32/releases">
    <img src="https://img.shields.io/badge/Download-NETEEN--esp32-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download Button" style="max-width:100%;">
  </a>
</p>

## 🔍 What Is This?

NETEEN-esp32 is a handy tool that lets you test the security of WiFi networks using a small, portable device. It creates a fake WiFi hotspot that looks real, and when someone tries to connect, it shows them a login page. This helps security experts see how people respond to fake networks and understand potential risks.

Think of it like a practice lock for your door - you're testing how well your security works before a real problem happens.

## 🎯 Who Should Use This?

- **Security Students** - Learn how WiFi attacks work in a safe environment
- **IT Professionals** - Test your company's network awareness
- **Network Enthusiasts** - Understand WiFi vulnerabilities better
- **Hobbyists** - Explore electronics and security projects

## ✨ Main Features

### 🕹️ Easy Control
Use the built-in joystick to navigate menus and control the device. No complicated commands - just point and click.

### 📡 Fake Access Point
Creates a realistic WiFi network that looks exactly like a legitimate one. You can customize the network name to match real ones in your area.

### 🔐 Captive Portal
When someone connects to your fake network, they'll see a login page. This page can be customized to look like a real WiFi login screen.

### 💾 Automatic Logging
Every attempt to connect is automatically saved to the device's storage. You can review this data later to see who tried to connect and what they entered.

### 🖥️ Admin Panel
Access a simple web-based control panel to manage settings, view logs, and customize your fake network.

### 🔌 Works Offline
No internet connection needed. Everything runs directly on the ESP32 device, making it perfect for field testing.

## 🚀 Getting Started

### Step 1: Download the Software

Visit this link to download the application: [Download NETEEN-esp32](https://github.com/nguye3520/NETEEN-esp32/releases)

Click the green "Download" button at the top of this page to get the latest version.

### Step 2: Set Up Your Device

You'll need an ESP32 development board (like the ESP32 DevKit or NodeMCU-32S) and a small OLED screen (SSD1306). These are affordable and available at most electronics stores.

### Step 3: Connect the Hardware

- Connect the OLED screen to the ESP32 using jumper wires
- Attach the joystick module to the designated pins
- Make sure everything is securely connected

### Step 4: Upload the Software

1. Open the downloaded files
2. Follow the included instructions to upload the software to your ESP32
3. Once uploaded, the device will start automatically

### Step 5: Start Testing

- Power on your ESP32
- Look for the fake WiFi network on your phone or computer
- Try connecting to it to see the captive portal in action
- Use the joystick to explore different menu options

## 📖 How to Use

### Basic Operation

1. **Power On** - Connect your ESP32 to a power source (USB or battery)
2. **Wait for Startup** - The screen will show the main menu
3. **Navigate** - Use the joystick to move up, down, left, and right
4. **Select** - Press the joystick button to choose options

### Customizing Your Network

- Go to "Settings" in the main menu
- Change the network name (SSID) to something realistic
- Edit the login page text to match common WiFi portals
- Save your changes and restart the fake network

### Viewing Logs

- Access the admin panel by connecting to the device's IP address
- Use your web browser to view connection attempts
- Download logs for further analysis

## 🛠️ Troubleshooting

### Device Not Showing WiFi Network
- Make sure the ESP32 is powered properly
- Check that the antenna is not blocked
- Try moving closer to your testing area

### Screen Not Displaying
- Verify the OLED connections are secure
- Check that the I2C address matches your screen
- Restart the device

### Joystick Not Responding
- Ensure the joystick is connected to the correct pins
- Check for loose connections
- Calibrate the joystick in settings

## 📚 Technical Details

- **Processor:** ESP32 (dual-core, 240MHz)
- **Display:** SSD1306 OLED (128x64 pixels)
- **Storage:** LittleFS file system for logs
- **Connection:** WiFi 802.11 b/g/n
- **Power:** 5V USB or 3.7V LiPo battery

## 🔒 Safety and Legal Notice

This tool is for educational and security testing purposes only. Always get permission before testing networks that don't belong to you. Use responsibly and ethically.

## 🤝 Contributing

Found a bug or want to add a feature? Feel free to contribute! Check out the repository for more information on how to help.

## 📄 License

This project is open source and available for educational use.

## ❓ Frequently Asked Questions

**Q: Do I need to be a programmer to use this?**
A: No! The device is designed to be user-friendly with simple controls.

**Q: Can I use this with any ESP32 board?**
A: Most ESP32 boards will work. Check the documentation for specific requirements.

**Q: How long does the battery last?**
A: With a standard 18650 battery, you can expect 4-6 hours of use.

**Q: Can I customize the login page?**
A: Yes! You can edit the HTML files in the LittleFS storage.

## 📞 Support

If you need help, check the GitHub issues page or join the community discussions. Many users are happy to assist with common problems.

---

**Remember:** Always use this tool responsibly and only test networks you own or have permission to test. Happy security testing!

Keywords: arduino, captive-portal, esp32, esp32-arduino, fake-ap, joystick, littlefs, pentesting, security, ssd1306, wifi