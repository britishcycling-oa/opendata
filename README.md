# British Cycling Let's Ride Open Data

## Open Data Endpoint
http://api.letsride.co.uk/public/v1/rides - a feed of the data from letsride.co.uk

## Standards
The data feed is published to conform to [OpenActive Realtime Paged Data Exchange 1.0](https://www.openactive.io/realtime-paged-data-exchange/1.0/) and [OpenActive Modelling Opportunity Data 2.0](https://www.openactive.io/modelling-opportunity-data/), using features from the [OpenActive Beta Namespace](https://www.openactive.io/ns-beta/), and the extension properties below.

## Issues, Questions and Comments
Please raise any issues, questions or comments as a [new issue in this repository](https://github.com/britishcycling-oa/opendata/issues).

## Extension Properties
In addition to the properties in the [Opportunity Data Model](https://www.openactive.io/modelling-opportunity-data/), the data also includes custom properties unique to British Cycling's implementation. A machine-readably context is [also available](http://data.letsride.co.uk/opendata/britishcycling.jsonld).

| (Class) Property    |  Expected Type  | Description                                                         |
|---------------------|-----------------|---------------------------------------------------------------------|
| <a name="gpxFile"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:gpxFile` | [`schema:URL`](https://schema.org/URL) | GPX is a type of file that’s really helpful to anyone who loves the outdoors, and is the most popular way of saving and exchanging routes which can be plotted on a map. |
| <a name="otherInformation"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:otherInformation` | [`schema:Text`](https://schema.org/Text) | Other information about the route |
| <a name="publicTransport"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:publicTransport` | [`schema:Boolean`](https://schema.org/Boolean) | Is it feasible to get to the meeting point of this ride via public transport only |
| <a name="publicTransportDetails"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:publicTransportDetails` | [`schema:Text`](https://schema.org/Text) | Information about public transport to use e.g. Pontefract Train Station. |
| <a name="stoppingPoints"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:stoppingPoints` | [`schema:Text`](https://schema.org/Text) | Description of stopping points on the route |
| <a name="terrain"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:terrain` | [`schema:Text`](https://schema.org/Text) | Route terrain, for example, 'Tarmac Road'. |
| <a name="topography"></a> ([`schema:Event`](https://schema.org/Event)) <br/>  `britishcycling:topography` | [`schema:Text`](https://schema.org/Text) | Route topography, for example, 'Some Hills'. |

## Changelog

| Date | Changes |
|---|---|
| 04/07/2016 | Initial version published |
| 05/12/2018 | Updated to Modelling Specification v2 |
