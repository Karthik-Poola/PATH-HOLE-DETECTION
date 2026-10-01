# Pothole Guard AI API

Production backend for pothole detection, GPS mapping, duplicate handling and RTO reporting.

## Render
- Build: npm install
- Start: npm start
- Health: /health

The YOLOv8 ONNX model is downloaded from Hugging Face on first detection, so the model binary does not need to be committed to GitHub.

RTO recipient is configured with RTO_EMAIL and is currently intended to be kp288885@gmail.com.
