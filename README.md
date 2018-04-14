[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

[<img src="https://avatars1.githubusercontent.com/u/36938641?s=200&u=b2d470fe66acc157d8ca8cb3fb815dee47d4466d&v=4" align="right" />](https://github.com/machine-learning-experiments)

# Bicycle sharing system forecast
This project use a neural network to predict daily bike rental ridership.
> See the [jupyter notebook](https://github.com/machine-learning-experiments/bicycle-sharing-forecast/blob/master/bicycle_sharing_neural_network.ipynb)

### Motivation

Implement the backpropagation algorithm for a neural network.

### Built With

- [Python 3](https://www.python.org/download/releases/3.0/) - Language
- [Anaconda](https://www.anaconda.com/what-is-anaconda/) - Python Data Science Platform 
- [Jupyter notebook](http://jupyter.org/) - Web application that allows to create documents that contain live code

### Dataset

The core data set is related to  the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data.
> For more information read [this](https://github.com/machine-learning-experiments/bicycle-sharing-forecast/tree/master/Bike-Sharing-Dataset)

## Getting Started

### Prerequisites
1. Download and install [Anaconda](https://www.anaconda.com/download/)
2. Update Anaconda
> ``` 
> $ conda upgrade conda 
> $ conda upgrade --all 
> ```

### Install

1. Clone and enter into the project's root directory by command line
> ``` 
> $ git clone https://github.com/machine-learning-experiments/bicycle-sharing-forecast.git
> ```
2. Create and activate enviroment
> ``` 
> $ conda env create -f enviroment.yaml 
> $ conda activate bicycle-sharing-forecast 
> ```
or
> ``` 
> conda create --name bicycle-sharing-forecast python=3
> source activate bicycle-sharing-forecast
> conda install numpy matplotlib pandas jupyter notebook
> ```
3. Start jupyter notebook
> ``` 
> $ jupyter notebook 
> ```
4. Your browser will open showing a list of files, click on the  [bicycle_sharing_neural_network.ipynb](https://github.com/machine-learning-experiments/bicycle-sharing-forecast/blob/master/bicycle_sharing_neural_network.ipynb) notebook file

## Author

[Lorival Smolski Chapuis](https://github.com/lorival)
> This project was developed during the [deep-learning](https://br.udacity.com/course/deep-learning-nanodegree-foundation--nd101) nanodegree from [Udacity](https://br.udacity.com/) 

