# Earthquake-Data-Engineering-Project-with-Microsoft-Fabric

Project Overview
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
An end-to-end project to showcase data engineering and analysis pipelineutilising Microsoft Fabric’s Data Factory, Data Engineering, and Power BI experiences.

Ingesting Earthquake events data from [usgs](https://www.usgs.gov/programs/earthquake-hazards).

Technologies Used: Python, PySpark, Fabric (Data Engineering, Data Factory, Power BI)

<img width="1351" height="757" alt="image" src="https://github.com/user-attachments/assets/43ad0c73-8512-4ef5-b421-e1f4ab7becc5" />

Getting Started
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
To get started with this project, download the notebooks in the repository and follow the guidance provided in the YouTube tutorial.

Repository Contents
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Worldwide Earthquake Events API - Bronze Layer Processing: This notebook focuses on ingesting raw earthquake data from the USGS API. It performs minimal processing to store data in its original format, serving as the foundational layer for further refinement.

Worldwide Earthquake Events API - Silver Layer Processing: This notebook enhances the data from the Bronze layer by cleaning, transforming, and consolidating it. It prepares the data for more analytical processing.

Worldwide Earthquake Events API - Gold Layer Processing: In this final processing stage, the notebook refines the data to create business-ready datasets. These are optimized for high-value insights and are tailored for specific analytical purposes, such as reporting and visualization in tools like Power BI.

Data Attribute Definitions
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Worldwide Earthquake Events API - Bronze Layer Processing: This notebook focuses on ingesting raw earthquake data from the USGS API. It performs minimal processing to store data in its original format, serving as the foundational layer for further refinement.
id: A string identifier for each data record.

latitude: The latitude of the event, stored as a double.

longitude: The longitude of the event, also stored as a double.

elevation: The elevation at which the event occurred, expressed in meters, stored as a double.

title: A string representing the title or name of the event.

place_description: A string describing the location of the event.

sig: A bigint (large integer) representing the significance score of the event.

mag: A double indicating the magnitude of the earthquake.

magType: A string describing the type of magnitude scale used.

time: A timestamp marking the exact time of the event.

updated: A timestamp indicating the last update time for the event data.

Prerequisites
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Microsoft Fabric Account.
Fabric Administrator (or access to an individual with an Admin account).
Familiarity with Python, Spark, and basic data engineering concepts.
Basic Power BI skills.

License
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project is licensed under the [MIT License](License). 

About me
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Hi there! I'm Shreta Chandni. I am a Health-case IT professional on a mission to keep learning and skill up as long as possible. Let's stay in touch! Feel free to connect with me shally2009@gmail.com
