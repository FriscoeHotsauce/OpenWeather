# ProgrammingChallenge
Programming Challenge for Dwolla

## Introduction

The purpose of this project is to fetch the temperature from a remote web api.

## Technologies Used

Feign: A REST client that simplifies calls to REST services

Jackson: Used to parse json results

Maven: Package management for the project

[Open Weather](https://openweathermap.org/current): The REST service used to obtain weather data

[TravisCI](https://travis-ci.org/FriscoeHotsauce/OpenWeather): A continuous integration tool to automatically build commits as they happen.


## Instructions

In order to use this project, you must provide an API key for OpenWeatherMap. You can sign up and create a free API key at https://openweathermap.org/

Once you have obtained your API key, place it in the application.properties file (located under src/main/resources) as such `apikey=xxxx` where xxxx is your api key.

When importing the project from github, intellij should prompt you to import it as a maven project.

In order to run the project, simply press play from the Application.java class in your Intellij IDE, or the use the command `mvn install` from the terminal to build a Jar.

## How to Use

To use this project, simply boot it up through one of the previous methods. You will be prompted to provide the name of the city you want the weather for. Basic error handling is provided for invalid API keys as well as your city not being found.