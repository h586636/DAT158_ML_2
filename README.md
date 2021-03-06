# DAT158_ML_2
- We chose to work with the Box Office Prediction dataset found here: https://www.kaggle.com/c/tmdb-box-office-prediction

## Installations
- Anaconda: https://docs.anaconda.com/anaconda/install/windows/
- Anaconda pandas install: https://anaconda.org/anaconda/pandas
- Anaconda numpy install: https://anaconda.org/anaconda/numpy
- Anaconda pycaret install: https://anaconda.org/conda-forge/pycaret
- Anaconda pathlib install: https://anaconda.org/anaconda/pathlib
- Anaconda streamlit install: https://anaconda.org/conda-forge/streamlit
- All the extensions can also be installed using pip by simply typing `pip install exstensionname` while in your Anaconda environment prompt
- If you do not have pip you can download it here: https://pip.pypa.io/en/stable/installation/

## Running on localhost using Anaconda
- Make an Anaconda environment
- Make sure your environment contains numpy, pycaret, streamlit, pandas and pathlib
- Clone project into the folder Anaconda defaults to and name the folder DAT158_ML_2
- Run Anaconda and go to your environment
- Navigate to the project source folder using the command `cd DAT158_ML_2/src`
- Run the command `streamlit run boxofficeapp.py`
- The app should open in your default browser. If not the link address is printed in the Anaconda prompt

## Running the deployed app
- The deployed app can be found here: https://share.streamlit.io/h586636/dat158_ml_2/main/src/boxofficeapp.py

## Using the app
- Input the data you have into the correct fields
- If you do not have data for all fields you can leave them empty
- Click the "Predict" button at the bottom of your window
- You now have a prediction of your movie's revenue
