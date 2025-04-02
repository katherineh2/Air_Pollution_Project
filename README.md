# Air_Pollution_Project

## Project Aims


## Contributers

Each of us was responsible for one step in the process, but all group members contributed to each part.

Data sourcing and Cleaning  - Delia - deliabel 
Analysis with Python  - Zaib - za1bahm3d
PowerBI Dashboard and Visualisations  - Dominika - Dlewan15


## Sourcing the Data

Sources:
I found the stations on the map, here:
https://www.scottishairquality.scot/
Zoomed into Glasgow, and compared it to the map of the LEZ here:
https://www.glasgow.gov.uk/LEZ


Townhead, Kerbside

(inside LEZ), Great Western Rd, High St (outside LEZ)
These four are on the Automatic Urban and Rural network, and I found the data here:
https://uk-air.defra.gov.uk/data/data_selector_service?show=auto&submit=Reset&f_limit_was=1

Here I selected: 
- Measured Data;
- Custom Date 01/01/2020 to 31/12/2024;
- Local Authority -> City of Glasgow -> [site name];
- Pollutant Name -> (ctrl) -Nitrogen Dioxide -PM10 particulate matter (Hourly measured) -PM2.5 particulate matter (Hourly measured);
- Data to email address (CSV), [enter email address].
- [get data] is on the right

Anderston, Byres road

These two are on the Locally Managed Automatic Monitoring, and I found the data by selecting that option on this map: 
https://uk-air.defra.gov.uk/interactive-map?network=nondefraaqmon

I then clicked on the station, and chose Download Data, which opened a different data selector:
https://uk-air.defra.gov.uk/data/datawarehouse

Here I selected:
- Local Authority;
- (ctrl) -Nitrogen Dioxide -PM10 particulate matter (Hourly measured) -PM2.5 particulate matter (Hourly measured);
- Custom Date 01/01/2020 to 31/12/2024;
- [step 2]
- Glasgow City;
- [step 3]
- [site name]
- Email (csv)
- [step 4]
- [enter email address]
- [get data]
