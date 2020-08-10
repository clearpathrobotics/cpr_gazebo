Clearpath Race Modules
=======================

This package contains generic components for building race-tracks.  Both paved & dirt/mud tracks are supported.

Please see launch/test_small_track.launch for an example of use.

Parameters
------------

Four tile types exist and can be spawned:
- straight_description: a straight segment of track
- edge_straight_description: barriers to be placed on each side of the straight_description
- corner_description: a 90-degree turn
- edge_corner_description: barriers to be placed on each side of the corner_description

track_type can be one of:
- road
- dirt
- mud
and defines the driving surface itself

barrier_type can be one of:
- racing
- black
and defines the appearance of the barriers

complexity can be one of:
- simple
- complex
and defines the polygon density & resolution of the surfaces.

size can be one of:
- small: tiles are 1m by 1m
- large: tiles are 3m by 3m
