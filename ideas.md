Future Project Ideas
====================

### Watch winder
Keep an automatic watch wound when it is not worn.

* Features:
  * Detect weight, and start automatically after a XX second delay?
  * Stop running after XX time of continuous use?
  * Use a light sensor to only run during the day?
  * Push button override of automated operations
* Basic components:
  * Wooden box as base
  * Soft foam for watch positioner
  * tiny PIC for brains
  * One or two micro servos to actuate winding


### Paper cutter
Cricut replacement for cutting paper, etching PCBs, etc.

* perhaps use a laser instead of a blade as the cutting implement?
* Swappable cutting/etching/piercing heads for different uses?


### Music writer
Get notes on input and write them to file.

* Notes would be from a digital source
  * the electronic drum kit?
  * an audio frequency ADC attached to a guitar or piano?
* The output file should be in a standard format, preferably one that:
  * is fairly human-readable
  * is easily rendered as sheet music


### Dremel CNC
A CNC machine with a commodity high-speed rotary tool as its cutting head

* start with 3 axis
  * The paper cutter would be a good proving ground for a lot of the control code
  * Final goal is a 5-axis design, with three linear axes and two rotational axes for the head
* Should be compatible with at least one common file format
  * G-code is the defacto standard and an obvious choice
  * What formats can be produced by open-source 3D CAD tools?


### Cable modem statistics tracker
Maintain statistics on connection state, signal strength, IPs, etc over time

* Split into two pieces, the collection daemon and the user interface(s)
* The collection daemon:
  * will run on a single server
  * will poll the cable modem for data periodically
  * will provide an API for UI implementations to get the data in a standard way
* The UI:
  * will display, plot, alert on, and generally do useful things to the data
  * will come in various flavors:
    * Full-power Linux/Windows client (or just Linux, if cross-platform doesn't pan out
	 * Lightweight alert-oriented modules for Linux, Windows, Android
	 * MediaPortal plugin
