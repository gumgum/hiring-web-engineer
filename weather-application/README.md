General Web Application - Weather Mapping
======================================

In this exercise you will be creating a two part MVC application. One portion which will handle web service data ingestion, 
and one that will handle reporting tools and query generation.

Create a simple MVC vanilla php application using MySQL as a database that works with the following scenario:

* A database of cities populates a multiselect element on a page.

* The user can either select or deselect these cities.

* On a button click or form submit, an ajax request is sent to the web app containing a list of what cities the user has selected.

* The web application uses the openWeather API to ingest JSON and save it in a database containing the temperature and date this information was created for each of the selected cities.
    http://openweathermap.org/API
    
* On a separate page, use the google Geomap api to display markers of the temperature of the cities that were scraped from above.

* At the top of this page also output the last time the temperatures were scanned/updated.
    -- https://developers.google.com/chart/interactive/docs/gallery/geomap

* Add a query filter system based on some dropdowns on this page for city and temperature.
    -- This filter system allows the returned report data to be limited to only selected cities or temperatures based on what is in the database.

* Use a common php design approach such as singleton, command etc.

* Code should be cleanly aligned with all brackets, assignment operators etc lined up.

* Everything should be defined with the correct visibility.

* For database operations use the PDO abstraction layer.
    -- http://www.php.net/manual/en/book.pdo.php

================================================

Extra points for using bootstrap, foundation or other frontend toolkit.

Extra points for leveraging memcache for the reporting page.

Feel free to use any non-commercial frameworks or libraries, but please explain why you chose to use those libraries.