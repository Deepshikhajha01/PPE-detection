# PPE-detection
Real-time helmet/PPE detection using YOLOv8 - trained on custom dataset with deployment-ready inference pipeline
DATASET LINK https://app.roboflow.com/deepshikha-jha/helmet-detection-j7vt9-9nfop/1
installation process
## Installation

1. Repository clone karo:
   \`\`\`bash
   git clone https://github.com/Deepshikhajha01/PPE-detection.git
   cd PPE-detection
   \`\`\`

2. Required libraries install karo:
   \`\`\`bash
   pip install ultralytics opencv-python roboflow
   \`\`\`

3. Trained model se prediction chalao:
   \`\`\`python
   from ultralytics import YOLO

   model = YOLO("best.pt")
   results = model("path/to/your/image.jpg")
   <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/28d8fb62-7066-4fe5-bda2-48610d1f7bcf" />

