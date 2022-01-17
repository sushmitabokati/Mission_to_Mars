### Mission to Mars

#### Project Overview
Create a webscraping app that utilizes various python libraries to scrape photograph and essential information for the planet Mars. Utilize html, css and bootstrap component to make the app cohesive and compatible for various devices. 

#### Tools used:
- Python libraries:  Flask, Splinter, Beautifulsoup, Pandas, Selenium
- Database: Monogdb
- Webstack: html, css

#### Deliveries:
1) Scrape the dictionary list for the Mars images from the https://marshemispheres.com/. Images dictnoary list were extracted using the help of the library splinter and beautiful soup. 
   <img width="757" alt="Screen Shot 2022-01-16 at 8 18 09 PM" src="https://user-images.githubusercontent.com/93223274/149689566-5428badf-432c-410f-a3cf-404c63323d3c.png">

2) Incorporate the scraping pieces done in the deliveries one into the functional python file so that it can be easily seemlessly used with the flask and mongo db. 

3) Put together the flask app where it users can scarpe the data with the html buttons and scraped data automatically updates the containers with in the web. 
   <img width="1215" alt="Screen Shot 2022-01-16 at 8 08 17 PM" src="https://user-images.githubusercontent.com/93223274/149689564-f42f0583-5004-4c8a-8b57-3d1aec143a55.png">


### Challenges:
One of the biggest challenge i faced during the process was to work arround with the mongo db and the flask. One of the challenges i faced was after installing the Mongodb I couldnot create /data/db folder. Even if i had created i was getting the permission issue. Below is the steps involved to fix it. 
    	1	sudo mkdir -p /System/Volumes/Data/data/db (Create the data/db folder)
	2	sudo chown -Rid -un/System/Volumes/Data/data/db (Give permissions)
	3	mongod --dbpath=/System/Volumes/Data/data/db (Change dbpath of mongodb)

