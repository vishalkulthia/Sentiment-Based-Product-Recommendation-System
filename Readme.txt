Following Files are included in this project -

1.  Sentiment-based product recommendation system V0.4.ipynb
    - This is end to end Jupiter Notebook which consists of the entire code (data cleaning steps, text preprocessing, feature extraction,       ML models used to build sentiment analysis models, two recommendation systems and their evaluations, etc.) of the problem statement         defined
    - Location --> Root Folder in ZIP

2. Deployment Files 
	a.)  'model.py' file, which contains only one ML model and only one recommendation system that has been obtained from the previous               steps along with the entire code to deploy the end-to-end project using Flask and Heroku
        
        b.) 'index.html' file, which includes the HTML code of the user interface
	     Location - Present in Template Folder

        c.) 'app.py' file, which is the Flask file to connect the backend ML model with the frontend HTML code
         
        d.) Supported pickle files, which have been generated while pickling the models

     Location - Present in Folder - Flask & Heroku Deployement