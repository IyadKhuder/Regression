# Regression
This Notebook is a summary of my self-learning of the Regression models.
I'm made a simple demo of each model on the same case-study and dataset that I fabricated myself for this purpose.

I've gathered the following regression models in one notebook, so they can be compared to each other.

- I. Polynomial Regression

- II. SVR

- III. Decision Tree

- IV. Random Forest Regression


*Case-study:*

*An applicant for the job position "ML engineer" at IDC claimed that his previous gross salary per annum was $65k, given that he worked as a junior ML engineer for 1.5 year and he is assessed to be in the midway between junior and senior ML engineer.*

*Based on a data sample of salary averages as a fenction of the position rankings, is he honest or this is a bluff?*
🙄

Let's build a ML model that estimates the salary of that applicant, and predicts whether he was honest or just bluffing.


For this scenario, I designed the dataset in such a way that the output does not change in a monotone manner with the input, so the graph cannot be described by a linear or simple ploynomial function, but rather a polynomial of a degree higher than 3.

I've made this part available in two versions:

-> In version 1.0 (plug-and-play) 

you don't need to worry about the dataset, because it's hosted on my Google Drive and made public. It's then imported using the necessary libraries and code. On the other hand, in v.1.1 the dataset needs to be hosted on your Google Drive, and therefore you should upload it on your Google Drive and then connect to it using the necessary code.

-> In version 1.1, 

In this version, the dataset is to be hosted on your own Google Drive. 
You might prefer to migrate this notebook on your premises. In that case, this version is a better option.
However, you'll need to upload the dataset on your Google Drive and then connect to it as follows: 
- Get the CSV file (attached herewith) and upload it to your Google Drive.
- Open the notebook file in  Google Colab
- Run the notebook cell that connects to your Google account

> from google.colab import drive
> 
> drive.mount('/content/drive')

and give it the necessary permission.
- Having connected to  Google Drive, you'll see an icon for that in the left menu. Expand that icon and locate the CSV file.
- Right-click the CSV file and copy its path.
Paste that path as the value for the variable Dataset_location_on_Google_Drive in the first cell.

Thus, the function
> salaries_dataset = pd.read_csv(Dataset_location_on_Google_Drive+'salary_vs_position.csv')

will be able to read and import the dataset properly.

A good article on linking Google Drive with your Google Colab notebook:
https://towardsdatascience.com/different-ways-to-connect-google-drive-to-a-google-colab-notebook-pt-1-de03433d2f7a

- - -


with best regards,

Iyad Khuder
