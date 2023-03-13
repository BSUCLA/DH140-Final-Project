[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BSUCLA/DH140-Final-Project/HEAD)

# DH140-Final-Project

This repository contains my analyis of Quentin Tarantino's films as a final Project for DH 140 at UCLA for W23 quarter.

This analysis uses data such as budget, revenue, cast, crew, and viewer sentinment to attempt to discover some of the factors which may contribute to his continued success.

---

## Questions of interest

Data can be used to address many statistical questions as well as help form connections between seemingly disparate pieces of information.
Some examples of questions include:  

* How did the budget for tarantinos films change overtime (as he became more famous)?
* What are the relationships between budget, revenue, popularity and rating for tarantino films? How are these related to:
    * Genre?
    * Cast?
    * Crew?        
* Since Tarantino is known for repeatedly casting some actors and actresses, can examining which ones are in which movies reveal hidden connections related to success?
* Less well known are crew members, do Tarantino's films re-use crew members in the same way?
  
---

## Data 

Data for this analysis is sourced from [The Movie Database (TMDB)](https://www.themoviedb.org), a community built database with millions of users that has been in service since 2008, using their publicly available web API.  
For more information about TMDB see the [About page](https://www.themoviedb.org/about). For information about the API, including documentation, see the [API page](https://www.themoviedb.org/documentation/api).  

The [tmdbsimple](https://github.com/celiao/tmdbsimple) library provides easy access to the TMDB web API using Python.