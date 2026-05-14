# lucky-map

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple web application that displays a random municipality in Japan on a satellite map.

## Demo

https://code4fukui.github.io/lucky-map/

The interface features a "幸運を感じる" (Feel Lucky) button, a link with the current location's name, and an interactive satellite map.

## Features

-   **Random Location:** Displays a random Japanese municipality on a satellite map when the page loads.
-   **Discover More:** Find a new random location by clicking the "幸運を感じる" (Feel Lucky) button.
-   **Direct Link:** Provides a clickable link to the official website of the displayed city or town.
-   **Interactive Map:** Utilizes an interactive satellite map to pinpoint the location.

## Usage

1.  Visit the [demo page](https://code4fukui.github.io/lucky-map/). A random location is displayed automatically.
2.  Click the **幸運を感じる** (Feel Lucky) button to generate a new location.
3.  The map will center on the new location, and its name will be displayed above the map.
4.  Click the linked city name to visit its official webpage.

## Technology Stack

This project is a static HTML application built with the following:

-   **Data Source:** [localgovjp-utf8.csv](https://code4fukui.github.io/localgovjp/localgovjp-utf8.csv) for Japanese local government data, including coordinates and official URLs.
-   **Mapping Library:** [gsi-map](https://github.com/code4fukui/gsi-map), a web component for displaying maps from the Geospatial Information Authority of Japan.
-   **CSV Parser:** [CSV.js](https://github.com/code4fukui/CSV) for parsing the location data.

## License

MIT License — see [LICENSE](LICENSE).