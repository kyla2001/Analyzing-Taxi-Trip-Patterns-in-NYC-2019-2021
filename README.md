# Analyzing Taxi Trip Patterns in NYC (2019–2021)

## Project Overview
This project focuses on analyzing taxi trip patterns in New York City using trip data from Yellow and Green Taxis between 2019 and 2021. How COVID-19 reshaped taxi usage in NYC spatially, economically, and socially. [Presentation Slides](https://docs.google.com/presentation/d/1aELyzroSV7WJfkgB4oMVoOTJ9B4J7eN1xs9D2_SWg0U/edit?usp=sharing) [Project Proposal](https://docs.google.com/document/d/1twahUp5GtmELRB3zR8a6gOU-vDn9rRyA-KzAVk1NrcY/edit?usp=sharing) [Project Milestone(https://docs.google.com/document/d/1sHUgODUegIMGREHmRuXCs1FDFKoeH3-JHuTHGHtS3Ag/edit?usp=sharing)

## Team Members
- **Yibei Li** (`yl3692`)
- **Yuchuan Zhang** (`yz2947`)
- **Joy Wang** (`zw673`)

## Dataset Description
The project uses NYC Yellow and Green Taxi trip datasets, which include the following key features:
- **Trip Information**: Pickup and dropoff times, trip distances, passenger counts, and fare amounts.
- **Geographic Information**: Pickup and Dropoff Location IDs (PULocationID and DOLocationID).
- **Fare Structure Variables**: RatecodeID, payment type, and congestion surcharge, allowing for an in-depth investigation into pricing and taxi regulations.

### Taxi Service Areas
- **Yellow Taxis**: Predominantly operate in Manhattan.
- **Green Taxis**: Serve the outer boroughs (Brooklyn, Queens, Bronx), with limited operation in Manhattan.

## Data Sources
- **NYC Taxi Fare Information**: [NYC Taxi Fare](https://www.nyc.gov/site/tlc/passengers/taxi-fare.page)
- **NYC Taxi Zones (.csv / .shp)**: `tazi_zones.csv` & `../data/NYC Taxi Zones`
- **Yellow and Green Taxi Trip Records**: [TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) `../data/2019` & `../data/2020` & `../data/2021`
- **Taxi Trip Data Dictionary**: `Yellow_Taxi_Trip_Data_Data_Dictionary.xlsx` & `Green_Taxi_Trip_Data_Data_Dictionary.xlsx`

## Objectives
1. **Analyze Trip Behaviors**:
   - Identify temporal patterns in taxi usage (e.g., rush hours, seasonal trends).
   - Examine spatial distribution of pickups and dropoffs.
2. **Explore Fare Dynamics**:
   - Assess fare variations based on trip distance, time, and location.
   - Investigate the impact of taxi regulations, such as congestion surcharges.
3. **Understand Geographic Trends**:
   - Evaluate how Yellow and Green taxis serve different boroughs and regions.
