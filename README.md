# AML
Assignment 2
topic: Autoencoder and types

requirements: pip install -r requirements.txt

How to run? 
1) Download assignment_2.ipynb file
2) download dataset from https://drive.google.com/file/d/1iVl4Q4Bq3Fbwv60lLthfBc6eYxYLrdnU/view?usp=sharing
3) put datasets in the same folder with ipynb file
4) delete 3 cells after import section: 
5) delete

from google.colab import drive

drive.mount('/content/drive', force_remount = True)

df_tr = pd.read_csv('/content/drive/MyDrive/assignment_2/data_transaction.csv')

df_id = pd.read_csv('/content/drive/MyDrive/assignment_2/data_identity.csv')

6) write df_tr = pd.read_csv("data_transaction.csv")
7) write df_id = pd.read_csv("data_identity.csv")
8) run code
