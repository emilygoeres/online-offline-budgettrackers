# online-offline-budgettrackers

## Description
<!-- ### Deployed link: https://egfitnesstracker.herokuapp.com/  -->
### Deployed Link: https://drive.google.com/file/d/1kHznhu2eQZNh5iYvpKOiDQQJ6dWg-Qr-/view
Traveling somewhere for vacation? Traveling sometimes takes you to a dirt road with no cell reception. Have no fear, track your finances with our budget tracker offline while traveling the dirt road and online once you get back into the big city.

## Table of Contents
1. [Description](#-Description)
1. [Technologies](#Technologies)
1. [Installation](#Installation)
1. [Steps](#Steps)
1. [Authors](#Authors)
1. [License](#License)

## Visuals 

![budgettracker](https://github.com/emilygoeres/online-offline-budgettrackers/blob/main/budget.PNG)

## Technologies 
* Heroku
* MongoDB Atlas
* Rendering

## Installation
1. Clone this repository to your local machine. 
1. Ensure server.js is enabled in the directory to which you have saved this repository. 
1. Install all npm packages. Modify the config.json to work with your own sql.  
    
## Steps
1. Create routes to home and index file
2. Create alll of the different routes to each file in app
3. Installed image cache to ensure images only load if on screen while using app
4. Tell the browser to activate this service worker immediately once it has finished installing
5. If response was good clone/store it to cache
6. Network request failed, try to get it from the cache
7. Deployed app on Heroku 

## Author

[Emily Goeres](https://github.com/emilygoeres)

## License 

MIT License

Copyright (c) 2020  Emily Goeres

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.