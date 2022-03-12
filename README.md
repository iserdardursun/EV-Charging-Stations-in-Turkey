# EV-Charging-Stations-in-Turkey
EV Charging Stations Data in Turkey

JSON Data of Electric Vecicles Charging Stations in Turkey. Data was gathered by scanning 17139 circles with a radius of 5km using TomTom API.

Content:
- Total 875 Stations
- JSON Format of Data
- GEOJSON Format of Data


An Example of a Station Data From JSON:

    "address": {
      "streetName": "Kelebek Sokak",
      "municipality": "Edirne Centre",
      "postalCode": "22100",
      "countryCode": "TR",
      "country": "Turkey",
      "countryCodeISO3": "TUR",
      "freeformAddress": "Kelebek Sokak, 22100 Abdurrahman",
      "localName": "Abdurrahman"
    },
    "position": {
      "lat": 41.66628,
      "lon": 26.57063
    },
    "viewport": {
      "topLeftPoint": {
        "lat": 41.66718,
        "lon": 26.56943
      },
      "btmRightPoint": {
        "lat": 41.66538,
        "lon": 26.57183
      }
    },
    "entryPoints": [
      {
        "type": "main",
        "position": {
          "lat": 41.66641,
          "lon": 26.57033
        }
      }
    ],
    "chargingPark": {
      "connectors": [
        {
          "connectorType": "IEC62196Type2Outlet",
          "ratedPowerKW": 22,
          "voltageV": 400,
          "currentA": 32,
          "currentType": "AC3"
        },
        {
          "connectorType": "IEC62196Type2CCS",
          "ratedPowerKW": 50,
          "voltageV": 400,
          "currentA": 125,
          "currentType": "DC"
        },
        {
          "connectorType": "Chademo",
          "ratedPowerKW": 50,
          "voltageV": 400,
          "currentA": 125,
          "currentType": "DC"
        }
      ]
    }
  }
