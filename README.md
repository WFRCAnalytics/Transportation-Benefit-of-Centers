# TDM-PP-Trip-Stats-by-SE-and-Transit-Intensity

To help quantify the transportation benefit of more centered development, stats were generated for different grouping of districts and also a html folium map showing transit lines and trips productions/attractions/ODs.

`Desnity-Mode-Share.ipynb` contains the following calcs/charts by Small District

- Household & Jobs per Acre vs Non-Motorized Share of All Trips
  ![image](https://github.com/user-attachments/assets/801a747d-a6a6-4028-a4ef-0ae3abf7cb52)

- Household & Jobs per Acre vs Transit Share of All Trips
  ![image](https://github.com/user-attachments/assets/b7fd56d2-562d-4217-a31f-4572a807057d)

- Distribution of Weighted Stop Density
  ![image](https://github.com/user-attachments/assets/57883a62-96f6-4922-9d6e-f03e4ca74c6d)

- Transit Mode Shares by Small District Household Density Categories:
  - All Households
  - \> 4 units per acre
  - \> 6 units per acre
 
  ![image](https://github.com/user-attachments/assets/babc2809-d66b-4806-ac9b-fea1ba58eaaf)


`Create-Transit-Map-From-Model-Data.ipynb` contains code to build HTML map showing TDM results for trips productions/attractions/ODs mapped with transit lines. Code programatically builds HTML file with embeded data with 6 tabs each with a map synchronized to all others.

![Screenshot 2025-04-07 114710](https://github.com/user-attachments/assets/b0932d84-c59e-4ad5-a849-512008fecbc0)
