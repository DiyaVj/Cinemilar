<p align="center">
<img src="https://user-images.githubusercontent.com/87236107/170822111-b45beb0f-46b9-4eb3-b2ce-f70a23ba5717.png" width=30% height=30%>
    <br />
  <a href="https://diyavj-cinemilar-app-kh30et.streamlit.app/"><strong>Explore the app here »</strong></a>
</p>
<details>
  <summary>Table of Contents</summary>
  <ol>
     <li>
      <a href="#project-structure">Project Structure</a>
    </li>
      <li>
      <a href="#problem-statement">Problem Statement</a>
    </li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#why-cinemilar">Why Cinemilar?</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#future-goals">Future Goals</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## Project Structure
```
root
|
|
|____Recommendation_engine
     |___.ipynb_checkpoints
          |____Movie-recommender-system-checkpoint.ipynb
     |____Movie-recommender-system.ipynb
     |____tmdb_5000_credits.csv
     |____tmdb_5000_movies.csv
|____.gitignore
|____LICENSE
|____Procfile
|____README.md
|____app.py
|____requirements.txt
|____setup.sh
                                     
```
## Problem Statement

<img src="https://user-images.githubusercontent.com/87236107/170763467-bb1e9f13-5651-482c-807e-c57c9deb6e42.jpeg" width=25% height=25%>

## About The Project

Recommender system help e-commerce sites to increase their sales.These days, recommendation Systems are used everywhere, whether it's an e-commerce site, Spotify, or Netflix and many others. The goal of a recommendation engine is to assist users in finding relevant items and to provide them with a personalized experience. Netflix makes recommendations using a hybrid system (collaborative filtering algorithm + content-based filtering algorithm).

Cinemilar is a web-based movie recommendation application.This application uses a content-based filtering algorithm. It recommends movies based on the similarity of their meta data.


### Why Cinemilar?

Cinemilar assists users in finding and personalising movies that they enjoy. Its goal is to predict users' interests and recommend movies that are likely to be of interest to them.
The best thing about using content-based recommendation is that no data from other users is required to begin making recommendations.

### Built With
* Frontend - [Streamlit](https://streamlit.io/)
* Backend  - [Python](https://www.python.org/)
* Dataset  - [TMDB 5000 Movie dataset (Kaggle)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download)
* Deployment plateform - [Heroku](https://www.heroku.com/)
## Getting Started

This application is very simple to use. To use cinemilar, follow the steps below.

* Go to [Cinemilar](https://cinemilarity.herokuapp.com/)
* You can see the application interface. Search for or select the movie to which you want to find similar movies.
* That's all. Cinemilar recommends the top five similar movies.  

### Testing code

Here are some details to consider before running code.

#### Prerequisites

* [Pycharm](https://www.jetbrains.com/pycharm/)
* [Jupyter Notebook](https://jupyter.org/)

#### Installation

* Clone the Repo 

```sh 
git clone https://github.com/DiyaVj/Cinemilar
```

* Install the requirements 

```sh 
pip install requirements.txt
```


## Future Goals

* I intend to improve UI/UX of the app.
* Would like to update the app and use a hybrid technique to make it more user-friendly.
* Also want to add more features to the application, such as movie details and information about the movie theatre and schedule where the specific movie is available.

## License

The project is acquired under the [MIT License](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#disclaimer).
