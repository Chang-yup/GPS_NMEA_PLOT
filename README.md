# GPS_DATA_PLOT
plotting GPS NMEA Data on matlab

You can see animated GPS trajectory on matlab.

# Demonstration
https://youtu.be/MYm6fZWJfCk


# How to use

1. Load your GPS log on matlab.

2. Change 'fileID = fopen('INCH-RTCM32_TEST.log');' into 'fileID = fopen('your_GPS_log');'

3. You may change your device identifier 'tline=extractBetween(tline,'GNGGA',',,');' ex) 'GNGGA' -> 'GPGGA' or else

4. Run it.

If you don't want to see animation, You can see whole trajectory at first. Comment out the 'Animated Plot' and uncomment 'Geo Plot'.

# Description
Checksum will be updated.

GPS_NMEA_DATA_PLOT : Main matlab code.

INCH-RTCM32_TEST.log : GPS log file I used.


