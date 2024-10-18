# Pharmacy Locator with Neo4j

This project demonstrates how to use **Neo4j** and **OSMnx** to locate pharmacies in a city and find the nearest one to a given location. The project includes data extraction, database insertion, and distance calculation between points of interest.

## Features

- **Data Extraction**: Download and filter pharmacy data from OpenStreetMap for a specified city.
- **Database Integration**: Insert pharmacy data into a Neo4j database.
- **Distance Calculation**: Compute distances between the current location and pharmacies.
- **Visualization**: Display pharmacies and routes on an interactive map using Folium.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pharmacy-locator.git
   cd Neo4jPharmacyFinder
   ```

2. Install the required packages:
   ```bash
   pip install  osmnx geopandas neo4j networkx geopy folium requests webbrowser
   ```

3. Set up Neo4j:
   - Install Neo4j and start the server.
   - Update the `uri`, `user`, and `password` in the script to match your Neo4j credentials.

## Usage

1. Run the script to download and process pharmacies nearby :
   ```python
   python script.py
   ```

2. Open the generated `map.html` file in your browser to view the interactive map.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
