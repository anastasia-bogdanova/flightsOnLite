# Flights on Lite
## Overview
Flights on Lite aims to make travel accessible to everyone by focusing on low-cost airlines and simplified travel options. The project retrieves and displays flight data using Amadeus airline APIs to showcase affordable travel opportunities. The goal is to highlight that flights can be an inclusive and cost-effective mode of travel for everyone.

## Instructions for the reviewer to run the project

### Online Version
0. Go to https://anastasia-bogdanova.github.io/flightsOnLite
1. Enter airport names, type at least 2 first letters. (NYC and Miami are pretty popular.)
2. Select the airport from the dropdown.
3. Select departure date by clicking on the calendar icon.
4. Select return date by clicking on the following calendar icon.
5. Enter number of travelers or use arrows.
6. Click on the "Search" button.
7. See a list of direct flights sorted from low to high price.

### Run locally
0. Clone the project repository `gh repo clone anastasia-bogdanova/flightsOnLite`
1. Navigate to the project directory: `cd FlightsOnLite`
2. Open the project in a code editor (For Visual Studio Code use `code .`)
3. Use Live Server to access index.html - "Flights on Lite" page.
4. Enter airport names, type at least 2 first letters.
5. Select the airport from the dropdown.
6. Select departure date by clicking on the calendar icon.
7. Select return date by clicking on the following calendar icon.
8. Enter number of travelers or use arrows.
9. Click on the "Search" button.
10. See a list of direct flights sorted from low to high price.

## Features

#### Use arrays, objects, and maps to store and retrieve information.
Flights on Lite uses an array of objects to manage flight data retrieved from the API. Each object represents an individual flight, including details like airport name, price, departure time, and arrival time.

#### Visualize data in a user friendly way.
Flights on Lite retrieves data from the API in arrays, filters out only the essential details, and displays the information in a clear and simple tile layout. The search details are shown at the top of the screen. The price and time take up more space in the tile, helping users focus on the most critical information.

#### Convert user input between two formats and display the result.
The project has functions that take departure and arrival dates, get information from the API in ISO format to display departure and arrival times shown in 24-hour format.

#### Retrieve and display data from a third-party API and  and use it to display information.
The page retrieves live flight data from the Amadeus API to display available direct flights. It also uses the Amadeus Airport & City Search API to provide autocomplete suggestions as users type airport names, requiring at least 2 characters to start showing matching airports.
