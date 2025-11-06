# Facial Expression Dataset

## Directory Structure
dataset/
├── angry/          # 😠 Angry expression images
├── disgust/        # 🤢 Disgust expression images  
├── fear/          # 😨 Fear expression images
├── happy/         # 😊 Happy/Smile expression images
├── neutral/       # 😐 Neutral expression images
├── sad/          # 😢 Sad expression images
└── surprise/     # 😲 Surprise expression images

## How to Collect Data:
1. Run: python webcam_capture_fixed.py
2. Press 1-7 to select expression type
3. Make the facial expression
4. Press SPACE to capture image
5. Capture 50-100 images per expression for best results

## Minimum Requirements:
- 20+ images per expression for basic training
- 50+ images per expression for good accuracy
- 100+ images per expression for best results
