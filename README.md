**Project: Predicting Boston Housing Prices**

**Install**
This project requires Python and the following Python libraries installed:

NumPy
Pandas
Mediapipe
matplotlib
scikit-learn
You will also need to have software installed to run and execute a Visual Studio Code.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

**Code**
Template code is provided in the daat_collection.py notebook file.Execute it to allow the device to collect your dataset via landmark points. Sample of the same is provided as of now in the labels.npy file. You will also be required to use the included daat_training.py Python file to train your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in inference.py is meant to draw prediction on the model thus created.

**Run**
In a terminal or command window, navigate to the top-level project directory inference.py

python data_collection.py
python training.py
python inference.py


**jupyter lab**
This will open the Jupyter Notebook software and project file in your browser.

**Data**
Dataset has been collected using the data_collection.py file using the mediapipe library with 
face landmarks=468
hand landmarks=21 for each hand
The dataset consists of 15 data samples, with each datapoint having 100 frames per second. 

