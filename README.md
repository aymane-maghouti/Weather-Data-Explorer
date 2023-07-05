# Weather Data Explorer and Web App
This project is a simple Python-based application that retrieves weather data, performs data analysis, and presents the results through data visualization and a web application built with Flask.

## Features
- Data retrieval: The application fetches weather data from an external source (https://public.opendatasoft.com/explore/?sort=modified).
- User interaction: Users can enter a station name and a date for retrieving specific weather data.
- Data processing: The station name is converted to uppercase, and the date input is validated.
- Data loading and storage: The retrieved weather data is stored in both JSON and CSV formats.
- Data visualization: The application generates a bar chart using the temperature data and displays it using the matplotlib library.
- Web application: The application includes a Flask web application.

## Prerequisites
Python 3.x
Required Python libraries: datetime, json, requests, os, csv, matplotlib, pandas, Flask
Installation
Clone or download the project repository.
Install the required Python libraries using pip:

`pip install datetime json requests matplotlib pandas Flask`

note that in this project I am working on the data of a city (Nantes), of course we can change the city (the python code provided in the beginning to enter the name of the station).
also note that you must change the path where the data folder will be created (add the appropriate path for your computer).

