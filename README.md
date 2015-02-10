# SBHacks-Oculus-Data-Explorer-
Top 5 SBHacks - Data Visualization Hack

Code - https://www.dropbox.com/s/r4ywoezvqav35vc/Data%20Explorer.zip?dl=0

Worked with James Vaughan (www.github.com/jamesbvaughan) 
at SBHacks (http://www.ucsbhacks.com/)

##Summary
What we've done is built a glimpse into the future of big data and virtual reality. We will need new, innovative ways to visualize and make sense of such immense data, Data Explorer is definitely one of those tools.

In the version we built at the hackathon, we pulled financial information from over 150 different cities in the United States, along with those cities' latitudes and longitudes from the OpenGov API, and generated a virtual 3D environment from that information for the user to explore. Each city is represented by a tower whose height corresponds to that city's income per capita. One of the features we're very proud of is that the distance between each city is proportional to their real world distances, so that as the user navigates the environment, they are navigating a scaled-down version of the real United States. The user starts in the center of the country and can move north, south, east, and west to the city of their choice and visualize the income per capita.

Our tagline : Feel your Data. Walking around data make it very personal and open itself up to new insights and epiphanies. In the example environment that we created, these insights will be related to the relative income of neighboring cities. We are hoping that these visualizations will spark new questions like, "Why is the income so varying in this geographically small area?" or "Why is there such a large income disparity in America? "

With Data Explorer, you can almost feel your data around you in this surreal experience. Words cannot describe this sensation. You simply have to try it.

##Files
- Blender
   - data.py : JSON data put in a python file
   - TowerGenerator.py : Python file that takes input JSON data (data.py) and converts it to 3D Models (hacks.blend)
   - hacks.blend : Blender file with 3D models of towers with labels
- Open Gov API 
   - index.html : AJAX requests pulling data from API
   - data.json : JSON data of city, latitude, longitude and income per capita
- DataDataData (Unity files)
   - Assets/OVR : Oculus/Unity Integration Package
   - **Data Explorer : File that starts Oculus App**

##Resources Used
- Javascript, Jquery
- Python
- Blender
- Unity
- Open Gov API (http://docs.governmententitiesapi.apiary.io/#)


