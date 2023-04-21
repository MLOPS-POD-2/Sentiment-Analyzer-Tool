# Sentiment-Analyzer-Tool deployment in EC2 using MLOPS
 It analyze the sentiment of the user, whether it is postive or negative.
 
 It uses [streamlit](https://streamlit.io) library for creating this sentiment analyzer tool on a platform like web.
 
 
 ## Requirement
 1. Scikit-Learn
 2. Streamlit
 3. Numpy
 4. Matplotlib
  and Python 3.9

For deployement 
 1. Dockerhub account 
 2. EC2 Instance with SSH access in AWS [Follow the https://github.com/appleboy/ssh-action to setup SSH access]
 
Just fork the repository, set the necessary secret variables and then commit, it will deploy the app in the EC2 instance without manual intervention everytime you commit the code and then you can interact with it in your browser.


Thank You!
