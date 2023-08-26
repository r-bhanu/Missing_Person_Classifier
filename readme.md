# Missing Person Image Classification
The Missing Person Image Classifier is a machine learning project aimed at assisting law enforcement and organizations in identifying missing persons using image analysis. This project utilizes image classification techniques to match input images against a database of images of missing individuals.
<div style="display: flex;">
    <img src="https://github.com/r-bhanu/Missing_Person_Classifier/blob/main/ss2.png" alt="Image 1" width="400" height="300"/>
    <img src="https://github.com/r-bhanu/Missing_Person_Classifier/blob/main/ss1.png" alt="Image 2" width="400" height"400"/>
</div>

### Folder structure

* <b>UI : This contains ui website code</b> 
* <b>server: Contains the Python flask server related code</b>
* <b>model: Contains python notebook for model building</b>
* <b>google_image_scrapping: Contains the code to scrap google for images</b>
* <b>images_dataset: Dataset used for training our model</b>

### Technologies used in this project,

* `Python`
* `Numpy and OpenCV for data cleaning`
* `Matplotlib & Seaborn for data visualization`
* `Sklearn for model building`
* `Jupyter notebook, visual studio code as IDE`
* `Python flask for http server`
* `HTML/CSS/Javascript for UI`

### Installation :

A good practice to start with a new project and use it, is to make a virtual enviornment for the particular project. Here is the steps for making virtual enviornment ::

1. `pip install virtualenv`
2. `python -m virtualenv myenv`

#### Install the dependencies of the App ::

Run commands on python terminal or anaconda terimial or any terminal you are using in your system.

* `pip install -r requirements.txt`

### Test the app:

* Clone the repository: `https://github.com/r-bhanu/Missing_Person_Classifier.git`
* Go to the project directory
* Go to Server Directory: `cd server`
* Run the app: `python app.py`
* The development server will be up and running on port 5000 at the URL: http://127.0.0.1:5000/
* Now go to the UI Folder and open app.html on the browser. <b>Note that the flask app server must be up and running.</b> 
* Drag an image of a missing person from the five and hit the classify button. Our app will predict the missing person's name with his/ her image. It will also show us the percentage match of our image with all the five possible people. 
