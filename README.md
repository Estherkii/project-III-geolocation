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

## Hypotheses:

In our analysis, we have identified several hypotheses regarding the concentration of gaming, web, and design companies, particularly in San Francisco. First, the high number of such companies in San Francisco may be attributed to the city's robust tech ecosystem, which provides access to venture capital, a talented workforce, and valuable industry partnerships.

The selection of our company's new location has been meticulously tailored to meet the diverse and specific requirements of our employees. To ensure that our design team thrives, we have situated the office in proximity to a vibrant community of companies involved in design, fostering collaboration and creativity. We've also considered our family-oriented staff, choosing a location in neighborhoods with outstanding schools and family-friendly amenities, guaranteeing a safe and supportive environment for employees with children. For our developers, we've positioned the office in areas renowned for tech innovation, offering access to successful tech startups with substantial funding, a stimulating environment that encourages innovation. Our executives can enjoy easy access to numerous Starbucks locations, aligning with our CEO's preferences for coffee shop meetings and quick breaks. Account managers will find convenience in our office's proximity to major transportation hubs, streamlining business travel and boosting efficiency. The young, dynamic workforce is drawn to our vibrant office location in entertainment districts and tech hubs that cater to their energy and preferences. Additionally, we've ensured that vegan dining options are readily available for our CEO, in line with their dietary choices. For our maintenance team, the office has a basketball court only 15 min walking from the office, allowing him to indulge in his passion for the sport. Even our beloved office dog, Dobby, benefits from the carefully chosen location, with pet services and groomers nearby. These considerations have resulted in a well-rounded workplace that fulfills the diverse needs and preferences of our employees, creating an environment where everyone can thrive and excel.

![image](https://github.com/Estherkii/project-III-geolocation/assets/123992666/547f735b-a9ad-4c6d-8c6f-b1038b89bd18)

## In conclusion:

In conclusion, the Geospatial Data Project presented a comprehensive approach to finding the ideal location for a new gaming company's office while taking into account the diverse preferences and requirements of its employees. The project began by querying a database to identify companies that met the unique criteria of the workforce, which ranged from design preferences to family-oriented needs and even a CEO's vegan lifestyle. This meticulous data-driven analysis was facilitated by utilizing APIs to validate the criteria and assess potential venues based on surrounding amenities and services.

Throughout the project, the team meticulously considered factors like proximity to design companies, childcare facilities, tech startups, Starbucks locations, travel options, vegan dining, and more. Weights were assigned to each criterion, and distances or densities were calculated to prioritize the best overall location that satisfied all the requirements. The data-driven approach ensured a well-rounded workplace environment where every employee, including designers, developers, account managers, executives, and even the office dog "Dobby," could thrive and excel.

By aligning the office's location with the unique needs of its workforce, the project has not only provided a valuable decision-making framework but also exemplified the company's commitment to creating an inclusive and supportive workplace that caters to its employees' diverse lifestyles and preferences.

Presentation link: https://www.canva.com/design/DAFzYvRyIZU/3MGtIFp1txYyGMUKCKTl8A/edit 

