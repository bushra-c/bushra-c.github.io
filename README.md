String webpage = R"rawliteral(
<!DOCTYPE html>
<html>
 <head>
   <title>Sensor Data</title>
   <style>
     /* Banner style */
     .banner {
       background-color: #4CAF50; 
       color: white; 
       text-align: center; 
       padding: 10px; 
       font-size: 24px;
     }
   </style>
 </head>
 <body style="background-color: #F5F5DC;">
   <!-- Banner -->
   <div class="banner">
     Plant Sensor Data Dashboard
   </div>
   
   <h1>Real-Time Sensor Data</h1>
   <p><strong>Download sensor data as a CSV file:</strong></p>
   <a href="/download" download="sensor_data.csv">
     <button type="button">Download CSV</button>
   </a>
   <p>The CSV contains:</p>
   <ul>
     <li>Air Temperature (C)</li>
     <li>Air Humidity (% RH)</li>
     <li>Soil Moisture (%)</li>
   </ul>
 </body>
</html>
)rawliteral";





