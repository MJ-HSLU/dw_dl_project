# Analysis of the impact of weather on traffic patterns for the city of Zurich

Authors: Yanik Baumann & Michael Jung

This project is part of the MScIDS course "Data Warehouse and Data Lake systems" at the Lucerne University of Applied Sciences and Arts (HSLU) Switzerland.


## Project Description

This project investigates the relationship between traffic patterns and weather conditions in the city of Zurich, Switzerland.
The goal is to understand if and how different weather and traffic events are correlated.
Finally, using LLM's, we will try and predict traffic flow based on a given weather pattern.

## Data Sources
- Traffic data: Collected via API from HERE over a period of one month (https://developer.here.com/develop/rest-apis)
- Weather data: Collected via API from Openweather over a period of one month (https://openweathermap.org/api)


### Methods Used and Technologies

The project involves the following key technologies:

1. Python
2. AWS Cloud Technologies (S3, Lambda, RDS, Cloud9)
3. Generative AI models ('llama3' via Ollama in a virtual machine provided by the lecturers https://ollama.com/)

This repository contains all of the Python code we used in this project.
The code will not executute properly if run in a local IDE. It was created explictely for AWS lamda functions.


## Folder and Files Navigator:

- Data folder: Weather and traffic files were logged as JSON files and saved directly to S3 for further processing. This folder is a backup
- Notebooks: Various Jupyter notebooks containing the code we used to fetch the data, store and analze it.
- Project proposal (PDF)
- Midterm presentation (PDF)
- Final presentation (PDF)
- Final report (PDF)


## Contributing Members

 - [Michael Jung](https://github.com/MJ-HSLU)
 - [Yanik Baumann](https://github.com/kre8tivz)
