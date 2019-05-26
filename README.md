# isochrones
isochrone assignment 

[Google Transit Feed Specification](https://developers.google.com/transit/gtfs/reference/?hl=en)

[GTFS google example](https://developers.google.com/transit/gtfs/examples/gtfs-feed)

[Transitfeeds.com locations](transitfeeds.com)

## thinking:

* Get location
* Walking speed buffer
* Time from location to "stops" within buffer
* buffer points within remaining time minus any waiting time
* walking speed buffer remaining time around "exit stops" 

<b>variable:</b> location/origin (start coordinate, point, or polygon centroid)

<b>variable:</b> time/duration (parameter of minutes from A to B)

<b>constant:</b> walking speed

<b>list</b>: over-all point list 
<>

<b>function:</b> buffer_process_1:   *output <b>walking_polygon1</b> + for all points within walking distance get 'remaining time' by deducting time from origin'


