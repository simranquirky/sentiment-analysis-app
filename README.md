
## We have built a machine-learning project which can be used to predict the sentiment of a particular message. This can be used to segregate hate comments on Twitter or any other social media app.

### Tech Stack Used
- Python
- Machine Learning
- Flask
- HTML
- CSS

### Files present
- app.py: Main application
- train.py: Script to train and save the trained model
- sentiment.tsv: Data file
- requirements.txt: It contains required packages/dependencies
- Dockerfile: To create the docker image
- Template folder: It contains our web page for the application. This contains the HTML and CSS pages.
- model folder: It contains our trained model

To run this project on your local machine 
- Clone this repo using the command:
`git clone https://github.com/simranquirky/sentiment-analysis-app.git`
- Then move to the folder sentiment-analysis-app using the command `cd sentiment-analysis-app`.
- Now download all the dependencies specfied in the requirements.txt file by running the command `pip install -r requirements.txt`
- Once all the dependencies are downloaded, you can run your app using the command `python3 app.py`. Your service will run and the url will be specified. You can click on the specified Url to access the application, which runs on port 5000.