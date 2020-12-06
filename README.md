The assignment is tricky to get it right first time itself but very good learning experience. The project is split for some reason into three parts and requested to be submitted as three parts too. Hence we have # Week3_CapstoneProject_Part1, Part2, Part3 as assignments. Please note each python notebook is an incremental update to the previous named version due to that. 
I suggest to redo the labs again and again that way doing this project will be easy. Please install first itself the libraries to use beautifulsoup package using the below commands. 
!pip install beautifulsoup4
!pip install lxml

Also for getting the coordinates from google try running the updated version like below. geopy first time did not work for me. 
#!conda install -c conda-forge geopy --yes 
from geopy.geocoders import Nominatim # module to convert an address into latitude and longitude values

The Part3 at the end I have analyzed 5 clusters of Toronto data and provided my recommendation as Cluster 0 as the best option as I like staying in calm place but still a place that has accessibility to restaurants, shops, fast food, most importantly parks and hiking trails. In addition Cluster 0 provides an option for dog run and swim school too. 

My assignment might have extra commands tried as I was trying to get the same data through couple of means to learn better. Instead of completely following the NewYork assignment I was trying to play around myself and made multiple syntax and logical mistakes only to learn more. For example, the color option in the Folium Circlemarker does not accept a float as a color option. I was playing around with round function or other options that might remove the float. Finally I ended up giving which color I want to choose. 

Overall this was a worthy learning experience. Thanks to IBM and authors for putting up this course material. 
