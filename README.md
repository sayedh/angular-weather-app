# Angular Weather App
In this project I used Angular13 to build a weather app where the user can search and display any city around the world. 
![WeatherApp](https://user-images.githubusercontent.com/30685241/175099765-1a0d5444-7010-4829-bb2f-1d13d4d7444b.png)

## Technologies Used
* Angular
* Node (npm)
* Git
* RapidAPI (Open Weather Map)


## Dependencies
* Install Node - https://nodejs.org/en/download/
* Install Git - https://git-scm.com/download/win
* Install Angular13 - https://go.dev/doc/install
```
npm install -g @angular/cli@13
```

## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/sayedh/agular-weather-app
cd cache-project
```
* Add node modules to project files by runing comand
```
npm install
```
* Finally view the project locally, this will open up a page in your browser
```
ng serve -o
```


## Add your own Rapid API key
* Since this project uses the Open Weather Map API, you can add you own key to the code. 
* Log in/create account in RapidAPI and navigate to the Open Weather Map API and you will find your key in the X-RapidAPI-Key section. 
* Once you have your key, insert it into the environment.ts file at Line 11:
```
  XRapidAPIKeyHeaderValue: 'YOUR_KEY_HERE'
```

