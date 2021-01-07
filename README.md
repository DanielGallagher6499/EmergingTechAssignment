# EmergingTechAssignment - 50%
#### Author - Daniel Gallagher 
#### Student number - G00360986
#### Email Address - G00360986@gmit.ie
***
#### Overview.
This is the repository for the emerging technologies modules project worth 50%. The project brief is displayed below and outlines what needs to be done in this project. The dealine for this project is the 8th of January at midnight. Any commits after this are not permitted.
***
#### The Brief.
In this project you must create a web service that uses machine learning to make predictions based on the data set powerproduction available on Moodle. The goal is to
produce a model that accurately predicts wind turbine power output from wind speed values, as in the data set. You must then develop a web service that will respond with
predicted power values based on speed values sent as HTTP requests. Your submission must be in the form of a git repository containing, at a minimum, the following items:

- Jupyter notebook that trains a model using the data set. In the notebook you should explain your model and give an analysis of its accuracy.

- Python script that runs a web service based on the model, as above.

- Dockerfile to build and run the web service in a container.

- Standard items in a git repository such as a README. To enhance your submission, you might consider developing and comparing more than one model. Rest assured, all the above concepts will be explored in lecture videos and other materials in the coming semester.
***
#### What you need installed to run this.
The latest version of each of the follow are essential for the running of this project.
- Python (We got ours via the latest anaconda)
- Flask
- Tensorflow
- Jupyter Notebook
A good editor software such as Visual Studio code is also recommended if you want to look at the source code.
***
#### Running the web application.
In this section the way in which the web application is run from the command line will be explained. It is very easy and straight-forward and if you have the correct software installed it should run easily on your machine.

- Step 1 : Open a command window in the project directory.

- Step 2 : Use this command "set FLASK_APP=web-service.py".

- Step 3 : Run this command next "python -m flask run".

After these commands are run a URL should show up inside the command window. Pasting this URL into your browser will then allow you to locally access the web application via the browser.
