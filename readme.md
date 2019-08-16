# Vuejs and Nodejs Single Page Full Stack application

This is a simple project illustrating how to create a Single 
Page Application using Vuejs on the frontend and Nodejs on the backend. Basically  the app is a tracker application that tracks stats of a players from a tracker network  [tracker network](https://tracker.gg/developers).

We pass a request from the frontend to the backend , the backend reaches out to 3rd party API to get some data. 

## App Installation and Usage
* Clone the repo **git clone**
* Install node depedency modules using **npm install** . You must have nodejs installed in your machine.
* Create an account on this [website](https://tracker.gg/developers) and navigate to dashboard.
* Create a new application and add some details. After completion you will get an **API key**.
* Copy the API URl and API key and add in in **config.env** file in **TRACKER_API_KEY** and **TRACKER_API_URL**


## License
This program is free software published under the terms of the GNU [Lesser General Public License](http://www.gnu.org/copyleft/lesser.html).
You can freely use it for commercial or non-commercial purposes.