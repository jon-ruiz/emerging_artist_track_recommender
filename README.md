# Emerging Artist Track Recommender
## Overview

When Last.fm launched in 2002, few imagined the full extent of the impact streaming services have on the music industry a decade later. As of September 2018, streams are responsible for more than 75% of the music industry's revenue.<sup>[[1]](https://www.theverge.com/2018/9/20/17883584/streaming-record-sales-music-industry-revenuespl)</sup> Music streaming services have not only provided users with an easy avenue to consume music legally, but have also created user experiences tailored to the individual largely via music recommendation algorithms, driving a large part of this growth--the most notable among them being Spotify. Spotify's recommendation engine has gained praise from users in the past few years for its seemingly deep understanding for what the users what to listen to. This is no surprise. Spotify's recommendation engine is incredibly robust and powered by three main strategies: collaborative filtering, NLP, and track-level audio analysis. The primary goal for this project will be to nuance the latter two approaches by introducing a novel data source to the NLP efforts (social media commentary) and identifying commonalities between songs by employing cosine similarity, a largely unexplored strategy for music recommendations.

A major consequence of the streaming economy has been the propulsion of already well-established artists into platinum acts. <sup>[[2]](https://pitchfork.com/features/oped/how-to-be-a-responsible-music-fan-in-the-age-of-streaming/) [[3]](https://www.billboard.com/articles/business/streaming/8479225/drake-ed-sheeran-rihanna-spotify-all-time-streaming-lists) [[4]](https://www.forbes.com/sites/hughmcintyre/2016/02/13/now-that-streaming-can-make-a-song-platinum-what-counts-and-what-doesnt/)</sup> This is why a secondary but still central goal of my project will be to work toward a methodology that can benefit emerging artists. The final product will therefore take songs from established artists who fit a given user's taste, match them with those from emerging artists, and offer them as recommendations to the user. 

This approach is not only attempts to balance the proverbial playing-field, but also fills a vital need for the user: the "serendipity" factor. <sup>[[5]](https://www.sciencedirect.com/science/article/pii/S1877050913008971)</sup> An exploratory survey I administered before landing on this project suggests that while Spotify does a great job recommending songs that tightly fit within users' taste-levels, users crave more recommendations from artists that may never be on their radar. This is the tertiary but still vital goal of this project.

### This project is split into the following parts:

* Exploratory Survey Analysis 
* Data Collection
* Preprocessing
* Recommender Information Architecture

### The tasks performed in this project include:
* Collecting data from the Spotify and Billboard APIs with the help of the Spotipy and Billboard libraries
* Preprocessing of mp3 files into spectrogram images using librosa library
* Building the information architecture for a recommender engine 
