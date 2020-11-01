# Pulmonary Fibrosis Prediction

# Introduction




# Getting Started 

```
git clone https://github.com/VeronicaLoy/pulmonary_fibrosis_progression.git

cd pulmonary-fibrosis-progression

conda create -n fibrosis python=3.6.7
conda activate fibrosis
pip install -r requirements.txt

streamlit run app.py
```
The app requires patient details to be indicated, and a zip folder containing CT scans of patients lungs in to be uploaded before prediction. The CT scans has to be in .dcm format. A sample of this zip folder of .dcm images can be found under `sample dataset` folder.
Administrator privilages may be required to run the app. This can be done by running Anaconda prompt as an administrator on Windows.

# About the model