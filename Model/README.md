## 🛠️ Environment Setup

### Python Version
This project uses **Python 3.11**

### Create Virtual Environment
```bash
python3.11 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install tensorflow
pip install keras
pip install scikit-learn
pip install opencv-python

#To add large dataset
git lfs track "*.keras"
git lfs track "*.h5"
git lfs track "*.pt"

Keep in Git:
.ipynb
.py
README.md
Use LFS for:
.keras
.h5
.pt
NEVER push:
datasets
.venv
.DS_Store

