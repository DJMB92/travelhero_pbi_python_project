## TravelHero - Power BI & Python Powered "Last Minute" vacation planner.

<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiZWQ1OTQwMDUtNzVlYy00MjdlLTk3ODEtYTI2ZTQyMGMzNDY0IiwidCI6ImFlMjMzMjNhLTFiMzktNGRjZi1hOTE5LWIzZDE2OTZmNWEwMyIsImMiOjJ9">	
    <img src="Last Minute Vacations.png">
  </a>
</p>

&nbsp;

## The Idea behind everything.

Exploring the many travel APIs out there, I wanted to create a beautiful no-hassle application that could give me any destination in the blink of an eye, with all the nearby ammenities & entertaiment along with the prices, weather for the days that I would be staying there.

<p align="center">
  <a>	
    <img src="how_does_it_work.png">
  </a>
</p>

## TravelHero consists of several separate steps:



- User's Interface: Tkinter - Receives the dates, origin, destination and number of passengers.
- WebsCrapping Cities Coordinates: Using Json connector to scrap from techslides.com the long & lat of all the main cities.
- Weather Report: Weather Forecast's API Consult based on the destination coordinates.
- IATA Codes: Webscrapping the IATA codes for every airport in the world.
- SkyScanner: Using IATA Codes, number of passengers and the dates provided by the user to get the flights.
- Hotels(GoogleMaps): Consulting Google Maps APIs to find the nearest hotels and entertaiment based on the destination's coordinates.
- Power BI Deployment: All the code is built within Power BI to refresh on demand and showcase the results just as any travel app.

### More About Me...
Find me on [LinkedIn](https://www.linkedin.com/in/danieljmendezb/)

