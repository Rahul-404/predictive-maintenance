# Predictive Maintenance on NASA Turbojet Engine Dataset 🛠️🔍
---
## Overview ℹ️
This project aims to implement predictive maintenance techniques on the NASA Turbojet Engine Dataset. Predictive maintenance involves monitoring the condition of equipment to predict when maintenance should be performed. By analyzing historical data from turbojet engines, we aim to develop models that can predict the remaining useful life (RUL) of these engines, allowing for proactive maintenance and minimizing downtime.

## Dataset 📊
The NASA Turbojet Engine Dataset contains sensor readings from different sensors attached to turbojet engines. Each row in the dataset represents a snapshot of the engine's condition at a specific point in time. The dataset includes features such as temperature, pressure, and other operational parameters, along with the corresponding remaining cycles until failure.

The dataset is available from the [NASA Prognostics Center of Excellence](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan). It includes training and testing sets, where the training set contains multiple operational cycles for each engine, while the testing set only contains the initial conditions and actual RUL values.

## Project Structure 📂
- `data/`: Directory to store the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration, feature engineering, model training, and evaluation.
- `models/`: Saved models after training.
- `results/`: Results and evaluation metrics.
- `README.md`: This file, providing an overview of the project.

## Setup ⚙️
To run the project, you need Python 3.x and the following libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- jupyter

You can install these dependencies using pip:

```
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

## Usage 🚀
1. Download the NASA Turbojet Engine Dataset from the provided link.
2. Place the dataset files in the `data/` directory.
3. Open and run the Jupyter notebooks in the `notebooks/` directory sequentially. These notebooks cover data preprocessing, feature engineering, model training, and evaluation.
4. After training the models, evaluate their performance using the provided evaluation metrics.
5. Experiment with different models, hyperparameters, and feature engineering techniques to improve performance.

## Results 📊
The project aims to achieve the following outcomes:
- Develop predictive maintenance models capable of accurately predicting the remaining useful life of turbojet engines.
- Evaluate the performance of the models using appropriate evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.
- Compare the performance of different models and feature engineering techniques to identify the most effective approach.

## License 📜
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
