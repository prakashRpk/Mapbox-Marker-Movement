# Mapbox Marker Movement

This project utilizes Mapbox GL JS to create an interactive map application that demonstrates moving a marker between predefined coordinates. The application showcases the journey from Sulur to Singanallur.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Interactive Map displaying the route between Sulur and Singanallur.
- A marker that moves smoothly between predefined latitude and longitude coordinates.
- Button to start the marker movement.

## How It Works

1. **Mapbox Setup**:
   - The project uses the Mapbox GL JS library to display a map with street view.

2. **HTML Structure**:
   - Contains a `div` element for the map and a button to initiate the marker movement.

3. **JavaScript Functionality**:
   - The Mapbox access token is set to access the map features.
   - An array of latitude (`right`) and longitude (`left`) values represents the path.
   - A button triggers the `btn` function, which starts the movement of the marker on the map.

4. **Marker Movement**:
   - The `move` function updates the marker's position on the map every second by cycling through the coordinates.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mapbox-marker-movement.git
   cd eyeball-follower
   open index.html
## Customization
You can change the background image by modifying the background-image URL in the CSS.
The eyeball images can also be updated by changing the src attribute of the <img> tags in the HTML.
Adjust the size and position of the eyes by modifying the CSS properties in the .eye and .eyeball classes.
