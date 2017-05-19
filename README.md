# School Donations Dashboard

## What is Donations Dashboard?

This is an interactive data visualization dashboard which allows users to see the statistics of funding made to various classroom projects
run by various schools in USA for more than 10 years.

## How it works?

It provides the stats of various types like number of donations in any year , total number of donations , total amount of donation etc ,
for all states in US. 

![donation1](https://cloud.githubusercontent.com/assets/22799847/26249325/f802374c-3c9d-11e7-9ef4-ed5e546ade63.PNG)


User can get the stats for any particular state simply by selecting the state from dropdown menu or by selecting the state from the map.
All the stats will change depending on the state selected by the user.


![donation2](https://cloud.githubusercontent.com/assets/22799847/26249326/f81ab448-3c9d-11e7-890b-0391ae971112.PNG)

## Please Note

Since this dashboard uses a very big dataset , it could take some time to load the data first time therefore rendering of graphs could take a little bit of time.

# Tecknologies used

## Client Side

**languages :** HTML, CSS, JavaScript

**Framework and Library :**
* **Bootstrap:** CSS framework
* **Jquery:** JavaScript libarary
* **D3.js:** A JavaScript based visualization engine, which will render interactive charts and graphs based on the data.
* **Dc.js:** A JavaScript based wrapper library for D3.js, which makes plotting the charts a lot easier.
* **Crossfilter.js:** A JavaScript based data manipulation library that enables two way data binding.
* **Queue.js:** An asynchronous helper library for JavaScript.
* **Intro.js:** A JavaScript library to help user using the dashboard.

## Server Side 

**Language :** Python

**Framework : Flask**- A Python based  micro – framework  used to serve our data from the server to our web based interface.

**Packages :** 
* **hsaudiotag** - to process the meda data of audio files
* **django-cleanup** - for automatic cleanup of FileField and ImageField
* **django-gravatar2** 
* **Pillow** , and some more..



## Storage

**Database : Mongo DB**- NoSQL Database used to convert and present  data in JSON format.

**Hosting :** Heroku


