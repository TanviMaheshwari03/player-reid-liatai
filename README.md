# player-reid-liatai
# 🏟️ Player Re-Identification in Sports Footage | Liat.ai Assignment

This project tracks and re-identifies players in a sports video, ensuring consistent player IDs even when they leave and re-enter the frame — simulating real-time re-ID in broadcast scenarios.

### 🧠 Task Chosen
**Option 2**: Re-identification in a Single Feed (15s video, YOLOv11)

---

## 🛠️ Setup Instructions (Colab Recommended)

> No local install needed! Just open and run the notebook in Google Colab.

Or, for local runs:


📂 File Structure
main.ipynb: End-to-end Colab notebook with all steps

tracker.py: Custom tracker using IoU + centroid logic

yolov11.pt: Pretrained model for player detection

output_reid.mp4: Final result with consistent IDs

report.md: Approach + methodology + insights

🔍 Sample Output

<img width="515" height="321" alt="image" src="https://github.com/user-attachments/assets/9fa91110-ef65-4fdc-b4c3-ecb488c6cba8" />

📊 Key Features
✅ YOLOv11-based player detection
✅ Custom ID tracker with IoU + centroid matching
✅ Robust to short occlusions and re-entries
✅ 100% portable — runs in Colab

