# USA

## Rover Setup

### Coordinate System

Choose a coordinate system based on `NAD83(2011)` (such as `NAD83(2011) / South Carolina`) or `NAD83(MA11)` (such as `NAD83(MA11) / UTM zone 54N`) or `NAD83(PA11)` (such as `NAD83(PA11) / Hawaii zone 1`) datums.

### Vertical Datum

Choose one of the available vertical datums:
* `ASVD02 height`
* `GUVD04 height`
* `NAVD88 depth`
* `NAVD88 height`
* `NMVD03 height`
* `PRVD02 height`
* `VIVD09 height`

The following geoids are used to perform the transformation:
* `GEOID12B`
* `GEOID18`

!!! note ""
	* Projects based on `NAD83(2011)` datum are compatible with `NAVD88 height`, `PRVD02 height`, and `VIVD09 height` vertical datums that use `GEOID18` geoid.
	* Projects based on `NAD83(MA11)` datum are compatible with `GUVD04 height` and `NMVD03 height` vertical datums that use `GEOID12B` geoid
	* Projects based on `NAD83(MA11)` datum are compatible with `ASVD02 height` vertical datum that also uses `GEOID12B` geoid

## Base Setup

Your base or NTRIP service should be in `NAD83(2011)` or `NAD83(MA11)` or `NAD83(PA11)` depending on which datum is used.

When setting up a base station on a benchmark, enter `NAD83(2011)` or `NAD83(MA11)` or `NAD83(PA11)` geographic coordinates (lat/long) and ellipsoidal height in the ReachView 3 *Settings* ⇒ *Base mode* tab.
