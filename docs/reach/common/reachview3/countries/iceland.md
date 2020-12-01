# Iceland

## Rover Setup

### Coordinate System

Choose a coordinate system based on `ISN2004` (such as `ISN2004 / Lambert 2004`) or `ISN2016` (such as `ISN2016 / Lambert 2016`) or `ISN93` (such as `ISN93 / Lambert 1993`) datums.

### Vertical Datum

Choose one of the available vertical datums: `ISH2004 height`.

!!! note ""
	When using `ISH2004 height` vertical datum, a correct geoid file will be selected automatically based on the chosen horizontal system:
	* Projects based on `ISN93` use `Icegeoid_ISN93` geoid
	* Projects based on `ISN2004` use `Icegeoid_ISN2004` geoid
	* Projects based on `ISN2016` use `Icegeoid_ISN2016` geoid

## Base Setup

Your base or NTRIP service should be in `ISN2004` or `ISN2016` or `ISN93` depending on which datum is used.

When setting up a base station on a benchmark, enter `ISN2004` or `ISN2016` or `ISN93` geographic coordinates (lat/long) and ellipsoidal height in the ReachView 3 *Settings* ⇒ *Base mode* tab.
