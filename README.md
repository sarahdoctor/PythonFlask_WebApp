# PythonFlask_WebApp
 ChatGPT ChatGPT The project is designed to apply Python's data manipulation capabilities, focusing on transforming a CSV file into a filtered dataset and subsequently rendering it as a web interface via Flask. It serves as a practical exercise to solidify understanding of Python's data structures and web development framework.


### Overview

This project demonstrates the application of Python to data manipulation and web presentation, employing libraries like Pandas and Flask.

### Steps to Execute

#### Data Preparation
Read the provided Crunchbase Open DataMap CSV into a Pandas DataFrame.
Remove any records with missing company names.
#### Data Analysis
Output the count and the first 10 records of the cleaned DataFrame.
Filter the records to include only USA-based companies starting with "ad" and perform the same output operations.
#### Data Conversion and Storage
Convert the filtered DataFrame to a list of JSON objects.
Write this list to a JSON file, ensuring each record is on a new line for readability.
#### Data Retrieval
Read the JSON file back into a Pandas DataFrame.
Filter for New York-based companies and output the count.
#### Web Presentation
Utilize Flask to create a web page displaying the final set of records.
Run the Flask server to view the results on a local web browser.
