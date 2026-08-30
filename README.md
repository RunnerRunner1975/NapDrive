# NapDrive V3

V3 fixes the Apple Maps mismatch by sampling waypoints directly from the selected OSRM road geometry, then passing those road-snapped coordinates to Apple's multistop directions URL.

Apple documents repeated `waypoint` parameters for multistop driving directions.
