**Project: Predicting Boston Housing Prices**<br>

**Install**<br>
This project requires Python and the following Python libraries installed:<br>

NumPy<br>
Pandas<br>
Mediapipe<br>
matplotlib<br>
scikit-learn<br>
You will also need to have software installed to run and execute a Visual Studio Code.<br>

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.<br>

**Code**<br>
Template code is provided in the daat_collection.py notebook file.Execute it to allow the device to collect your dataset via landmark points. Sample of the same is provided as of now in the labels.npy file. You will also be required to use the included daat_training.py Python file to train your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in inference.py is meant to draw prediction on the model thus created.<br>

**Run**<br>
In a terminal or command window, navigate to the top-level project directory inference.py<br>

python data_collection.py<br>
python training.py<br>
python inference.py<br>


**jupyter lab**<br>
This will open the Jupyter Notebook software and project file in your browser.<br>

**Data**<br>
Dataset has been collected using the data_collection.py file using the mediapipe library with: <br>
face landmarks=468<br>
hand landmarks=21 for each hand<br>
The dataset consists of 15 data samples, with each datapoint having 100 frames per second. 

