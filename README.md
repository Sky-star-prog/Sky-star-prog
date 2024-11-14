<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <title>My Weather Application</title>
</head>
<body>
 <div class="weather-app">
   <header>
     <form id="search-form">
       <input type="search" placeholder="Enter a city.." required class="search-input" id="search-input" />
       <input type="submit" value="Search" class="search-button" />
     </form>
   </header>
   
   <main>
     <div class="current-weather">
       <div>
         <h1 class="current-city" id="current-city">Paris</h1>
         <p class="current-details">
           <span id="current-date"></span>, moderate rain <br />
           Humidity: <strong>87%</strong>, Wind: <strong>7.2 km/h</strong>
         </p>
       </div>
       <div class="current-temperature">
         <span class="current-temperature-icon"></span>
         <span class="current-temperature-value" id="current-temperature">24</span>
         <span class="current-temperature-unit">°C</span>
       </div>
     </div>
   </main>
   
   <footer>
     <p>
       This project was coded by
       <a href="https://github.com/Rennish" target="_blank">Rennish Mboya</a> and is
       <a href="https://github.com/Rennish/Weather-APi-Correct" target="_blank">on GitHub</a> and
       <a href="https://beautiful-kiten-9b7d1e.netlify.app/" target="_blank">hosted on Netlify</a>
     </p>
   </footer>
 </div>
</body>
</html>
