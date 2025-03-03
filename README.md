# WebAR Experiment for OLabs  

## Demo Video  
[Watch the Video](https://drive.google.com/file/d/1Wfm-NOINuB0eAEoGixyq7OgRUFwc6Nzk/view?usp=drive_link)  
MindAR Voice-Controlled AR Model  

# WebAR Experiment for OLabs  

## Project Background  
This project was initiated as part of the **OLabs Hackathon**, where our team sett out to enhance **virtual science experiments using WebXR and AR technologies**. Our goal was to make online labs **more interactive and immersive**, helping students better understand scientific concepts.  

### Motivation  
Traditional online lab simulations often lack **hands-on interaction**, making it difficult for students to visualize real-world applications. Our team saw an opportunity to bridge this gap using **Augmented Reality (AR)**. By integrating WebXR, we aimed to create **an accessible, modular, and reusable WebAR framework** for OLabs experiments.  

### Challenges Faced   
📌 **Surface detection & object placement** – Implementing accurate AR object placement took trial and error, especially for realistic refraction simulations.  
🖼️ **Image tracking issues** – We faced difficulties with image recognition but plan to refine it further for better experiment interaction.  
⚡ **Performance optimization** – Ensuring smooth rendering while keeping AR interactions fluid required balancing resource usage and loading times.  
🎙️ **Voice recognition & QR scanning** – Integrating voice control and dynamic QR-based experiment loading needed additional APIs and fine-tuning.  

Despite these challenges, we successfully built a **WebAR-based website** that allows experiments to be dynamically loaded, interactively guided, and voice-controlled—all within a **browser** without requiring external apps.  

## Features  
  
🧑‍🔬 **Interactive AR objects** – Users can manipulate 3D elements like prisms, lenses, and lab tools.  
📂 **Modular design** – Easily add new experiments using a JSON-based configuration.  
🎯 **Image tracking** – Detects lab apparatus and positions 3D models accordingly.  
📡 **Surface detection** – Places AR objects on real-world surfaces with accurate alignment.  
📸 **QR code scanning** – Load experiments dynamically by scanning QR codes.  
🗣️ **Voice recognition** – Enables hands-free experiment interaction using voice commands.  
🔄 **Dynamic loading** – Fetches and loads experiment data from external JSON files.  
⚡ **Performance optimized** – Efficient rendering and resource management for smooth AR experiences.  
🌍 **Cross-platform compatibility** – Works on mobile, tablets, and AR/VR headsets with WebXR support.  

## Hosting & Local Development  

### Running a Local Server with Python  
To test WebXR applications locally, we used Python’s built-in HTTP server to host the files.  
Run the following command in your project directory:  

**python -m http.server 8000**

This starts a simple HTTP server on localhost:8000. You can then access your project in a browser at:

**http://localhost:8000**

## Using ngrok for Public Access
Since localhost is only accessible on your device, we used ngrok to create a public URL for testing WebXR on mobile devices.

Get the public URL from the ngrok output and open it on your mobile device or share it with teammates for remote testing.




## Scalability & Future Expansion  

📈 **Cloud-Hosted Experiment Library**  
- Expand the number of experiments dynamically via a cloud-based database.  
- Educators can create and upload their own AR experiments.  

🌍 **Multi-Language Support**  
- Implementing voice commands and instructions in **multiple languages**.  
- Expands accessibility for students across different regions.  

🖥️ **PC & AR Headset Support**  
- Expanding compatibility with **HoloLens, Oculus Quest, and AR glasses**.  
- Provides a full immersive experience for high-end devices.  

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


## Augumented Reality

 ![Surface Detection](/images/AR%20(1).png) 
 ![QR Code Scan](/images/QRCode.png) 

 ## Prism Model

 ![Prism](/images/prism1.png) 
 ![Prism](/images/prism2.png) 
 ![Prism](/images/prism3.png) 


## Setup Instructions  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/spsancodes/Mind_AR_Experiments
   cd Mind_AR_Experiments

## Acknowledgments 🙌
Would like thank the following individuals and resources for their valuable contributions:  

- 👨‍💻 **[Teammate 1](https://github.com/Garudan014)**
- 👨‍💻 **[Teammate 2](https://github.com/Yadi-codes)**
- 👨‍💻 **[Teammate 3](https://github.com/)**

### Miscelleneous
- |**Mentors in the Hackathon**|
- |**University Advisors and professors**|
- |**[Mr. Pratyaksh](https://github.com/LoneWolf4713)**|


