# Tidy Tuesday Project #1 LEAP DAY
Happy Leap Day! This week's data comes from the [February 29](https://en.wikipedia.org/wiki/February_29) article on Wikipedia.

### Data Dictionary

# `events.csv`

|variable |class     |description |
|:--------|:---------|:-----------|
|year     |integer   |Year of the event. |
|event    |character |A short, free-text description of the event. |

# `births.csv`

|variable    |class     |description |
|:-----------|:---------|:-----------|
|year_birth  |integer   |Year in which this person was born. |
|person      |character |The name of the person. |
|description |character |A short description of the person. |
|year_death  |integer   |Year in which this person died. |

# `deaths.csv`

|variable    |class     |description |
|:-----------|:---------|:-----------|
|year_death  |integer   |Year in which this person died. |
|person      |character |The name of the person. |
|description |character |A short description of the person. |
|year_birth  |integer   |Year in which this person was born. |

# Result

The first three pie charts give an overview of each CSV file. Since there were too many different years, I've decided to group these years by centuries for easier visualization. 
![pie1](https://github.com/Fuzerius/TidyTuesday-projects/assets/139658690/aa616a77-8ff6-4016-bd5e-222d6e3963c8)



After combining all these files, I tried to find all the countries and nationalities mentioned. For example, every time an American is mentioned, or something happened in the United States, the United States count increases by one. This chart is not 100% accurate because some countries no longer exist or are part of another country. Some data loss is expected.
![chart1](https://github.com/Fuzerius/TidyTuesday-projects/assets/139658690/ab2bb9c0-1786-4094-a97e-8f1aec3d2c1d)



The last pie chart shows the continents where these events happened .
![pie2](https://github.com/Fuzerius/TidyTuesday-projects/assets/139658690/de158c5f-c12f-46a7-b237-8455ff3ec864)

