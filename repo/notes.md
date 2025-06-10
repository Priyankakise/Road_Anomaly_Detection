# 📓 Project Notes

## Overview
This file contains notes and helpful information used during development and testing of the Road Defect Detection system using YOLOv8.

---

## 💡 Development Highlights

- **Model Used**: YOLOv8 (custom-trained)
- **Detected Classes**: Lane mark, Plain road, Manhole, Divider, Speed bumps, Cracks, Pothole, Zebra crossing, Footpath, Rumble strips, Sign board, Leading lines

---

## 📁 Folder Breakdown

- `images/labels`: YOLO-format dataset
- `scripts/`: All core code for prediction, frame processing, CSV generation, and visualization
- `runs/`: YOLO inference outputs (auto-generated)
- `csv files`: Contains final defect summary reports

---

## 🧪 Testing Notes

- Used test videos from GPS-enabled camera app
- Verified frame-wise detection and summary CSV generation
- Annotated outputs visually verified

---

## 🔁 Feedback/Improvement Ideas

- Add a feedback loop to manually tag missed defects and retrain
- Auto-flag "Unknown" or low-confidence frames for review
- Integrate map-based visual dashboard using folium or streamlit

---

*Last updated: June 2025*
