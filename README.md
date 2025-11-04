# 🚀 SpaceX Falcon 9 Launch Data Wrangling

This project collects, enriches, and cleans SpaceX Falcon 9 launch data using the SpaceX REST API. It extracts detailed information about rockets, payloads, launchpads, and booster cores to build a structured dataset suitable for analysis or machine learning.

## 📦 Dataset Features

The final dataset includes:

- **BoosterVersion**: Name of the rocket used
- **PayloadMass**: Mass of the payload in kilograms
- **Orbit**: Target orbit for the payload
- **LaunchSite**: Name of the launch site
- **Longitude & Latitude**: Coordinates of the launch site
- **Outcome**: Whether the booster landing was successful
- **Flights**: Number of flights for the booster core
- **GridFins, Legs, Reused**: Booster configuration details
- **LandingPad**: Landing pad used
- **Block**: Booster version block number
- **ReusedCount**: Number of times the booster was reused
- **Serial**: Serial number of the booster core
- **FlightNumber**: Sequential launch number

## 📁 Files

- `spacex_data_wrangling.py`: Python script to fetch and process the data
- `spacex_falcon9_launch_data.csv`: Final enriched dataset
- `README.md`: Project overview and instructions

## 🛠️ Requirements

- Python 3.x
- `pandas`
- `requests`

Install dependencies:

```bash
pip install pandas requests
