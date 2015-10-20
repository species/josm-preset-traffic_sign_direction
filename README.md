# josm-preset-traffic_sign_direction
Very simple preset for the Java OSM Editor to show the "direction" tag of a highway=traffic_signals/stop/give_way

## This style is now available in the Map Paint Styles list in JOSM.

Add it this way:
* F12 (Settings)
* Map settings
* Map paint styles
* choose “Direction for traffic signs”, 
* Click the > button to add it to Active styles on the right
* OK
 
## What does its do?

On ways that have a highway=stop/give_way/traffic_signal, it displays the way direction.

It marks highway=stop/give_way that are missing the “direction” tag with an easily spottable orange rectangle

It shows a symbol that indicates which direction is set on the node: (↑) forward or (↓) backward

It displays a warning symbol if highway=stop/give_way is used on crossing vertices with more than one way.
