# The Very Unique Weather App ;)
![build status](https://github.com/praisetompane/the_very_unique_weather_app/actions/workflows/the_very_unique_weather_app_merge.yml/badge.svg) <br>
A toy simple weather application to experiment with the full life-cycle of a React Single Page Application.

### Application Tour

##### 0. Homepage
![Alt text](/previewimages/homepage.png?raw=true "Optional Title")

##### 1. Retrieve 5 day weather forecast

![Alt text](/previewimages/fivedayweather.png?raw=true "Optional Title")

##### 2. Drill down to 3 hour interval weather forecasts
![Alt text](/previewimages/hourlyweather.png?raw=true "Optional Title")

##### 3. Drill into the details of a specific hourly forecast
![Alt text](/previewimages/detailedweather.png?raw=true "Optional Title")

##### You can find the deployed version of the application here: [the-very-unique-weather-82ed7.web.app](https://the-very-unique-weather-82ed7.web.app)

## Getting the App to Work Locally
### Prerequisites
You need to install NodeJS to run this program locally. Visit the official NodeJS website for how to do this.

### Note: You need to be in the project's folder when executing any of these comamnds

### Installing the application dependencies(You need to be connected to the internet for this)

```shell
# from root directory
pnpm install 
```

### Running the tests
```shell
# from root directory
pnpm run test
```

### Running the app locally(You can  find it here in your web browser: localhost:8080)

```shell
# from root directory   
pnpm run start
```

### Building the app for production deployment
```shell
# from root directory   
pnpm run build
```

### Building and deploying using Firebase
```shell
# from root directory   
pnpm run deploy
```
### Authors
   Praise Tompane
      
### Licence
    This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details
    
### Acknowledgments

##### Thanks to https://github.com/tylermcginnis/react-fundamentals-curriculum for the base style sheet
