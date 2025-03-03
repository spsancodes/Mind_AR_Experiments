# WebAR Experiment for OLabs  

## Demo Video  
[Watch the Video](https://drive.google.com/file/d/1Wfm-NOINuB0eAEoGixyq7OgRUFwc6Nzk/view?usp=drive_link)  
MindAR Voice-Controlled AR Model  

# WebAR Experiment for OLabs  

## Project Background  
This project was initiated as part of the **OLabs Hackathon**, where our team set out to enhance **virtual science experiments using WebXR and AR technologies**. Our goal was to make online labs **more interactive and immersive**, helping students better understand scientific concepts.  

### Motivation  
Traditional online lab simulations often lack **hands-on interaction**, making it difficult for students to visualize real-world applications. Our team saw an opportunity to bridge this gap using **Augmented Reality (AR)**. By integrating WebXR, we aimed to create **an accessible, modular, and reusable WebAR framework** for OLabs experiments.  

### Challenges Faced  
🔍 **Getting WebXR to work properly** – Initially, setting up a functional WebXR environment for mobile browsers was tricky. We had to test different configurations to ensure smooth performance.  
📌 **Surface detection & object placement** – Implementing accurate AR object placement took trial and error, especially for realistic refraction simulations.  
🖼️ **Image tracking issues** – We faced difficulties with image recognition but plan to refine it further for better experiment interaction.  
⚡ **Performance optimization** – Ensuring smooth rendering while keeping AR interactions fluid required balancing resource usage and loading times.  
🎙️ **Voice recognition & QR scanning** – Integrating voice control and dynamic QR-based experiment loading needed additional APIs and fine-tuning.  

Despite these challenges, we successfully built a **WebAR-based modular framework** that allows experiments to be dynamically loaded, interactively guided, and voice-controlled—all within a **browser** without requiring external apps.  

## Features  
✅ **Step-by-step guidance** – Displays instructional overlays to guide users through the experiment.  
🧑‍🔬 **Interactive AR objects** – Users can manipulate 3D elements like prisms, lenses, and lab tools.  
📂 **Modular design** – Easily add new experiments using a JSON-based configuration.  
🎯 **Image tracking** – Detects lab apparatus and positions 3D models accordingly.  
📡 **Surface detection** – Places AR objects on real-world surfaces with accurate alignment.  
📸 **QR code scanning** – Load experiments dynamically by scanning QR codes.  
🗣️ **Voice recognition** – Enables hands-free experiment interaction using voice commands.  
🔄 **Dynamic loading** – Fetches and loads experiment data from external JSON files.  
⚡ **Performance optimized** – Efficient rendering and resource management for smooth AR experiences.  
🌍 **Cross-platform compatibility** – Works on mobile, tablets, and AR/VR headsets with WebXR support.  


## Scalability & Future Expansion  

📈 **Cloud-Hosted Experiment Library**  
- Expand the number of experiments dynamically via a cloud-based database.  
- Educators can create and upload their own AR experiments.  

🌍 **Multi-Language Support**  
- Implementing voice commands and instructions in **multiple languages**.  
- Expands accessibility for students across different regions.  

🔗 **Integration with Learning Management Systems (LMS)**  
- Seamless integration with **Google Classroom, Moodle, and Blackboard**.  
- Auto-generates experiment reports for teachers and students.  

🖥️ **PC & AR Headset Support**  
- Expanding compatibility with **HoloLens, Oculus Quest, and AR glasses**.  
- Provides a full immersive experience for high-end devices.  

🔬 **AI-Powered Experiment Analysis**  
- AI-driven insights to **predict errors in experiments** and suggest improvements.  
- Virtual teaching assistant to answer student queries in real-time.  

🚀 **Open-Source Contribution & Community-Driven Expansion**  
- Encouraging developers and educators to contribute and create new features.  
- Making it a global platform for WebAR-based science education.  

---

## Technologies Used  
- **WebXR** – Enables immersive AR/VR capabilities in the browser.  
- **Three.js** – Handles 3D rendering and object interactions.  
- **JavaScript & HTML** – Core technologies for frontend development.  
- **JSON-based configuration** – Flexible experiment setup without modifying code.  
- **Web Speech API** – Implements voice recognition for hands-free control.  
- **Zxing.js** – Used for QR code scanning functionality.  
- **Blender** – Used for creating and optimizing 3D models for AR.  
- **GLTF Formats** – Standard format for AR model storage and rendering.  

---


## Screenshots 📸  

Here are some **screenshots** showcasing the WebAR framework in action:  


| 
| **Surface Detection in Action** | ![Surface Detection](/images/AR%20(1).png) |
| **QR Code Scanning for Experiment Loading** | ![QR Code Scan](/images/QRCode.png) |
| 
| **AR Object Interaction - Prism & Refraction** | ![Prism](/images/prism1.png) |
| ![Prism](/images/prism2.png) |
| ![Prism](/images/prism3.png) |
|

## Setup Instructions  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/spsancodes/Mind_AR_Experiments
   cd Mind_AR_Experiments
