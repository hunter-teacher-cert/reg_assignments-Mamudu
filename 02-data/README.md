# In this exercise, you will analyze data mapping by looking at the path of a wild seal.

In geography, longitude represents the x-axis or movement horizontally, and latitude represents the y-axis or movement vertically (in other words, how far you are from the equator).  Latitude increases as you go north and the longitude gets larger as you go west for this area of the globe.

For example, the coordinates for Times Square in New York City are Latitude 40.7577° N, Longitude 73.9857° W.


The tracking data for a gray seal named Muskeget can be found here:

WhaleNet/Seal STOP Data (Links to an external site.) ------- http://www2.whalenet.org/whalenet-stuff/Stop39395-18/data39395-18.html

This data table lists dates that the seal's location was tracked, along with his latitude and longitude on that date.  You can take any one of these points and plug it into Google Maps and see the seal's location.  On January 30th, 2018, written as 30.01.18 in the data set, he is near Nantucket, shown as a red pin on the map below:

Muskeget_Google_Map.png

Another gray seal, Gracie, has also been tracked recently, using a tracking microchip attached to her flipper. This allows scientists to track her movement in the ocean to see her exact location. The following lines of code represent the latitude and longitude of Gracie's location over time.

lat = [40.59, 40.52, 40.621, 40.519, 40.56, 41.265, 40.61, 40.806, 41.259, 41.265, 41.264, 41.264, 41.259, 41.262, 41.263]
lon = [69.532, 69.419, 69.354, 69.263, 69.478, 70.805, 69.706, 70.331, 70.815, 70.823, 70.815, 70.81, 70.824, 70.811, 70.811]

The lat list indicates how far north and south Gracie the seal has traveled, and the long list represents how far east and west she has traveled.  The larger the latitude value, the further north the seal was located, and for this area of the world, the larger the longitude value, the further west the seal is located.

# Write a program to calculate the farthest in each direction that Gracie was located throughout her travels.  Add four print statements to the lines of code above that output the following, where the number signs are replaced with the correct values from the correct list:

Farthest north = #

Farthest west = #

Farthest south = #

Farthest east = #
