# Original AIML Practicals

This repository contains the four original Jupyter notebooks supplied for the practical work. The notebook files are copied without changing their contents or renaming them.

## Files

- `cv.1(1).ipynb` — Image Processing Pipeline Implementation
- `cv.2(1).ipynb` — Edge, Corner, Blob Detection and Feature Matching
- `dl.1(1).ipynb` — Diabetes Prediction and Student Performance Prediction
- `dl.2(1).ipynb` — Regularization and Normalization
- `requirements.txt` — Python libraries used by the notebooks

## Input files expected by the original notebooks

The notebook code uses relative paths, so keep these input files in the repository root (the same folder as the notebooks):

- `image.jpg`
- `image1.png`
- `image2.png`
- `diabetes.csv`
- `Student_Performance.csv`
- `Breast_Cancer_Dataset.csv`

The original notebook files refer to the following dataset locations:

- Diabetes: https://github.com/shekharkumar1412-cpu/Teaching_Content/blob/main/MCA_Rungta/DL/Practice_Problems/diabetes.csv
- Student Performance: https://github.com/shekharkumar1412-cpu/Teaching_Content/blob/main/MCA_Rungta/DL/Practice_Problems/Student_Performance.csv
- Breast Cancer: https://github.com/shekharkumar1412-cpu/Teaching_Content/blob/main/MCA_Rungta/DL/Practice_Problems/Breast_Cancer_Dataset.csv

The image files are referenced by the CV notebooks but were not part of the four notebook files supplied in this chat. Add the exact images you intend to use with the filenames above before running those notebooks. Dataset CSV files should likewise be downloaded from the original links above and placed in this folder. No substitute datasets or images have been added.

## Setup in VS Code (Windows)

Install Python 3.11 (64-bit), then open this folder in VS Code. Install the Microsoft **Python** and **Jupyter** extensions. In the VS Code terminal, run these commands one at a time:

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name original-aiml-practicals --display-name "Python (Original AIML Practicals)"
```

Open a notebook, select the `Python (Original AIML Practicals)` kernel, and run cells in order.

## Upload to GitHub

Create a new GitHub repository, then upload the contents of this folder. Do not upload the `.venv` directory.
