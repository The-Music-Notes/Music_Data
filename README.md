# Music_Data

**Requirements**

<!-- Completed Analysis Uploaded to GitHub 
Final data analysis contains ample and complete information in README file 
Final repository is acceptable for professional quality presentation  -->


Hypothesis:  With music being "feelings you can hear", was it significantly impacted by the shutdowns during Covid 19?   What other changes to trends might emerge from the data?  We took data from Spotify, and broke it down primarily by date:  Pre-covid (before March 17, 2020) and Covid/Post-covid (March 17, 2020 and beyond).
Questions:
    * Was music streaming significantly affected by the Covid 19 Pandemic shutdown overall?
    * Did people stream more or less?
    * Were there any changes by genre?
    * Was there any change in the top artists?
    * Were there changes in the types of songs (loudness, tempo, energy, etc.)?

The location of the repository is https://github.com/The-Music-Notes/Music_Data.

A data file of all Spotify music streams from 2017 - 2022 (data.csv) was downloaded from Kaggle.com and cleaned up with the first Jupiter Notebook, Cleanup.ipynb.
    * Since Spotify had so many genres, we created a new column called "Master Genre" and a key file called "genre_key".  We assigned a single genre that best represents the song.
    * Columns for Month and Year were added to make calculations easier.
    * The data was saved to a new csv called "Music_Data.csv".

In the Jupyter Notebook file genre_category.ipynb, the data is analyzed for total number of streams as well as by genre by year.

In the Jupyter Notebook file CW_Music_Data_starter.ipynb, the data is analyzed for ?

Finally, an API call to Spotify allowed us to gather more information regarding the attributes (as defined by Spotify) of the music that was streamed: 
"Popularity", "acousticness", "danceability", "duration_ms", "energy", "instrumentalness", "key", "liveness", "loudness", "mode", "speechiness", "tempo", "time_signature", "valence"

**Visualizations** 

<!-- 6–8 visualizations of data (at least two per question) 
Clear and accurate labeling of images 
Visualizations supported with ample and precise explanation -->


The charts have been stored in a folder called Graphs.

**Analysis and Conclusion**

<!-- Write-up summarizes major findings and implications at a professional level 
Each question in the project proposal is answered with precise descriptions and findings 
Findings are strongly supported with numbers and visualizations 
Each question response is supported with a well-discerned statistical analysis from lessons (e.g., aggregation, correlation, comparison, summary statistics, sentiment analysis, and time series analysis)  -->

There is little to no statistical evidence that Covid 19 shutdowns changed the music we listened to or how we listened to it.  We therefore reject the hypothesis.

**Group Presentation**

<!-- All group members spoke during the presentation 
Group was well prepared 
Presentation is relevant to material 
Presentation maintains audience interest  -->

**Slide Deck**

<!-- Slides are visually clean and professional 
Slides are relevant to material 
Slides effectively demonstrate the project 
Slides are clear and maintain audience interest  -->
