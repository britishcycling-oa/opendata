# British Cycling Sky Ride Open Data

## Open Data Endpoint
http://api.ridesociallondon.co.uk/api/EventFeed/ - a feed of the data from goskyride.com

## Standards
The data is published to conform to [Openactive Realtime Paged Data Exchange 0.2.3](https://www.openactive.io/realtime-paged-data-exchange/0.2.3/).

## Issues, Questions and Comments
Please raise any issues, questions or comments as a [new issue in this repository](https://github.com/britishcycling-oa/opendata/issues).

## Data Fields

| Data Field | Example Value | Description |
|---|---|---|
|"CalendarEventID" | 42831 | Internal ID of the session |
|"EventType"| "Sky Ride" | Type of event, one of: "Sky Ride" (NGB organised); "Ride Social" (User Submitted) |
|"Title"| "Sky Ride Birmingham" | Session title|
|"StartDateTime"| "2014-07-20T11:00:00"| Start time of session|
|"CityName"| "Birmingham" | City of ride, not related to location |
|"Postcode"| "B13 8RD"| Postcode of meeting location |
|"Location"| "Whitwell- Rutland Cycling" | Free text location, not an address, do not attempt to Geocode this field |
|"SuitableFor"| "Anyone"| One of "Women and Children", "Women Only", "Adults 16+ only". Note that the "Age Restrictions" calculated field on the Go Sky Ride site is populated when this field is set to "Adults 16+ only" |
|"Difficulty"| "Easygoing" | One of "Easygoing", "Steady" or "Challenging" |
| "BikeSuitability" | "Mountain Bike;Road;Hybrid (road tyres);Hybrid (off road tyres);" | Semi-colon delimited list of bike types |
| "Description" | "" | Full text description of the ride, with HTML tags stripped |
| "GroupName" | "Lincoln Cycle Chimps" | Name of riding group, especially when related to Ride Social rides |
| "Pace" | "Slow (below 8 mph)" | Pace of the ride |
|"EstimatedDurationCyclingMins" | 60 | Minutes cycling |
|"EstimatedDurationTotalMins" | 90 | Total minutes in session including cycling
| "RideDistanceMiles" | 5 | Ride Distance |
| "StartLatitude" | 52.45082082040742 | | 
| "StartLongitude" | -1.8999221725943267 | | 
| "Permitted" | 100000 | Maximum number or riders permitted to attend the session (100000 = unlimited) |
| "BookedPreRide" | 78 | Number of riders booked before the ride started |
| "Booked" | 78 | Number of riders booked total |
| "Free" | 0 |  Free places remaining |
| "Publish" | false | Ride is published on the public website. Value "false" should be considered as a deleted record. |
| "Link" | "http://www.goskyride.com/Search/Details?eventid=42831" | URL of session on Sky Ride site.
| "LastUpdated" | 19523983 | Record last updated timestamp |


## Changelog

| Date | Changes |
|---|---|
| 4/07/2016 | Initial version published |
