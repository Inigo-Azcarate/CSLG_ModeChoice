**Mobility mode choice model using Gipuzkoa (Spain) as a use case**

# Folders
- [input_data](https://github.com/Inigo-Azcarate/CSLG_ModeChoice/tree/main/input_data) contains all the data necessary to run the AI model in the \model folder. Most data is generated after running the code in the \preprocessing folder. If you are having any kind of problem, you can download the file with all the data to run the model on [this](https://drive.google.com/drive/folders/13uN8kvLhV2v1BW2bOM5owNVi9Ct8cwQv?usp=sharing) link.
- [model](https://github.com/Inigo-Azcarate/CSLG_ModeChoice/tree/main/model) contains the code to create the supervised learning AI model that predicts the mobility choices. 
- [preprocessing](https://github.com/Inigo-Azcarate/CSLG_ModeChoice/tree/main/preprocessing) contains the code to generate the files in \input_data.

Each directory contains a brief guide explaining the functionality of that particular folder.

# Make the model work

<img src="/images/work_flow.png" width="700" />

1. Download (clone) the repo on your own computer.

2. a) [long version]  Download raw_data folder from [this](https://drive.google.com/drive/folders/15Tvs44dEeYGiAhtrJAkiMDmLhnPeNjkB?usp=sharing) link and paste it on your \preprocessing folder. Afterwards, run the code on \preprocessing on the order shown on its [README](https://github.com/Inigo-Azcarate/CSLG_ModeChoice/tree/main/preprocessing) to generate the input_data.  
   b) [short version] Download the full input_data folder [here](https://drive.google.com/drive/folders/13uN8kvLhV2v1BW2bOM5owNVi9Ct8cwQv?usp=sharing) so you don't need to run the code in \preprocessing.

3. a) [long version]  Run `pre_model.ipynb` and `training_model.ipynb` in that order to generate the machine learning model.  
   b) [short version] Download the results folder from [this](https://drive.google.com/drive/folders/1FFE9koNYpAtOD4vMElMvnr7FvtkDbeBl?usp=sharing) link and paste it inside \model. You can then directly run `training_model.ipynb` to generate the machine learning model.

4. Use the model that is saved on \models directory on \model to predict mobility mode choices in different scenarios. 



