
---

## 🧠 `report.md` (Human + Hacker Friendly)

## 🎯 Objective
To re-identify players in a single-camera 15-second sports video, even if they go out of frame and reappear — maintaining consistent player IDs throughout.

## 🧠 Approach
- Used YOLOv11 for player detection (model provided by Liat.ai).
- Developed a custom tracker using:
  - Bounding box IoU
  - Centroid distance
  - Memory buffer for temporarily lost players
- Tracked and annotated player IDs in real-time across frames.

## 🧪 Techniques Explored
- IoU-only matching (too unstable)
- Added centroid proximity check (improved re-ID)
- Explored Deep SORT, but prioritized simplicity for short clip

## ⚠️ Challenges
- Jittery IDs with only IoU
- Reappearance after occlusion
- Varying bounding boxes due to camera shake

## 💡 Improvements If Extended
- Integrate Deep SORT with Kalman filter and appearance embeddings
- Use OCR for jersey number-based re-ID
- Add a web-based playback demo (Streamlit or Gradio)

---

## 🗂️ Submission Format
- GitHub repo: https://github.com/yourusername/player-reid-liatai
- Or Google Drive folder: https://drive.google.com/your-folder

