# Music Recommendation system using Spotify Dataset


## Introduction

The goal of this project is to recommend songs for a given playlist. This project starts from data collection all the way to model deployment to ensure you have a working model to showcase.

### Data extraction

Data is available in the form of json files and several steps have to be followed to extract features into a csv file.

#### Spotfiy API 
For this, we need a [Spotify for developers] (https://developer.spotify.com/) account. From here, go to the dashboard and “create an app”. Now, we can access a public and private key, needed to use the API.

#### Spotify Credentials Storage and Access

Now that we have an app, we can get a client ID and a client secret for this app. Both of these will be required to authenticate with the Spotify web API for our application, and can be thought of as a kind of username and password for the application. 


## Repo Structure

```
│
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── raw            <- The original, immutable data dump.
│   ├── processed      <- The preprocessed data sets for training.
│   ├── test           <- The test data sets for testing.
│   └── final          <- The final data sets for modeling.
│
├── models             <- Trained models, model predictions, or model summaries.
│
├── notebooks          <- Serialized Jupyter notebooks created in the project.
│   ├── script         <- Script for data extraction and loading data
```
