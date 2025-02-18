## GNSS NMEA 0183 Data

`120k` is probably the one you want, with ~60 minutes of data, starting at 2025-02-18 09:48:40 UTC, captured from an ArduSimple simpleRTK2B Budget (u-blox ZED-F9P).

`100k` is ~90 minutes of data, starting at 2025-01-06 10:49:28 UTC, captured from an ArduSimple simpleGNSS board (u-blox NEO-F10).

`6m` is ~96 hours of data, with the capture starting at 2025-01-16 12:30:39 UTC, again on the simpleGNSS board. If you need this, good luck.

`.nmea` files contain the raw NMEA data, while `.tsv` files are the same NMEA sentences along with the time in seconds since the previous sentence was received.

All data was captured at QUB's Ashby Building in Northern Ireland using a stationary antenna.
