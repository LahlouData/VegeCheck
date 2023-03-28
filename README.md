# VegeCheck

#Create Virtual (Windows) Environment:

py -m venv env
.\env\Scripts\activate


#prerequis: 

pip install -r reuiqrements.txt

run app: 
streamlit run app.py           

# To share with public: 

To share your Streamlit application with the public, you can use Streamlit Sharing, 
a free hosting service for your Streamlit applications. Here's how to do it:

Create a GitHub account if you don't already have one.
Create a new repository on GitHub and give it an appropriate name.
Add all the files for your Streamlit application to this repository. Make sure to include all the necessary files, such as the file containing your code (e.g. app.py), data files (e.g. OpenFoodFacts.csv) and possibly the requirements.txt and Procfile files.
Go to share.streamlit.io and login with your GitHub account.
Click on "New app" at the top right of the page.
Select the repository you created in step 2, then select the branch and file for your app (for example, app.py).
Click on "Deploy" to deploy your application.
Streamlit Sharing will deploy your application and provide you with a public link that you can share with others. Note that using Streamlit Sharing is free, but subject to certain limitations in terms of resources and runtime.

If you want more control over your hosting or need additional resources, you may want to consider other hosting options such as Heroku, AWS, Google Cloud or Microsoft Azure.