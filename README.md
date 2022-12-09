# Music Recommendation system using Spotify Ddataset


## Introduction

The goal of this project is to recommend songs for a given playlist. This project starts from data collection all the way to model deployment to ensure you have a working model to showcase.

### Data extraction

Here are a couple of things you should know before starting the project.

#### Spotfiy API Acquisition
If you haven’t used an API before, the use of various keys for authentication, and the sending of requests can prove to be a bit daunting. The first thing we’ll look at is getting keys to use. For this, we need a [Spotify for developers] (https://developer.spotify.com/) account. This is the same as a Spotify account, and doesn’t require Spotify Premium. From here, go to the dashboard and “create an app”. Now, we can access a public and private key, needed to use the API.

#### Spotify Credentials Storage and Access

Now that we have an app, we can get a client ID and a client secret for this app. Both of these will be required to authenticate with the Spotify web API for our application, and can be thought of as a kind of username and password for the application. It is best practice not to share either of these, but especially don’t share the client secret key. To prevent this, we can keep it in a separate file, which, if you’re using Git for version control, should be Gitignored.

Spotify credentials should be stored the in the a `secret.txt` file with the first line as the **credential id** and the second line as the **secret key**:

```

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
│  
```
