# Regression
This Notebook is a summary of my self-learning of the Regression models. 
I've created a demo for each model and applied it on a simple dataset.

In this Notebook, I'm covering the following models all together since I use the same dataset for both models, so you don't bother linking to Google Drive each time:

I. Polynomial Regression

II. SVR

III. Decision Tree

IV. Random Forest Regression

In this 1.1 version, the dataset is to be hosted on the user's Google Drive, and therefore he/she should upload it on their Google Drive and then connect to it as follows: 
- Get the CSV file (attached herewith) and upload it to your Google Drive.
- Open the notebook file in  Google Colab
- Run the notebook cell that connects to your Google account
---
from google.colab import drive
drive.mount('/content/drive')
---
and give it the necessary permission.
- Having connected to  Google Drive, you'll see an icon for that in the left menu. Expand that icon and locate the CSV file.
- Right-click the CSV file and copy its path.
Paste that path as the value for the variable Dataset_location_on_Google_Drive in the first cell.

Thus, the function
salaries_dataset = pd.read_csv(Dataset_location_on_Google_Drive+'salary_vs_position.csv')
will be able to read and import the dataset properly.

A good article on linking Google Drive with your Google Colab notebook:
https://towardsdatascience.com/different-ways-to-connect-google-drive-to-a-google-colab-notebook-pt-1-de03433d2f7a

with best regards,
Iyad Khuder
