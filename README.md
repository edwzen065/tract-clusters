Run MetroClusterer.ipynb in the .zip file. Make sure to use the .zip file since it includes a .geojson file which is necessary for the program to run.

The program prompts the user four times.

**Cluster Scale Factor (Float): **
Represents the size of the clusters; Values around 0.1 recommended.

**Seed (Integer): **
Different seeds might not produce different outputs, just input an integer.

**Hide rural? (True/False): ** 
This moves all areas with at most 2 census tracts into a single cluster, essentially only showing urban clusters on the map.

**Keep borders? (True/False, removing borders is a bit ugly unfortunately): ** 
Shows outlines of census tracts. Keeping it on is recommended because removing them reveals gaps between census tracts.

The program creates an .html file in the same folder as the program. Run the file to show the map result.
