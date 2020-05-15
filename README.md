# WeatherPy

The Python scripting here provides the groundwork for a future PlanMyTrip app. This project implements making an API call to gather a weather dataset, visualizing it using Google Maps, and then adding a directions feature for a customer to locate the nearest hotels in an area.

Table of contents
=================

<!--ts-->
   * [Introduction](#Introduction)
   * [Background](#Background)
   * [Tools](#Tools)
<!--te-->

# Introduction

This challenge harnesses existing programming skills using try-except blocks, input statements and nested decision statements, and logical expressions. Python and the Pandas library's methods and attributes allows for this project to make an API request and build a new DataFrame. This project alters the DataFrame to create a marker layer map, and a directions layer Google map that shows directions to travel between multiple cities.

# Background

For the new modications to the PlanMyTrip app, more data must be added onto the database, or cities DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. The project accounts for the amount of rainfall or snowfall within the last three hours so that customers can alter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, the project creates a directions layer Google map that shows the directions between multiple cities for travel.

# Tools

The following tools have been used for this challenge:
* Use Pandas methods and attributes on a DataFrame or Series.
* Gmap library's pop-up markers
