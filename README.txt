from google.colab import drive
drive.mount('/content/gdrive')

import pandas as pd
train = pd.read_csv('/content/gdrive/MyDrive/heights.csv')