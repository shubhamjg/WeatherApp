# WeatherApp

This is a simple weather information application developed in android studio.
Please use your own API_KEY to successfully run the application.

https://openweathermap.org/

register on this website to get the API_KEY for you.

Paste the API_KEY in CurrentWeatherService class

public class CurrentWeatherService {

    private static final String TAG = CurrentWeatherService.class.getSimpleName();

    private static final String URL = "https://api.openweathermap.org/data/2.5/weather";
    private static final String CURRENT_WEATHER_TAG = "CURRENT_WEATHER";
    private static final String API_KEY = "YOUR API KEY HERE"; <--- INSERT API KEY HERE
