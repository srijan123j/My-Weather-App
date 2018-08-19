# My-Weather-App
Android App

This is an android app which gives information about the current weather conditions and the weather forecast of the users' location which they can also share.
</br>Functionalities of the app include:-
<ol>
<li>Users can select any location about whose weather conditions they want to know.</li>
<li>The app gives the information about the current weather in both the Celsius and the Fahrenheit scales.</li>
<li>The app also gives the information about the Humidity level, Pressure and the wind speed.</li>
</ol>
</br>To make the users' experience better some of the best practices followed in the market are used, such as:-
<ul>
<li>Shared Preference is used to store and save users' preferences of the weather scale and users' location</li>
<li>The implicit intent is used to facilitate the users to share the weather conditions with others.</li>
<li>RecyclerView was used instead of the simple linear layout to display the weather forecast so that resources of Android phones such as RAM are used efficiently.</li>
<li>AsyncTask Loader is used for fetching the weather data from the internet.</li>
</br>The weather data is gathered from <a href="https://openweathermap.org/">OpenWeatherMap</a> by using their public API.
