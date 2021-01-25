
# Online Offline Budget Tracker

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
    
## Description
This is a budget tracking app.  Users are able to enter expenses and deposits which are tracked by date and time.  Data for this app is stored using mongodb and a mongoose schema.  User data is collected using html inputs, which will work when the page is offline, as well as online.  I used a `service-worker.js` file to create a cache for the files that are required to keep the app functioning while offline.  Cache files data is stored in a machine’s local memory and may still collect data using `indexdb` to be used later when the page reconnects to the internet.  Once this app is back online, data in `indexdb` will be pushed to the mongodb where the user's data is collected and saved.  Using these methods creates a progressive web application that remains functional whether a user is on or offline.  This budget tracker is perfectly suited for smartphones that will travel in and out of internet coverage.     

## Installation
This app requires the following dependencies to be installed, `compression` , `express` , `lite-server` , `mongoose` , and `morgan.`  A mongodb connection is established to store user data.

## Usage
This application may be used while on or offline.  Users enter their expenses and deposits to track cash flow by date and time.  While offline data is stored locally until a connection can be reestablished. 

<img src = "BudgetTrackerGif.gif" />

<br>

[Link to Deployed Site](https://sleepy-wave-24018.herokuapp.com/)

## Contributors
Ben Robinson

## Testing
NA

## License: 

For more information about the license click on the link below. 


[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
    
### Questions: 

![GitHub Logo](GitHub-Mark-32px.png)
[GitHub Profile](https://github.com/Tarbo13)

If you have additional questions please email me **mailto:**<robinson.dri@gmail.com>

### Table of Contents:
- [Description](#Description)
- [Installation](#Installation) 
- [Usage](#Usage)
- [Contributors](#Contributors)
- [Testing](#Testing)
- [License](#License)
- [Questions](#Questions)