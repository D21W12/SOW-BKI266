# Explainable AI (SOW-BKI266)

> 🎓 This repository contains my course work for **Explainable AI** (SOW-BKI266)

---

Contributions in this repository are made by **Daan Wichmann**.

### Installation

1. Move to a destined location in your file system and clone the repository:

```
git clone https://github.com/D21W12/SOW-BKI266.git
```

2. Create a virtual environment

```
python -m venv .venv
```
3. Activate the virtual environment

```python
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # MacOS/Linux
```

4. Install all required dependencies from `requirements.txt`:
```
pip install -r requirements.txt
```

If installing via the following command doesn't work, please try the following command installing all required libraries:

```
pip install notebook torch torchvision
```

5. Download dataset (cell included at the top of each notebook)

```
curl -L -o ./data.zip https://www.kaggle.com/api/v1/datasets/download/navoneel/brain-mri-images-for-brain-tumor-detection
unzip -d ./data ./data.zip
```

If the following commands don't work, please manually download the data from [kaggle (click here)](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection), and place it in `"Final Assignment"/data`.