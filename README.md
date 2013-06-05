rd2wgs48
========

RD coordinates to WGS48 conversion function

Usage:

```php
include("rd2wgs48.php");
$latlon = rd2wgs48(113029.751, 400211.209);
echo $latlon['latitude']; // Prints latitude (51.589243073896)
echo $latlon['longitude']; // Prints longitude (4.7815707523717)
```