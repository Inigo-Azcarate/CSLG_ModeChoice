- `pre_model.ipynb` adds noise to survey data, assigns origin and destination to each trip, and calculates the travel time for each mode of transportation.
- `training_model.ipynb` reads the output file from `pre_model.ipynb` and trains the supervised learning AI model.
- `predict_().ipynb` are predicting codes that use the aforementioned AI model (Random Forest Classifier) to predict different scenarios.

Notes: 
- To run `pre_model.ipynb` you will need a GOOGLE API key to download data from the *distancematrix* API.
- If you are having trouble running `pre_model.ipynb`, download the following folder and paste it on the \model directory.
