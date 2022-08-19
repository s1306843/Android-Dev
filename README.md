# Weather Forecast App

This app aims to 4 major things in relation to weather/geoclimate data that pertains to the user and their precise location. 

This Weather Forecast app is created in kotlin language
The App starts with a Starting Screen that contains the app name and its logo, with having added animation to them.  
Then, the app is taken to Navgigation Activity,where one has created Navigation drawer with the menu items to choose from:
1.Home
2.Maps
3.Settings
4.About
I have created fragments for each each menu items

Home -->

- The home screen is the main screen in which the user is greeted with, as well as the screen in which the user obtains all of the information relative to their geopositional location.
- The Navigation Activity opens with Home fragment it displays the weather Information like Temperature, Weather-type,min Temperature,max Temperature.
- Uses the Volley Library to fetch data from the OpenWeatherApi using Json get Request which in response returns the Json objects of the weather details.
- To get the date and time of the device one has used Calender class of java.

Maps -->

- Used mapActivity for the maps section of app one has integrated with gooogle maps Api.
- It can get location of any place whether you have set the location manually or used device location. This toggle button can be found in the settings tab.

Settings -->

- The user can choose to either use Device location or set location manually for getting the weather for the location.
- If the user wants to set location manually he/she needs to enter the city name and the country name. He/she needs to set which System of units does he want metirc or imperial and click Done to apply the changes.
1.Metric- °C , m/s
2.Imperial- °F , mph

About-->

- A set of strings that simply explains to the user what the application is all about and how to use it.
