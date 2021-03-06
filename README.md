# Heart-Disease-Prediction-using-ML-Algorithms


<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->




<!-- PROJECT LOGO -->
<!-- <br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://imgur.com/UNOxdW7" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div> -->



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center">
  <img src="https://imgur.com/UNOxdW7.png" />
</p>

This project is part of our College Semester IV machine learning project. The main machine learning code was written on [Google Colab](https://colab.research.google.com/drive/1splSxv4lArjGC1WXJCuVhGfMKn-HQBZ4?authuser=1#scrollTo=znFNntxszpUw&uniqifier=1). The prediction is based on the [Heart Disease prediction dataset on Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

On acquiring the dataset, three different kinds of classification algorithms were applied to it to figure which algorithm would perform the best. The three classification algorithms we proceeded with were the following:

* [Logistic Regression](https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc)
* [Support Vectorm Machine](https://www.javatpoint.com/machine-learning-support-vector-machine-algorithm)
* [Random Forest Classifier](https://www.javatpoint.com/machine-learning-random-forest-algorithm)

The [Google Colab Notebook](https://colab.research.google.com/drive/1splSxv4lArjGC1WXJCuVhGfMKn-HQBZ4?authuser=1#scrollTo=znFNntxszpUw&uniqifier=1) contains a menu-drivev program to choose the ML algorithm a user might want to choose. Furthermore, we have made a simple web app out of the project by saving our models; which make us able to use them outside of our Google Colab notebook. This was achieved by using [Pickle](https://practicaldatascience.co.uk/machine-learning/how-to-save-and-load-machine-learning-models-using-pickle). 

Our Web application consisted of a ReactJS frontend with a Flask backend. We take our feature input from the frontend, send it to our backend, do our prediction in the Python backend using the saved `.pkl` models, and return the predicted results back to the frontend to be displayed.


<p align="right">(<a href="#top">back to top</a>)</p>



## Built With
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="100" height="100"> <img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" width="100" height="100"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/1280px-Node.js_logo.svg.png" width="100" height="60"> <img src="https://cdn.freebiesupply.com/logos/large/2x/flask-logo-png-transparent.png" width="100" height="100"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="100" height="100">
</p>
  
  
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple example steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/AaryadevChandra/heart-disease-prediction-classfication.git
   ```
2. Enter the root repository directory and then install the Python packages by running
   ```sh
   pip install -r requirements.txt
   ```
3. Enter the `react-app` directory and proceed to install NPM packages
   ```sh
   npm install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Once you have downloaded the repository and have entered the root directory, you are all set to go!

We'll first proceed by running the backend.

1. Enter the `/backend` directory and run
    ```sh
    python heartdiseasebackend.py
    ```
2. Then enter `/react-app` and run 
    ```sh 
    npm start
    ```
    
     Your frontend should automatically launch in your default browser.
    
    ![Frontend imagae](https://imgur.com/gpWKcs8.png)
    
    Make sure you already have run ```npm install ``` in a terminal in the `/react-app` directory.
    
<p align="right">(<a href="#top">back to top</a>)</p>




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Aaryadev Chandra - [@Aaryadev](https://www.linkedin.com/in/aaryadevchandra/) - aaryadevc@gmail.com 

Dev Chandan - [@DevChandan](https://www.linkedin.com/in/dev-chandan/) - dev02chandan@gmail.com

Project Link: [https://github.com/AaryadevChandra/heart-disease-prediction-classification](https://github.com/AaryadevChandra/heart-disease-prediction-classfication)

<p align="right">(<a href="#top">back to top</a>)</p>
