# Regression
This Notebook is a summary of my self-learning of the Regression models. 
I've created a demo for each model and applied it on a simple relevant dataset.

I've gathered the models that use the same dataset in one notebook, so you don't bother linking to Google Drive for each model.


Part 1: Notebook 1

In this part, I cover the following models all together since I use the same dataset for them:

I. Polynomial Regression

II. SVR

III. Decision Tree

IV. Random Forest Regression

I've made this part available in two versions:

In version 1.0, you don't need to worry about the dataset, because it's hosted on my Google Drive and made public. It's then imported using the necessary code and importing the relevant libraries. On the other hand, in v.1.1 the dataset needs to be hosted on your Google Drive, and therefore you should upload it on your Google Drive and then connect to it using the necessary code.

In version 1.1, the dataset is to be hosted on the user's Google Drive, and therefore he/she should upload it on their Google Drive and then connect to it as follows: 
- Get the CSV file (attached herewith) and upload it to your Google Drive.
- Open the notebook file in  Google Colab
- Run the notebook cell that connects to your Google account

from google.colab import drive
drive.mount('/content/drive')

and give it the necessary permission.
- Having connected to  Google Drive, you'll see an icon for that in the left menu. Expand that icon and locate the CSV file.
- Right-click the CSV file and copy its path.
Paste that path as the value for the variable Dataset_location_on_Google_Drive in the first cell.

Thus, the function
salaries_dataset = pd.read_csv(Dataset_location_on_Google_Drive+'salary_vs_position.csv')
will be able to read and import the dataset properly.

A good article on linking Google Drive with your Google Colab notebook:
https://towardsdatascience.com/different-ways-to-connect-google-drive-to-a-google-colab-notebook-pt-1-de03433d2f7a

- - -

Part 2: Notebook 2
In this Notebook, I'm covering the following models all together since I use the same dataset for both models, so you don't bother linking to Google Drive each time:

I. Logistic Regression

II. K-Nearest Neighbors (K-NN)

III. Support Vector Machine (SVM)

IV. Kernel SVM

V. Naive Bayes

VI. Decision Tree Classification

VII. Random Forest Classification



with best regards,
Iyad Khuder
