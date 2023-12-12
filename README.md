# CourseProject Movie Recommender 
This project is a movie recommender application it takes a users chosen movie and outputs 5 similar movies out of a database of 6,000. It will prompt the user to select their favorite movie or show and input it into the search bar. It will then search and compare the users movie or show description to a database of other movie and shows and find related terms that the user may like related to the input movie or show. There is also a second search bar that also searches the whole database that will show the movies and shows in the database and provide information about them such as the dircetor, cast, duration, the year it came out, and the description. This application can be used for a variety of things as well so long as it has a database with title and description. 

To start this application

You need:
MovieRecommenderApp.py
netflix_titles.csv 

These 2 files must be in the same folder

you need to make sure you have done the following installs in command prompt before launching or it will not work simply run the following commands in command prompt

     pip install pandas 
     pip install dash 
     pip install rank_bm25 
     pip install plotly 
     pip install dash_bootstrap_components 

Then run the MovieRecommenderApp.py application in IDE 

![a45af692f82853f2af7158a7b5da55c4](https://github.com/SilverHolo/CourseProject/assets/73237866/7fa69e0f-5261-4b97-ac7e-89c7292b8e54)

Then you go to http://127.0.0.1:8050/ should also be output in IDE or can enter manually and input a movie or show to recieve you recommendations 

The application checks imports and packages and libraries. Then loads movie and show data and launches the website using DASH and BOOTSTRAP that have the UI Component. Then uses a callbacks and associated functions to check and compare related descriptions using BM25 and calculates the simularities in the descriptions and outputs the top 5 using a simularity score. 
