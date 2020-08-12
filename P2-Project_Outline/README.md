# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
<!-- Include overview here -->

> # ⚡ LightniNG
> **LightniNG is a free browser-based (eventually desktop) weather app that actually alerts you of the weather!**
>
> Weather decides many of our decisions, from what we spend, to what we do with our time, to where we want to go for business or leisure.
>
> There used to be all sorts of apps with recognized name recognition based on their brand that could alert you as to what the weather was like in your area and if there were storms in the vicinity. Now, just about every weather app just sits on your computer, sometimes not even for where you are. Almost none of them alert you of the local weather. And some times (in the case of Microsoft's Live tiles) not even updating the information.  What good is a weather app that doesn't tell you the current weather?
>
> **LightniNG** is a new app that notifies you of weather alerts in the area as they occur and can tell you what is going on in your area, using various sources.
>
> Users have control over what information they would like to see. Unlike other free weather apps that spend most of their time collecting user data for advertising but never giving them the vital information which was the reason they downloaded the app in the first place, Lightning gives user the power to opt out of marketing features (if those are ever implemented).  The user doesn't have to tell the app anything about where they are or what their computer is doing, they can simply get the weather, most of the data provided by the National Weather Service.
>
> *Use a weather app that give you power! ⚡ **Use LightniNG!***

### Features
<!-- Include Features here  -->

* Show forecasts for your area
* Get weather alerts in your browser based on location.
* Save places you want forecasts and notifications form
* Set what type of notifications you would like for specific areas.
* See local radar images.
* ***Secure!*** Uses HTTPS instead of HTTP.

### Technologies
<!-- Include Technologies here  -->

* [Angular](https://angular.io/)/[TypeScript](https://www.typescriptlang.org/)
* [Leaflet](https://leafletjs.com/)/[OpenStreetMaps](https://www.openstreetmap.org/)
* [OpenWeatherMap](https://openweathermap.org/)
* [MariaDB](https://mariadb.org/)
* <abbr title="National Oceanic and Atmospheric Administration">NOAA</abbr> <abbr title="National Weather Service">NWS</abbr> [National Digital Forecast Database](https://graphical.weather.gov/xml/rest.php)
  * A RESTful interface!

### What I'll Have to Learn
<!-- Include what you will need to learn here  -->

* What differences there are between MySQL and MariaDB.
  * MariaDB is a fork of MySQL. Basically, there were some folks a few years ago who were not happy Oracle bought MySQL.
  * Functionally, MariaDB should be no different from MySQL execpt for being Open Source. On the other hand, MariaDB does come with extensions that support JSON.
  * In 2013, Google moved from MySQL to MariaDB.
  * MariaDB [is compatible with MySQL](https://mariadb.com/kb/en/mariadb-vs-mysql-compatibility/) up to version 5.7 and is working toward 8.0 compatibility.
  * If fear of missing out is the reason to stick with Oracle and MySQL, you're not missing much as [MariaDB performs faster than MySQL](https://www.guru99.com/mariadb-vs-mysql.html).
* How to make a persistent Angular app. (Connect Angular with MariaDB)
  * The good news is that there is a [MariaDB](https://www.npmjs.com/package/mariadb) Node package.
* Use the [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)
  * MDN has a good API set up.
* Use the [Notifications API](https://developer.mozilla.org/en-US/docs/Web/API/notification)
  * MDN also has a good API for this. This will provide browser notifications.
* HTTPS
  * In order for those features to work, Secure HTTP (HTTPS) must be used as they will not work with HTTP.

### Project Tracker
<!-- Link to your Trello board here  -->

Follow my progress on [Trello](https://trello.com/b/u6vgjNE5/lightning-liftoff-project)
