# Home Assistant Floorplan Digital Twin Demo

Welcome to the **Home Assistant Floorplan Digital Twin** demo repository!  
This project is a visual and interactive representation of a smart home using Home Assistant and an SVG-based floorplan. It complements the YouTube tutorial series that walks you through creating a digital twin dashboard from scratch.

🖼 Preview
![teaser_long-optimize](https://github.com/user-attachments/assets/e264ca39-a120-4db9-9f88-81f6fa625cca)

## 📺 YouTube Tutorial Series

🎥 Watch the full series here: [Home Assistant Floorplan Digital Twin Tutorial Playlist](https://youtube.com/playlist?list=PLI2tV0kk3Z6mVv6DB5F-khoFVal22caoB&si=aMfgwHl5MW1NNCMp)

This series covers:
- Creating and editing SVG floorplans
- Toggling lights and devices visually
- Using YAML for lovelace UI customization
- Styling with CSS for responsive and dynamic displays
- Integrating real Home Assistant entities

## 🧰 Features

- Dynamic light toggles (on/off) with SVG interactivity
- Custom CSS for visual indicators and themes
- YAML configuration for entity linking
- Layer-based SVG visibility

## 🗂️ Repo Contents

```text
/demo/
├── demo.yml        # Your dashboard file
└── demo.svg        # SVG file with an office example
└── demo.yml        # Custom styles for floorplan display

README.md
```
## 🚀 Getting Started

### 1. Install HACS and custom plugins (if needed)

Make sure you have HACS installed for enhanced custom card support. You may also want to install `card-mod`, `ha-floorplan`, or other helpers mentioned in the videos.

### 2. Upload SVG and CSS

1. Place the `demo.svg` and `demo.css` files in `/www/floorplan/demo/` in Home Assistant.
2. Copy the contents of `demo.yml` file in the dashboard raw configuration editor.
   
4. Customize
Replace entity IDs in the YAML config to match your actual devices:

📦 Example Entitie Used
Lights (light.*)

📄 License
MIT License. Feel free to use and adapt this project for your own smart home.

🙌 Credits
Created by [Tinker Tut](https://www.youtube.com/@tinker_tut)
Follow the YouTube series for a step-by-step guide!
