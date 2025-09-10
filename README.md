# Safe-Bluebikes-Finder
When finding a Bluebike station, it is often assumed that the closer the station, the better. However, this application proves that being closer is not always better. By interacting with this app, users will be able to gauge whether it is worth it to travel to a farther station with a higher safety score rather than settle for a closer station that is in an area more prone to accidents and fatalities.

Essentially, Safe Bluebike Finder is a web app that helps you find safe Bluebike stations around Boston. Each Bluebike station is assigned a safety score which is calculated based on publicly available datasets on bike accidents and bike fatalities. After the user inputs their location, Safe Bluebike Finder will display all Bluebike stations within a 0.5-mile radius with their corresponding safety scores. By clicking on a station, users can see bike accident and bike fatality data for the area around the station.

Please contact me directly to view the source code.

## Main Interface 
<img width="1060" height="641" alt="image" src="https://github.com/user-attachments/assets/d6287445-955a-49b3-8c48-d3740724860f" />
<i>(light mode of the main interface, where the blue pin represents the user and the other pins represent Bluebikes station with colors indicative of safety scores (a spectrum from red -> green, representing dangerous -> safe) <i>


## Bluebikes Station Information Modal
<img width="1048" height="641" alt="image" src="https://github.com/user-attachments/assets/a5c767bb-daeb-4aab-928b-57796698d725" />
<i>(dark mode display after clicking on a specific Bluebikes station in the sidebar, showing descriptive stats such as number of accidents, number of recent accidents (within 12 months), and directions to the station on the right) <i>

## Other Features
* View a Google Maps route to your selected station 
* Detect your current device location
* Show or hide bike lanes on the map
* Switch between light and dark mode

## Data Sources
* [Bluebikes Station Data](https://bluebikes.com/system-data)
* [Boston Bike Accident Records](https://data.boston.gov/dataset/vision-zero-crash-records)
* [Boston Bike Fatality Records](https://data.boston.gov/dataset/vision-zero-fatality-records)
