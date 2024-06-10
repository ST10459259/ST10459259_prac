# ST10459259_prac
Start
    Function getWeatherForecast(location)
        // This function retrieves the weather forecast for a given location
        // For simplicity, let's assume the forecast is retrieved from an external API
        forecast = ExternalAPI.getWeatherForecast(location)
        Return forecast
    End Function
        // This function displays the weather forecast
        Write "Weather Forecast:"
        Write "Temperature: " + weather.temperature
        Write "Description: " + weather.description
        Write "Wind Speed: " + weather.windSpeed
        Write "Humidity: " + weather.humidity
    End Function
    
    // Main program
    location = getUserLocation() // Assuming this function retrieves user's location
    weatherForecast = getWeatherForecast(location)
    displayWeather(weatherForecast)
End
