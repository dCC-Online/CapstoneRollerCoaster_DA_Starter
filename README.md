# Capstone_DA_Starter
Starter data and materials for the Data Analytics Capstone Roller Coaster Case Study

## Data Set Information:
---
### There are **four** tables of data for this case study.  Two are included within this repository, while two are hosted in a remote MySQL database.

#### `steel_coasters.csv`
Contains Golden Ticket Award winners for steel coasters from 2010-2022, in a CSV file.
##### Columns:
    - Rank: The rank of award the coaster received
    - Year_of_Rank: The year the award was given
    - Award_Category: The category of awards (Steel or Wooden)
    - Name: Roller coaster name
    - Park: Name of amusement park where coaster is located
    - Location: Location of park, in mixed format
    - Supplier: The supplier of the roller coaster
    - Year_Built: The year the roller coaster was constructed
---
#### `wood_coasters.csv`
Contains Golden Ticket Award winners for wooden coasters from 2010-2022, in a CSV file.
##### Columns:
    - Rank: The rank of award the coaster received
    - Year_of_Rank: The year the award was given
    - Award_Category: The category of awards (Steel or Wooden)
    - Name: Roller coaster name
    - Park: Name of amusement park where coaster is located
    - Location: Location of park, in mixed format
    - Supplier: The supplier of the roller coaster
    - Year_Built: The year the roller coaster was constructed
---
#### `coaster_metrics`
Contains metrics for various roller coasters in a remote MySQL database.
##### Columns:
    - Coaster_ID: The unique identifier for each coaster in the database
    - Name: The name of the roller coaster
    - material_type: The material used to construct the coaster
    - seating_type: The type of seating the coaster uses
    - speed: The speed of the roller coaster, in MPH
    - height: The height of the roller coaster, in meters
    - length: The length of the roller coaster, in meters
    - num_inversions: The number of inversions for the roller coaster
    - manufacturer: The company that constructed the roller coaster
    - Park: The name of the park where the coaster is located
    - status: The current operational status of the roller coaster
---
#### `park_locations`
Contains the amusement park name and corresponding location info in a remote MySQL database.
##### Columns:
    - Park_ID: The unique identifier for each park in the database
    - Park: The name of the amusement park
    - City: The city where the park is located
    - State: The state (or province/region) where the park is located
    - Country: The country where the park is located
    - Zip_Code: The zip code where the park is located