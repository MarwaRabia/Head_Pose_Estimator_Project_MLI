MLI project  Head Pose Estimation
==============================

machcine learning 1 project
Head Pose Estimation Using Landmarks
------------
The main objective of this task is to find the relative orientation (and position) of the human’s head with respect to the camera. In particular, in the head pose estimation task, it is common to predict relative orientation with Euler angles – yaw, pitch and roll. They define the object’s rotation in a 3D environment

![alt text](https://indatalabs.com/wp-content/uploads/2021/01/2d-3d-head-pose-estimation.jpg)


How it works
------------
- Face detection. A face detector is introduced to provide a face landmarkes  containing a human face.
- Facial landmark detection. A pre-trained model take the face image as input and output 936 facial landmarks.
- These  landmarkes used as input to our model 
- The out put of model is yaw, pitch and roll

MediaPipe
------------

MediaPipe offers ready-to-use yet customizable Python solutions as a prebuilt Python package.

![alt text](https://github.com/google/mediapipe/blob/master/docs/images/mediapipe_small.png?raw=true)


To Sum Up
------------

Head pose estimation  is vital for vision-based application development. Face recognition apps, video surveillance systems, AI fitness and therapy apps – all of them more or less utilize head pose estimation algorithms.


Project Organization
------------

==============================

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>



