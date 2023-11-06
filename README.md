# Project-III- Geospatial Data Project

### Overview

This GitHub project focuses on finding the best location for a new gaming company's office, taking into consideration various employee preferences and requirements. The company has a diverse workforce, including designers, engineers, developers, account managers, executives, and a CEO with unique preferences. The project aims to provide a data-driven decision for the optimal office location.


### Requirements/Libraries Used

* from pymongo import MongoClient
* import pandas as pd
* import time
* import requests
* import json
* from getpass import getpass
* import os
* import folium
* from folium import Choropleth, Circle, Marker, Icon, Map
* from folium.plugins import HeatMap, MarkerCluster
* import geopandas as gpd
* from cartoframes.viz import Map, Layer, popup_element
* Matplotlib.pyplot
* from dotenv import load_dotenv

### Option A: Stealing an Existing Company's Venue

#### Step 1: Querying the Database

The project initiates by querying the database to gather essential information about existing companies. The selection criteria are based on employee preferences and requirements, including:

* Designers: A preference for proximity to companies involved in design.
* Family-Oriented: 30% of the staff have at least one child.
* Developers: A desire to be near successful tech startups with at least $1 million in funding.
* Executives: A love for Starbucks, so there must be a nearby Starbucks.
* Account Managers: The need for easy travel.
* Young Workforce: Everyone in the company falls between the ages of 25 and 40.
* CEO's Vegan Lifestyle: Consideration of vegan dining options.
* Maintenance Guy's Basketball Interest: Proximity to a basketball stadium.
* Office Dog "Dobby": Requirement for a nearby hairdresser.

### Step 2: Using an API to Validate Criteria

To ensure the selected location meets all criteria, an API is utilized to gather data about the surroundings of potential venues. This includes factors like the presence of design-focused companies, childcare facilities, tech startups, Starbucks locations, travel options, nightlife venues, vegan restaurants, basketball stadiums, and pet grooming services.

### Step 3: Data-Driven Decision

The decision-making process is data-driven, considering various factors. Weights are assigned to each criterion based on its importance, and distances or densities are calculated as needed. The goal is to prioritize and optimize for the best overall location, taking all requirements into account.


Presentation link: https://www.canva.com/design/DAFzYvRyIZU/3MGtIFp1txYyGMUKCKTl8A/edit 

