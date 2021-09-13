<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="logo.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/weather-icons/2.0.9/css/weather-icons.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/balloon-css/0.5.0/balloon.min.css">
    <script src="https://use.fontawesome.com/389802374e.js"></script>
    <title>Weather App</title>
</head>

<body>
    <!-- Header -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <a class="navbar-brand">
                <img src="icon.svg" width="30" height="30" alt="">
                <a class="navbar-brand">WeatherApp</a>
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor01" aria-controls="navbarColor01"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarColor01">
               &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
                <form id="meteo-form" class="form-inline my-2 my-lg-0">
                    <div id="search-loading" class="loading">
                        <div></div>
                    </div>
                    <span id="geolocation" data-balloon="Geolocate me!" data-balloon-pos="down">
                        <i class="fa fa-crosshairs"></i>
                    </span>
                    <input name="meteo-city" class="form-control mr-sm-2" placeholder="City" type="text">
                    <button class="btn btn-secondary my-2 my-sm-0" type="submit">Search</button>
                </form>
            </div>
        </nav>
    </header>
    <!-- Content -->
    <div class="container">
        <h2 id="meteo-title">
            <span>
                Weather in <a href="https://www.google.fr/maps/search/gwalior" class="text-muted meteo-city" target="_blank">Gwalior</a>
            </span>
        </h2>
        <section class="section-meteo row">
            <div id="meteo-day-1" class="meteo-day col-sm">
                <h3><span class="name">Day 1</span> <span class="text-muted date">--/--</span></h3>
                <div class="meteo-block row meteo-temperature-container">
                    <div class="meteo-temperature">
                        <i class="wi wi-night-sleet"></i>
                        <span class="data">--°C</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-humidity">
                        <div class="meteo-block-title">
                            <i class="fa fa-tint" aria-hidden="true"></i>
                             Humidity
                        </div>
                        <div class="meteo-block-data">--%</div>
                    </div>
                    <div class="col meteo-block meteo-wind">
                        <div class="meteo-block-title">
                            <i class="fa fa-flag" aria-hidden="true"></i>
                            Wind
                        </div>
                        <div class="meteo-block-data">-- km/h</div>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-sunrise">
                        <div class="meteo-block-title">
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunrise
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                    <div class="col meteo-block meteo-sunset">
                        <div class="meteo-block-title">                      
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunset
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                </div>
            </div>
            <div id="meteo-day-2" class="meteo-day col-sm">
                <h3><span class="name">Day 2</span> <span class="text-muted date">--/--</span></h3>
                <div class="meteo-block row meteo-temperature-container">
                    <div class="meteo-temperature">
                        <i class="wi wi-night-sleet"></i>
                        <span class="data">--°C</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-humidity">
                        <div class="meteo-block-title">
                            <i class="fa fa-tint" aria-hidden="true"></i>
                             Humidity
                        </div>
                        <div class="meteo-block-data">--%</div>
                    </div>
                    <div class="col meteo-block meteo-wind">
                        <div class="meteo-block-title">
                            <i class="fa fa-flag" aria-hidden="true"></i>
                            Wind
                        </div>
                        <div class="meteo-block-data">-- km/h</div>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-sunrise">
                        <div class="meteo-block-title">
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunrise
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                    <div class="col meteo-block meteo-sunset">
                        <div class="meteo-block-title">                      
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunset
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                </div>
            </div>
            <div id="meteo-day-3" class="meteo-day col-sm">
                <h3><span class="name">Day 3</span> <span class="text-muted date">--/--</span></h3>
                <div class="meteo-block row meteo-temperature-container">
                    <div class="meteo-temperature">
                        <i class="wi wi-night-sleet"></i>
                        <span class="data">--°C</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-humidity">
                        <div class="meteo-block-title">
                            <i class="fa fa-tint" aria-hidden="true"></i>
                             Humidity
                        </div>
                        <div class="meteo-block-data">--%</div>
                    </div>
                    <div class="col meteo-block meteo-wind">
                        <div class="meteo-block-title">
                            <i class="fa fa-flag" aria-hidden="true"></i>
                            Wind
                        </div>
                        <div class="meteo-block-data">-- km/h</div>
                    </div>
                </div>
                <div class="row">
                    <div class="col meteo-block meteo-sunrise">
                        <div class="meteo-block-title">
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunrise
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                    <div class="col meteo-block meteo-sunset">
                        <div class="meteo-block-title">                      
                            <i class="fa fa-sun-o" aria-hidden="true"></i>
                            Sunset
                        </div>
                        <div class="meteo-block-data">--:--</div>
                    </div>
                </div>
            </div>
        </section>
    </div>
    <!-- Footer -->
    <footer>
        Sparsh Kharya &copy; 2021 all rights reserved
    </footer>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.20.1/moment-with-locales.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/suncalc/1.8.0/suncalc.min.js"></script>
    <script src="utility.js"></script>
    <script src="app.js"></script>
</body>
</html>
