July 11th 2020 - Update Research Article -  Aritificial Intelligence for damage detection 

# Deep learning for damage detection

Go to https://leonelbianchi.github.io/27/12/2020/project-deep-learning-for-damage-detection to see the article associated with this repository.

Fields: AI, Civil Engineering, Deep Learning, Machine Learning, Structural Health Monitoring, Technology

*Summary: Deep learning model that takes dynamic properties of the structure (in this case a pedestrian bridge) as input to predict in which area of the structure there is damage (simulated as a decrease in its rigidity). This allows remote and rapid monitoring of structures at low computational cost.*

# Abstract

The objetive of this project is to create a software based on a deep neural networks to identify damages in civil and mechanical engineering structures. This software allow a continuous and fast remote monitoring of structures and buildings at a low economic and computational cost. To have a first aproximation of the model, we will use a pedestrian bridge and see how the model works. The supervised learning algorithm consists in 40,000 cases of damage events to train the model. The input of each event consists of natural frequencies and first mode of vibration of this particular structure with its random damage assigned to a particular element of the bridge. The output of each event consists in the percentage reduction of the stiffness of the element (this reduction is the hypothesis used as simulation of the damage).

# Files

```bash
- Neural Network Rev1.py (script using python that generates a .csv file used as input in the neural network script)
- Damage Creation.py (script using python and libraries (Keras, Scikit-Learn, Numpy, Matplotlib, Pandas) that reads the .csv file and generates a .csv file that predicts wich beam is damaged)
- input_pasarela4.csv
- test1.csv
```

# Libraries to install

Then,
```bash
pip install tweepy
pip install pandas
pip install numpy
pip install tensorflow
pip install keras
pip install matplotlib
```
