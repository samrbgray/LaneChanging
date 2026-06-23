# FSD Positional Data — Column Reference

See the [Dataset page](https://samrbgray.github.io/LaneChanging/dataset.html) for full column definitions.

| Column | Units | Description |
|--------|-------|-------------|
| GPS_TOW | seconds | GPS Time of Week |
| Raw_Timestamp | seconds | Elapsed time from trial start |
| DateTime_EST | — | Wall-clock time (Eastern Standard) |
| Latitude | decimal degrees | WGS-84 latitude (RTK, ±0.01 m) |
| Longitude | decimal degrees | WGS-84 longitude (RTK, ±0.01 m) |
| Altitude | meters | Ellipsoidal altitude |
| Heading | degrees | Heading from North (0–360°) |
| Speed_mps | m/s | Ground speed |
| LeftLane_Lat / _Lon | decimal degrees | Left lane boundary projection |
| RightLane_Lat / _Lon | decimal degrees | Right lane boundary projection |
| LongDist_LeftLane_m | meters | Longitudinal distance along left lane from trial start |
| LatDist_LeftLane_m | meters | Lateral offset from left lane marking |
| LatDist_RightLane_m | meters | Lateral offset from right lane marking |
| LaneSpacing_m | meters | Estimated lane width |
| VehicleType | — | LV, LCV, F1, or F2 |
| Rel_Longitudinal_Dist_from_LC | meters | Distance from lane-change event (– before, + after) |
| LongDist_LeftLane_m (Common Reference) | meters | Shared longitudinal reference across all vehicles |
