# Room Occupancy Estimation

This project aims to estimate the number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2, and PIR.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Models Used](#models-used)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
This project uses various machine learning algorithms to estimate room occupancy based on sensor data. The dataset includes readings from temperature sensors, light sensors, sound sensors, CO2 sensors, and Passive Infrared (PIR) sensors. The goal is to predict the number of occupants in a room (0 to 3).

## Project Structure
room-occupancy/
├── data/
│ └── data.csv
├── notebooks/
│ └── analysis.ipynb
├── README.md
└── requirements.txt

- **data/**: Contains the dataset.
- **notebooks/**: Contains Jupyter notebook containing everything I have coded in the project.
- **README.md**: This file.
- **requirements.txt**: Lists all the dependencies.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/tanishk-ou/room-occupancy.git
   cd room-occupancy
2. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install the required packages:
   pip install -r requirements.txt

## Usage
Open the Jupyter notebook for analysis:

jupyter notebook notebooks/RoomOccupancyModel.ipynb


## Models Used
K-Means Clustering: For unsupervised learning and pattern recognition.
Logistic Regression: For predicting categorical outcomes.
Gradient Boosting: For improving accuracy through boosting techniques.
Random Forest: For robust classification using an ensemble of decision trees.

## Results
Our models achieved the following accuracies on the test set:

K-Means Clustering: 81.23%
Logistic Regression: 99.26%
Gradient Boosting: 99.63%
Random Forest: 99.85%
The Random Forest model provided the best performance with an accuracy of 99.85%. The detailed analysis and visualizations can be found in the Jupyter notebook (notebooks/RoomOccupancyModel.ipynb).

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.

