# Simple-Image-Classifier
Image classifier for the popular Apex Legends FPS game. Firstly, I built and used a Google images web scraper to gather image data for preprocessing, secondly I created and trained a simple classifier model and lastly I set up a flask web app for uploading an image to be classified.


### Requirements: 
- Flask
- Werkzeug


### Project Workflow:
- [X] Gather and pre-process images data.
- [X] Build, train and store Classifier Model.
- [X] Create simple Flask web app to upload and display image to be classified by model.
- [ ] Add model into Flask web app code and show prediction.


### To Run:
Simply run *flask run* in the working directory or *python app.py*


### Known issues / implications:
- The images pulled from Google using the scraper are far from ideal.
- Model Accuracy sits at a very discomforting ~60%.
- I did not focus as much on optimizing the model and perfecting the dataset as I did on learning the workflow of the project.
