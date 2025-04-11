# UAV Strategic Deconfliction System

This project simulates a strategic deconfliction system for UAVs (drones) in shared airspace. It ensures a planned mission is free from spatial and temporal conflicts with other UAV trajectories.

## ✈️ Features
- Detects spatial and time-based conflicts between UAVs
- Simulates 2D and animated 4D (time-progressive) drone paths
- Modular, extensible Python structure
- Colab-compatible and real-time executable

## 📁 Project Structure
```
uav_deconfliction/
├── core/               # Conflict check logic
├── data/               # Sample missions or saved conflict reports
├── visualizations/     # Animated plots and images
├── tests/              # Unit tests
├── main.py             # Main script (ready to run)
└── README.md
```

## ▶️ How to Run
```bash
python main.py
```

Or open the included notebook: **UAV_Deconfliction.ipynb**

## 🔄 GitHub Upload Instructions
```bash
# Clone your GitHub repo (replace the URL below)
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Copy files into your repo
cp -r /mnt/data/uav_deconfliction/* .

# Add, commit and push
git add .
git commit -m "Add UAV deconfliction system"
git push origin main
```

---

Made with 💻 Python + Matplotlib
