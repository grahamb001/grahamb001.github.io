<!doctype html>
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=2, shrink-to-fit=no">
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
        <title>Latitude Dashboard</title>
    </head>
    <body>

      <!--title-->
        <div class="container" style="title">
          <a class="navbar-brand" href="index.html">Latitude</a> 
        </div>
      <!--/title-->

        <!--navbar-->
        <div class="container" style="margin-top:10px">
            <ul class="nav nav-tabs">
                <li class="nav-item">
                  <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">Plots</a>
                  <div class="dropdown-menu">
                      <a href="temp.html" class="dropdown-item">Max Temperature</a>
                      <a href="humidity.html" class="dropdown-item">Humidity</a>
                      <a href="cloud.html" class="dropdown-item">Cloudiness</a>
                      <a href="wind.html" class="dropdown-item">Wind Speed</a>
                  </div>
                  <li class="nav-item">
                      <a href="#" class="nav-link">Comparison</a>
                  </li>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">Data</a>
                </li>
                <li class="nav-item">
                </li>
            </ul>
        </div>
        <!--/navbar-->

    <!-- container -->
    <div class="container pt-5">
      <!-- row -->
      <div class="row">

        <!-- summary -->
        <div class="col-lg-7">
          <h1 class="mb-4">Summary: Latitude vs. X</h1>
          <hr class="mr-4">
          <img class="p-3" src="Resources/assets/images/Fig1.png" alt="vs. max temperature" height="280" align="left">
          <p>The purpose of this project was to analyse how weather changes as you get closer to the equator. To 
            accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset on more
            than 500 cities
          </p>
          <p>After assembling the dataset, we used MatPlotLib to plot various aspects of the weather vs. latitude.
            Factors we looked at incuded temperature, cloudiness, wind speed, and humidity. This site provides the source 
            data and visualizations created as part of the analysis, as well as explanations and descriptions of any 
            trends and correlations witnessed. 
          </p>
        </div><!-- /summary -->
                
        <!-- visualizations -->
        <div class="card col-lg ml-3 mr-3 mb-3">
          <h3 class="pb-4">Visualizations</h3> 
          <div class="row justify-content-center">
            <div class="col-lg-5 col-sm-3">
              <div class="card mb-3">
                <a href="temp.html" >
                  <img class="card-img-top" src="Resources/assets/images/Fig1.png" alt="vs. Max Temp">
                </a>
                <div class="card-body">
                  <h6 class="card-title text-center">Max Temp</h6>
                </div>
              </div>
            </div>

            <div class="col-lg-5 col-sm-3">
              <div class="card mb-3">
                <a href="humidity.html" >
                  <img class="card-img-top" src="Resources/assets/images/Fig2.png" alt="vs. Humidity">
                </a>
                <div class="card-body">
                  <h6 class="card-title text-center">Humidity</h6>
                </div>
              </div>
            </div>

            <div class="col-lg-5 col-sm-3">
              <div class="card mb-3">
                <a href="cloud.html" >
                  <img class="card-img-top" src="Resources/assets/images/Fig3.png" alt="vs. Cloudiness">
                </a>
                <div class="card-body">
                  <h6 class="card-title text-center">Cloud Cover</h6>
                </div>
              </div>
            </div>

            <div class="col-lg-5 col-sm-3">
              <div class="card mb-3">
                <a href="wind.html" >
                  <img class="card-img-top" src="Resources/assets/images/Fig4.png" alt="vs. Wind Speed">
                </a>
                <div class="card-body">
                  <h6 class="card-title text-center">Wind Speed</h6>
                </div>
              </div>
            </div>
          </div>
        </div><!-- /visualizations -->
      </div><!-- /row -->
    </div><!-- /container -->

    <!-- bottom bar -->
    <footer class="footer">
        <div class="container-fluid">
        </div>
      </footer>

        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    
</body>
</html>
