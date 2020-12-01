# United Kingdom

## Rover Setup

### Coordinate System

Choose a coordinate system based on `OSGB 1936` datum (such as `OSGB 1936 / British National Grid`).

### Vertical Datum

Choose one of the available vertical datums:
* `Belfast height`
* `Douglas height`
* `ODN (Offshore) height`
* `ODN Orkney height`
* `ODN height`
* `St. Marys height`
* `Stornoway height`

The following geoids are used to perform the transformation:
* `OSGM15_Belfast`
* `OSGM15_GB`

!!! note ""
	For `Belfast height` vertical datum `OSGM15_Belfast` geoid is used, and for others `OSGM15_GB`.

## Base Setup

Your base or NTRIP service should be in `ETRS89`. The following methods are used to perform the datum conversion: `OSTN15` grid.

When setting up a base station on a benchmark, enter `ETRS89` geographic coordinates (lat/long) and ellipsoidal height in the ReachView 3 *Settings* ⇒ *Base mode* tab.
