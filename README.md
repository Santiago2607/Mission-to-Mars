# Mission-to-Mars

## Overview of the Project

During this project, we helped the company SpaceForward and Robin, its Data Analyst, to gather different information about Mars such as the weather, temperature, pressure, and how many different days has a martial year comparing to an earth year. Analyzing a huge amount of data such as this one can be easier or more difficult depending on which tools and methods we use, however, we agreed with Robin to use a method that can help us save time and excel in our analysis at the same time. We decided to use the web scraping method on two NASA webpage regarding Mars. 

## Analysis

For the first part of this analysis, we extracted information such as the title and the preview text of all of them of one of the websites, so we can have a better understanding of the most recent news about this planet. The resources that we used in this part along with the web scraping tool were splinter, bs4 or beautiful soup, and webdriver_manager.chrome.

Here is the code we used to extract the titles and previews
![image](https://user-images.githubusercontent.com/113261292/208784332-9c02cf50-ded8-4748-9228-6eddaeb6ef43.png)

And how we managed to show all that information as an output
![image](https://user-images.githubusercontent.com/113261292/208784490-343a0d47-c9a7-4157-9ce3-2f469786348d.png)

For the second part of this analysis, we extracted a table with its information so we can study and analyze it in a simpler way. We also used some for loops so we can get specific data such as min and max temperature, pressure, and the total days a martial year has. To achieve this goal, we had to add to our tools matplotlib and pandas to show a better output graphically and legibly. 

![image](https://user-images.githubusercontent.com/113261292/208785230-bb1ce2ff-3d9e-4e75-adf4-9cb7b91a3646.png)
![image](https://user-images.githubusercontent.com/113261292/208785294-70397902-1b3a-4be3-aecb-92a03cf2b133.png)
![image](https://user-images.githubusercontent.com/113261292/208785318-bdcf8890-c8bb-4862-be33-33fc7ccc7c48.png)
![image](https://user-images.githubusercontent.com/113261292/208785357-ab17de4d-ad95-4b2a-8b83-62f2705e314d.png)

## Results

Some of the results that we got by doing the analysis are:

1. There is a total of 687 earth days in a martial year.
2. The minimum (coldest) temperature you can experience on Mars is about -83.307292 degrees and is during the month of March.
3. The maximum (hottest) temperature you can experience on Mars is about -68.382979 degrees and is during the month of August.
