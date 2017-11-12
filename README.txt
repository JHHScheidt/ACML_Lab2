The Main.py class is the main class in this project. It will run a RNN and trains according to a given dataset.
The dataset on which the training should be performed has to be a text file, and should be inserted in the "data" folder.
Once this dataset has been added, go to the main class and change the DATA object in line 13 to match the name of the added data.
In the first run, the model will be created and saved to the "models" folder. Afterwards, the models will be loaded and reused for prediction if the dataset has already been used.