# Agritech Hackathon 2020 Pre Hack Challenge

Work done for the 2020 Agritech Hackathon pre hack challenge which focused on measuring activity and visitor origin/demographics to Charles Daley park in Niagara, ON.

https://agritechhackathon.ca/

### Step 1: Create wifi sign in splash page with postal code collection

  - basic HTML page with consent, terms and condidions, and postal code collection for display

### Step 2: Creating example postal code file of "visitors"

In QGIS:
  - create park point & 50kmtrade area around park
  - clip ON postal code file to 50 km trade area

In Python:
  - add a "visitor count" field and multiply based on inverse distance  to park point so we have higher counts closer to the park
  - remove geographies from postal code file and format into a list of postal codes - will act as the wifi login "output"

### Step 3: Bring postal codes into python script to append Census Tract areas / demographic data and create point file for heat map
