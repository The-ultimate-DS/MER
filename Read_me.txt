Music Emotion Recognition (MER)
This repository contains code for a Music Emotion Recognition (MER) project.  The code is developed and tested on Google Colab; some minor adjustments are necessary for running it locally.


Requirements -

numpy==1.23.5
pandas==1.5.3
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.2.2
tensorflow==2.13.0
xgboost==1.7.5
librosa==0.10.0
kymatio==0.3.2


How to Run

1. Upload Files to Google Drive

Upload the 162 audio files (Corpus-Audio-162) to a folder in your Google Drive. 

Upload the MER-Audio-dataset.xlsx file to your Google Drive.

2.  Mount Google Drive in Colab, run the importing code as provided.

3. Update File Paths to your location on the drive for 
audio_path
metadata_path

4. Run each cell in the notebook sequentially.


* Ensure all files are correctly loaded and paths are set according to your Google Drive directory.
* Dependencies: Make sure all Python packages are installed as required.
* File Paths: Double-check all file paths to ensure they are correctly set.