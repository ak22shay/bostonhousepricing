
# Automated machine learning/deep learning model deployment in Edge/Cloud devices​

It is an Automated deployment strategy for ML model to deploy on a cloud.
The model created here is for predicting long beach's housing price. The ML model has a web user interface that take input from the user and predicts the housing price.

## Software And Tools Requirements

    VSCode (or any IDE)
    GitHub
    Heroku

## Libraries required
    Flask
    scikit-learn
    pandas
    numpy
    matplotlib
    gunicorn

-Running the application loaclly

    python3 app.py

-Set up the GitHub repository with the project.
-Update the code and push it to the GitHub.

    git add.
    git status
    git commit -m "your comments"
    git push origin main

Code will be pushed to the GitHub repository and the build will start automatically. Once build is successfull, application can be open at Heroku cloud.

Need to add actions in GitHub secrets

- HEROKU_API_KEY
- HEROKU_APP_NAME
- HEROKU_EMAIL

Once all the above steps are performed, application will run on a cloud environment.


    
