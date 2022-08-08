# Unit 6 Homework: Planning Vacation based on Weather Conditions

### Analysis

>This is a general summary of the weather patterns and a general description of the processes. 

### Mentionable observations in climate:

* There is a noticable change in atmospheric moisture as you approach the equator from the north or south pole.
* That change is slightly different in the two hemispheres. There is a peak in the climate conditions nearer to the tropic of cancer.
* Below the tropic of cancer there is an inland concentration of hot arid climates that might skew those moisture readings.
* By moisture, referring to a pattern somewhat repeated in cloudiness, as well as humidity.


### Processes

##### *WeatherPy*
* Random generation of a list of global cities
* Pulled climate date using open weather app api formatted in JSON.
* Cleaned and checked the dataframe and stored it to file city_data.csv
* Genreated a scatter plot with a regression line
* Once the first plot was complete, remaining plots followed with simple editting and reloaction of annotation

=======================================================

##### *VacationPy*
* Imported city_data.csv
* Generated a heatmap based on humidity levels of all cities in the dataframe
* Reduced the dataframe to fit user criteria
* Added empty column to the shorter dataframe to hold hotels
* Using lat and lon coordinates made a new url request into json for hotels nearest to the city center
* Populated the hotel column of the dataframe with the results and dropped null values
* Generated a new map layer with markers for the hotels
* Using the same heatmap, but with the shorter list, overlayed the marker layer onto the map


### Next time
* To simplify the iteration of the forloop, I might make better use of creating empty variables as lists rather than making an empty column right in the dataframe, and then pass the lists into the df as the variable.  This might work cleaner, diversify my options for looking at, and manipulating the data, as well as making the code easier to read.
* Need to make better practices and study limitation tools for my use of api keys, before getting into larger datasets
 
Authors:
* John Torgerson (JohnTorgerson) 


