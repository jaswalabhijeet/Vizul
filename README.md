Vizul - World Bank Data Graph
============
 [![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](http://safery.github.io/Vizul/) - [Click to Try the Website](http://safery.github.io/Vizul/)

Vizul is a pure Javascript based application that gets data from World Bank and visualizes those data into a graph.

![Chat Preview](http://i.imgur.com/74XUutB.jpg)

![Chat Preview](http://i.imgur.com/79hFd1W.png)

## Warning
Please note that the left side bar after searching for data has been taken out. To prevent no web scraping, The next update should implement an API based information for the country. It currently on display the selected country flag. If no flag is displayed, either this data was not World Bank, or there were no data available for this country.

## Recent Changes
* Made all text color black
* Fixed the CSS issue where it spawns the flag outside the left border
* Fixed JS where it deletes the whole div elements when user presses the back button
* Fixed the "live population data". Made it much more slower.

## Current Known Issues
* Some data don't plot on the graph.


---

## Features
- Material Design
- Pure JS supported, no need for PHP.
- AJAX support one page site.
- Animated Graph
- Country information
- Country Map
- Country Flag supported
- Changing background

---

## Setup
Really easy to set up, just download this repo and upload it to your server. Index.html contains the main page.

---

## Usage
The website makes a "XMLHttpRequest" to gather data from the World Bank servers. This means, the server is not implying on normal API GET request, such reason the algorithm tries to gather data from a 3rd party domain (World Bank). This is not a risk to user but it is a safe caution done by modern browsers to prevent any unwanted site from having securty issues. This site will not work on some modern browsers until users enable dev mode.

---

## License
This project is licensed under the terms of the **MIT** license.
