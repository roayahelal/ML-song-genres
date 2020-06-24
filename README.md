# Machiene Learning Song Genre Predictor

This is a Random Forest Machine Learning model, trained using 15 audio analysis features. Users can input a song name which is used to retrieve audio-analysis features from Spotify’s API for the model to return the predicted genre. 

Tech used: Python (Pandas,Numpy, Sklearn, Matplotlib, Pickle, Flask), HTML, CSS, Bootstrap

## Background

Spotify's API has genres that are tied to artists but not individual songs.

In today's music, we are seeing that artists tend to not stick to one genre when producing music, this can be the case for even albums having multiple genres musically that all relate to one genre artisticly. An example of this is Kanye West's The Life of Pablo; individual songs can vary from hip-hop to electronic but the overal artist's intended genre is actually gospal and Kanye west is carectorized as a hip-hop and rap artist.

It can be diffucult to like a single song from an artist's catelog and try to find similar songs musically and not neccesarly similar based on the artist's genre.The purpose of creating this proect was to create a model that would be abel to predict a song's genre based on nothing but audio-analysis features. By doing so, we would be removing all other aspects that can influnce and add a bias to labeling a song's genre and when identifying a single song's genre users would be abel to know genres of individual songs that they like


![alt text](https://github.com/roayahelal/ML-song-genres/blob/master/images/UI.png)
