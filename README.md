# RPA-11-API-Integration-and-Data-Processing
### NAME:DHARUNYADEVI S
### REGISTER NUMBER:212223220018

## AIM:
To display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.

## ALGORITHM:
1.Get API Key from a weather provider (e.g., OpenWeatherMap).

2.Use Input Dialog to get the city name.

3.Create the API endpoint URL: Example: "https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric"

4.Use the HTTP Request activity:

* Method: GET
  
* URL: The full endpoint above

* Set Output to a variable (e.g., responseWeather)

5.Use Deserialize JSON to parse responseWeather.

6.Extract values like:

* Temperature: jsonObject("main")("temp").ToString
  
* Description: jsonObject("weather")(0)("description").ToString

7.Display the result in a Message Box.

## Program:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb9ed040-a3a8-42b6-b3ca-a80847a8a565" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e073e294-1fc7-4101-b484-b2e8c07c69c0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/77d2f552-14a7-4470-aea9-0f60eafa7078" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63e98212-25c6-4b0b-9b41-4d904cc7aaf0" />


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/976d274a-c11b-4357-bafc-5883ee6e49b1" />

<img width="344" height="305" alt="image" src="https://github.com/user-attachments/assets/f380fe94-5fc2-40ac-9f72-c512a7384df3" />

## RESULT:
Hence we display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.


