# UFOs
## Overview of Project

To create a webpage and dynamic table with table multiple filters like city, state, country, and shape for UFO sightings. 

### Resources 

data.js - contains the information about sightings including Datatime , City, State , Country , Shape, Duration and Comments.
Using javascript , HTML and Bootstrap.

### Results
Below is the webpage when we load the html page with the data

![image](https://user-images.githubusercontent.com/98556229/177202808-efb80b77-cf17-48e8-bd6d-f562e4322e69.png)


UFO data loaded from the data.js file, the webpage shows the entire dataset. We can filter the date based on different filters.Below is snapshot: 

![image](https://user-images.githubusercontent.com/98556229/177205396-7dc48d6c-060d-478e-9e8d-436a6696b714.png)

When we enter one/more of the search criterias and hit enter , the already loaded data is refined based on the search criteria and new data is loaded.Below is the snapshot for a search criteria - 
1. for Filter search City = "la mesa" - 
![image](https://user-images.githubusercontent.com/98556229/177206147-0fe949bf-3f12-4717-877d-152f9bce5605.png)

2. for Fiter search shape = triangle 
![image](https://user-images.githubusercontent.com/98556229/177206214-dcfae648-0cf8-4998-99ed-8daed7f4ddb4.png)

3. for multiple filter State = ca , shape = trianle ,data = 1/1/2010
![image](https://user-images.githubusercontent.com/98556229/177206302-f173bbfc-6d30-42db-945b-9b30c40d582c.png)


### Summary 
#### Drawbacks.
The filters that are provided need to be exact matches and are casesensitive. A user should be able to filter data based on standard state codes that are typicalls used or in any cases (lower or upper case) same should hold true for other searches.

#### Recommendations.
1. We can add pictures for each of the observations so that its be interactive and user friendly and more informative for the user using the webpage.
2. We can add an export button to the webpage so that they view the data in a pdf or excel format as a report the desired specific data.
