# Organ Segmentation Project

This repository contains a Google Colab notebook (`Task.ipynb`) for organ segmentation.  
The notebook demonstrates how to load medical imaging data, run segmentation models, and visualize results in 3D

### Option 1 — Run on Google Colab
The easiest way is to open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/your-repo/blob/main/Task.ipynb)

1. Open the notebook in Colab.  
2. Run each cell step by step.  
3. If your dataset is stored on Google Drive, mount it with:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')


Option 2 — Run Locally

If you want to run it on your computer:

git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt

Then open Task.ipynb with Jupyter Notebook or Jupyter Lab


Requirements

1)Python 3.8+
2)Nibabel
3)Plotly
4)TotalSegmentator

Install them with:
  ```python
    !pip install totalsegmentator plotly nibabel
 ```

Repository Contents

1)Task.ipynb → Main Colab notebook.
2)README.md → Project description and usage guide.

Credits

1)TotalSegmentator
 for pretrained segmentation models.

2)Google Colab
 for the runtime environment.
