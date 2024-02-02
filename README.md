# Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership

<img width="551" alt="transport pipeline" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership/assets/105381652/93dc7bfa-3782-4f58-9cb9-71c06d2528e2">


## Create resource group and resources
1. resoure group
2. azure data lake gen2
3. azure data factory
4. azure SQL Server Database + server (networking)

## ingest data inside adls container
1. upload parquet file inside the folder

## Extract, Transform, Load (ADF)
1. create linked services to connect to both ADLS & SSMS
2. add new dataset (for both ADLS & SQL DB)

<img width="944" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership/assets/105381652/a8c9691a-9054-406c-86ad-6e5e368d13f9">

<img width="921" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership/assets/105381652/7ce74431-9880-4e1d-9c7c-77b1f8085e39">

3. create a pipeline and set the source from the ADLS and sink from the SQL Server

<img width="886" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership/assets/105381652/f6123430-5284-47b5-88f1-e223c87920cd">

5.  run the pipeline and monitor of status

## open SSMS and connect to the server and check the table inside db/ or just open query editor

1. <img width="876" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Daily_Public_Transport_Ridership/assets/105381652/08194135-e9c3-4be1-acaf-24600ddfb9a1">

## connect to powerbi

1. open power bi desktop and connect to the source SQL Server

   


