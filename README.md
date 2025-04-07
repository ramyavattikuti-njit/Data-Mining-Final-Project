# Data-Mining-Final-Project

You can read the data using below code in python.
!pip install ucimlrepo
from ucimlrepo import fetch_ucirepo
import pandas as pd

# Fetch the Heart Disease dataset (ID 45 in UCI repository)
heart_disease = fetch_ucirepo(id=45)
X = heart_disease.data.features
y = heart_disease.data.targets

# Display basic information about the dataset
print(heart_disease.metadata)
print(heart_disease.variables)
