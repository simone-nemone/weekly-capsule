# Weekly Capsule Wardrobe Generator

A simple web app that generates a 5-day work wardrobe based on weather forecast for Bairnsdale, Victoria (or other Australian locations).

## What It Does

- Fetches 5-day weather forecast from OpenWeatherMap API
- Suggests daily outfit combinations based on temperature and rain probability
- Adapts to different dress codes (Smart Casual, Business Casual, Business Formal, Casual)
- Allows custom wardrobe items or uses sensible defaults
- Designed for primary school education support staff with smart casual requirements

## How to Use

1. Open the app: [https://YOUR-USERNAME.github.io/capsule-wardrobe/](https://YOUR-USERNAME.github.io/capsule-wardrobe/)
2. Select your location (default: Bairnsdale, VIC)
3. Select your dress code (default: Smart Casual)
4. Optionally add your own wardrobe items (comma-separated)
5. Click "Generate My Wardrobe"

## Wardrobe Logic

- **Different top each day** - cycles through available tops
- **Bottoms can repeat** - alternates every 2 days
- **Layer added** when temperature < 20°C
- **Outerwear added** when temperature < 15°C or rain chance > 60%
- **No footwear suggestions** - as requested

## Features

- No installation required - runs in browser
- No backend needed - all client-side
- Responsive design for mobile and desktop
- Custom wardrobe items supported
- Free to use (within OpenWeatherMap API limits)

## Tech Stack

- HTML/CSS/JavaScript (vanilla, no frameworks)
- OpenWeatherMap API for weather data

## Setup for Your Own Use

If you want to clone this:

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the API key in the JavaScript (line 205)
3. Upload to GitHub Pages or run locally

## License

Free to use and modify for personal use.

## Credits

Weather data provided by OpenWeatherMap.
