# ristau_berton_huang_meneses_w207_final_project

This is our project on music classification - to identify musical ensembles of a song using MusicNet Classicial Music Dataset.

We have four folders in this repo:

- data folder: 
  - Features we extracted from the wav and midi files were exported to csv and saved in this folder 
  - Wav, Midi, Metadata, NPZ Files dataset (21 Gigabytes) can be found at this <a href="https://www.kaggle.com/imsparsh/musicnet-dataset/code">kaggle link</a> and in <a href="https://drive.google.com/drive/u/1/folders/1f4AakoH7RQ51WqieexWNDDhywJ0sH3vC">our google drive link </a>.
  - EDA Plots done in google collab were saved in both google drive and github. Not all the plots could not be done in github due to 21gb data size.

- scripts folder:
  - Data Preprocessing : Extraction and Feature Engineering
    - 3 Datasets were created :                    
      - MIDI Features only : Feature Engineering Performed 
      - Spectral Features from Wav Files
      - Wav and MIDI combined
              
  - Exploratory Data Analysis : Distribution and Correlations 
    - Link to <a href="https://colab.research.google.com/drive/1xwEuh2z3gEDekdTmc5qNzagcIhIRpBBl?authuser=1#scrollTo=qZgc6bu8FFVi"> Google Collab EDA File </a> : This runs the EDA on larger files saved in google drive. Please contact Ziling Huang if you are a grader and need access to mount the google drive and the google collab file. Instructor Cornelia Ilin has been given access.
    - Exploratory Data Analysis.ipynb saved in github. You can view the same code here as well but some of the code only runs in google collab.
    - NPZ Data Exploration
    - WAV files Exploration
    - MetaData Exploration
    - MIDI Data Exploration

  - Models :
    - Naive Bayes (Baseline)
    - Decision Tree
    - Logistic Regression
    - Random Forest
    - Support Vector Machines
    - Neural Network

- output folder:

- literature folder:
