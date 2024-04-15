# [<img src="logo.png" width="20"/>](image.png) DatWeatherDoe

- Fetch weather using: 
    - Location services
    - Zip Code
    - Latitude / Longitude
    - City
- Configurable polling interval
- Dark mode support

## Screenshots

![Screenshot 1](screenshot_1.png)\
![Screenshot 2](screenshot_2.png)
![Screenshot 3](screenshot_3.png)

## Installation

### Homebrew Cask

`brew install --cask datweatherdoe`

### Manual

- [MacOS 13.0+](https://github.com/inderdhir/DatWeatherDoe/releases/latest)
- [MacOS 11.0-13.0](https://github.com/inderdhir/DatWeatherDoe/releases/tag/3.3.0)

## Using Location Services

If using location, please make sure that the app has permission to access location services on macOS.

`System Preferences > Security & Privacy > Privacy > Location Services`

![Location services screenshot 1](location_services_1.png)
![Location services screenshot 2](location_services_2.png)

## Developer Setup

- Get your personal API key for openweathermap [here](http://openweathermap.org/appid)
- Add the following in "Config.xcconfig":
```
OPENWEATHERMAP_APP_ID = YOUR_KEY
```

## Donate

Buy me a coffee to support the development of this project.

<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="dgiaco" data-color="#FFDD00" data-emoji="" data-font="Bree" data-text="Keep ‘em comin’" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>

<a href="https://www.buymeacoffee.com/inderdhir"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=inderdhir&button_colour=FFDD00&font_colour=000000&font_family=Poppins&outline_colour=000000&coffee_colour=ffffff"></a>

## Contribute

Please see CONTRIBUTING.md
