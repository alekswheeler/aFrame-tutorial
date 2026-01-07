
# WebXR Demo — A-Frame & AR.js

This repository contains two WebXR experiments built with **A-Frame** and **AR.js**, focusing on **VR visualization** and **marker-based Augmented Reality**, with special attention to **mobile experience**.

The goal of this project is to explore how immersive 3D and AR experiences can be delivered directly in the browser, without native apps, while maintaining good usability on smartphones.

---

## About A-Frame and AR.js

### A-Frame

[A-Frame](https://aframe.io/) is a web framework for building **3D, VR, and AR experiences** using HTML.  
It is built on top of **Three.js** and follows an **Entity–Component–System (ECS)** architecture, making it easy to create and manipulate 3D scenes declaratively.

A-Frame handles:

- 3D scenes and objects
    
- Cameras and lighting
    
- User interaction
    
- Desktop and mobile rendering
    
- WebXR integration
    

---

### AR.js

[AR.js](https://ar-js-org.github.io/AR.js/) is a lightweight library for **Web-based Augmented Reality**.  
When combined with A-Frame, it enables AR experiences such as **marker-based tracking** directly in the browser, using the device camera.

AR.js provides:

- Marker-based AR (Hiro, Kanji, custom markers)
    
- Image tracking (NFT)
    
- Mobile-friendly performance
    
- No app installation required
    

> In this project, AR.js is used **on top of A-Frame**, meaning all 3D logic still relies on A-Frame components.

---

## Project Structure

This project contains **two separate pages**, each showcasing a different type of immersive experience.

---

## 1️⃣ VR Container Visualization (A-Frame)

This page is a **VR / 3D visualization** of a shipping container.

### Purpose

- Allow users to explore a 3D container model
- Optimize the experience for **mobile devices**
    
### Features

- Mobile-friendly camera controls
    
- Touch-based or button-based navigation
    
- Gyroscope-based look controls
    
- Works on desktop and mobile browsers
    
### 🔗 [Demo Link](https://alekswheeler.github.io/aFrame-tutorial/vr/)

---

## 2️⃣ Marker-Based AR Experience (AR.js + A-Frame)

This page demonstrates a **marker-based Augmented Reality** experience using AR.js.

### Purpose

- Display a 3D object anchored to a physical marker
- Explore pose estimation and tracking behavior
- Understand the limitations and strengths of marker-based AR
    

### How It Works

- The camera detects a predefined marker
    
- A 3D object is rendered relative to the marker
    
- The object appears fixed in space as long as the marker is visible
    

### 🖼️ [Marker Image](https://raw.githubusercontent.com/alekswheeler/aFrame-tutorial/refs/heads/main/ar/card.png)

### 🔗 [Demo Link](https://alekswheeler.github.io/aFrame-tutorial/vr/)

---

## Learn More

If you want to dive deeper into the technologies used in this project, check out the resources below.

### A-Frame

- Official Website: [https://aframe.io/](https://aframe.io/)
    
- Documentation: [https://aframe.io/docs/](https://aframe.io/docs/)

### AR.js

- Official Website: [https://ar-js-org.github.io/AR.js/](https://ar-js-org.github.io/AR.js/)
- Documentation: [https://ar-js-org.github.io/AR.js-Docs/](https://ar-js-org.github.io/AR.js-Docs/)

These tools are a great starting point for anyone interested in **WebXR, WebAR, and browser-based 3D experiences**.

---

## Notes

- All experiences run **directly in the browser**
    
- No native app installation required
    
- Best experienced on modern mobile devices with camera and gyroscope support
    
- Marker-based AR depends on lighting conditions and marker visibility
    
