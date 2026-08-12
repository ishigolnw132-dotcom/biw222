# Abstract Hero AR

Browser-based Thai educational WebAR game for teaching Abstraction (แนวคิดเชิงนามธรรม).

## Run

Serve the folder over HTTPS (recommended) or from localhost. Camera access and WebXR require a secure context. Open `index.html`, allow camera permission, then press **เริ่มภารกิจ**.

## Features

- HTML5 / CSS3 / ES6
- Three.js + WebXR AR enhancement
- WebRTC `getUserMedia()` camera fallback for browser/device combinations without immersive AR
- MediaPipe Hand Landmarker live video tracking
- GSAP animation
- 5 learning levels + Chaos AI-style boss mission
- Thai explanations with Web Speech API
- Adaptive level timing based on accuracy
- Score, combo, stars, achievements, reflection and certificate
- Teacher dashboard via localStorage, CSV export, optional Google Sheets webhook
- Touch, mouse and keyboard fallbacks
- Colorblind mode and large touch targets

## Google Sheets

Set `GOOGLE_SHEETS_WEBHOOK` in `index.html` to a Google Apps Script Web App URL that accepts a POST body containing the result array.
