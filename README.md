📝 Manuscript Damage Detection and Percentage Calculation using Deep Learning

📌 Project Overview

This project aims to detect damaged regions in historical manuscript images and calculate the damage percentage using Deep Learning (U-Net) and Computer Vision (OpenCV) techniques.
The system identifies common types of manuscript damage such as stains, tears, fungal marks, and ink fading, segments the affected areas, and generates a post-processing damage percentage report for restoration and preservation purposes.
This work contributes to digital preservation, historical document analysis, and supports cultural heritage conservation using AI.

⸻

🎯 Problem Statement

Historical manuscripts often suffer from physical damage due to aging, environmental conditions, and improper storage.
Manual inspection is time-consuming, subjective, and inaccurate, especially when measuring the extent of damage.
The challenge was to develop an AI-powered automated method that can:

✔ Detect damaged regions from manuscript images
✔ Segment damage with pixel-level accuracy
✔ Calculate accurate damage percentage
✔ Classify different types of damage (faded, torn, fungal, stained)

⸻

🚀 Proposed Solution

To solve this, we developed a Deep Learning-based damage segmentation pipeline using:

🧠 U-Net CNN architecture trained on annotated manuscript damage dataset
⚙️ Custom loss functions (Dice Loss + Focal Loss) to handle class imbalance
🖼️ OpenCV post-processing to detect damaged area contours
📊 Area measurement using image masks to compute damage percentage
📤 Final output: Image with damage mask + percentage damage report

         Input Image
              │
              ▼
        Data Preprocessing
              │
              ▼
         U-Net Model
      (Segmentation Mask)
              │
              ▼
   Post-processing (OpenCV)
   │   └─ Contour Detection
   │   └─ Pixel Area Calculation
              │
              ▼
   Damage Percentage Report

   📚 Future Enhancements

🔹 Multi-class damage classification (faded, torn, stained)
🔹 Real-time manuscript restoration suggestions (AI-based repair)
🔹 Deploy as a Web App using Streamlit/Flask
🔹 Integrate Vision Transformers (ViT) for better segmentation

⸻

🙌 Contribution

Contributions are welcome! Fork this repo, raise issues, and submit PRs.

⸻

✍️ Author

👤 Your Name
📧 ravitejaammati@gmail.com

