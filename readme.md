July 11th 2020 - Update Research Article -  Aritificial Intelligence for damage detection 

# Deep learning for damage detection

Go to https://leonelbianchi.github.io/27/12/2020/project-deep-learning-for-damage-detection to see the article associated with this repository.

Fields: AI, Civil Engineering, Deep Learning, Machine Learning, Structural Health Monitoring, Technology

*Summary: Deep learning model that takes dynamic properties of the structure (in this case a pedestrian bridge) as input to predict in which area of the structure there is damage (simulated as a decrease in its rigidity). This allows remote and rapid monitoring of structures at low computational cost.*

# Files

- Neural Network Rev1.py (script using python that generates a .csv file used as input in the neural network script)
- Damage Creation.py (script using python and libraries (Keras, Scikit-Learn, Numpy, Matplotlib, Pandas) that reads the .csv file and generates a .csv file that predicts wich beam is damaged)
- input_pasarela4.csv
- test1.csv

# Libraries to install

Go to the directory in cmd.

Use an -env (using Anaconda environments, for example) 
	conda activate env_name

Then,

tensorflow 
	$ pip install tensorflow<br><br>
keras 
	$ pip install keras<br><br>
pandas 
	$ pip install pandas<br><br>
numpy 
	$ pip install numpy<br><br>
matplotlib 
	$ pip install matplotlib<br><br>
