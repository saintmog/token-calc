# 💸 BloxFusion Token Converter

Simple and sleek desktop app that helps you convert tokens into USD based on a set rate. Designed for quick calculations and enhanced with sound effects, Discord integration, and a slick animated logo, it's perfect for users who need fast and beautiful conversions.

## 🧠 Features

- 🖥️ Desktop GUI using Tkinter  
- 🎞️ Animated logo using a GIF  
- 🔊 Sound feedback for success and errors  
- 🧮 Converts tokens to USD (at $2.10 per 1,000 tokens)  
- 🌐 Sends conversion results to a Discord webhook  
- 📦 Built to be packaged as a standalone executable with PyInstaller  

## 📸 Preview

![Animated Preview](preview.gif) <!-- Replace with actual preview GIF or screenshot if available -->

## 🛠️ Installation

### 🔧 Requirements

- Python 3.8+
- The following libraries:
  - `Pillow`
  - `requests`
  - `tkinter` (built-in)
  - `winsound` (Windows only)

Install dependencies with:

```bash
pip install pillow requests

📤 Discord Integration
Whenever a conversion is made, the app sends a message to a Discord webhook in the following format:

pgsql
Copy
Edit
💸 BloxFusion Token Conversion
100,000 tokens → $210.00 USD
To enable this, replace the DISCORD_WEBHOOK_URL at the top of the script with your own.

🔔 Sounds
success.wav – Played when a valid conversion is made

error.wav – Played on invalid input

Make sure both audio files are placed in the same directory as your script or executable.

🎨 UI Design
Dark theme with smooth font styles (Segoe UI, Consolas)

Modern, minimalistic interface with animated branding
