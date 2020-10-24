# AgritechHackathon2020
Work done for the 2020 Agritech Hackathon

### Step 1: Creating example postal code file of "visitors"

In QGIS:
  - create park point & 50kmtrade area around park
  - clip ON postal code file to 50 km trade area
  - add a "visitor count" field and multiply based on inverse distance  to park point so we have higher counts closer to the park
  - remove geographies from postal code file and format into a list of postal codes - will act as the wifi login "output"

### Step 2: Bring postal codes into python script to append Census Tract areas / demographic data and create point file for heat map
