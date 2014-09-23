http://gtfs.ovapi.nl/new/gtfs-nl.zip

Bron: http://nl.wikipedia.org/wiki/Noord/Zuidlijn
Lijn 52
12 ritten per uur, van 6:00 tot 0:00 (elke 5 minuten)

Lengte: 9309 meter.

Gemiddelde snelheid:

    1535:GVB:54:W:WE:54:100,1,GVB:09501,,09:06:00,09:06:00,0,0,1,0,0
    1535:GVB:54:W:WE:54:100,2,GVB:09503,,09:07:10,09:07:28,0,0,0,740,740
    1535:GVB:54:W:WE:54:100,3,GVB:09509,,09:08:25,09:08:43,0,0,0,1360,1360
    1535:GVB:54:W:WE:54:100,4,GVB:09511,,09:09:53,09:10:11,0,0,0,2106,2106
    1535:GVB:54:W:WE:54:100,5,GVB:09513,,09:11:26,09:11:44,0,0,0,2922,2922
    1535:GVB:54:W:WE:54:100,6,GVB:09515,,09:13:12,09:13:30,0,0,0,3873,3873
    1535:GVB:54:W:WE:54:100,7,GVB:09566,,09:14:42,09:15:00,0,0,0,4595,4595
    1535:GVB:54:W:WE:54:100,8,GVB:09517,,09:16:42,09:17:00,0,0,0,5912,5912
    1535:GVB:54:W:WE:54:100,9,GVB:09551,,09:18:26,09:18:44,0,0,0,6789,6789
    1535:GVB:54:W:WE:54:100,10,GVB:09521,,09:19:53,09:20:11,0,0,0,7399,7399
    1535:GVB:54:W:WE:54:100,11,GVB:09523,,09:21:42,09:22:00,0,0,0,8246,8246

Tijden tussen stops:

     1 >  2, 1:10 min =  70 sec,  740 meter, 10.6 m/s
     2 >  3, 0:57 min =  57 sec,  620 meter,  8.3 m/s
     3 >  4, 0:50 min =  50 sec,  746 meter, 14.9 m/s,
     4 >  5, 1:15 min =  75 sec,  816 meter, 10.9 m/s,
     5 >  6, 1:28 min =  88 sec,  951 meter, 10.8 m/s,
     6 >  7, 1:12 min =  72 sec,  733 meter, 10.2 m/s,
     7 >  8, 1:42 min = 102 sec, 1317 meter, 12.9 m/s,
     8 >  9, 1:26 min =  86 sec,  877 meter, 10.2 m/s,
     9 > 10, 1:09 min =  69 sec,  612 meter,  8.9 m/s,
    10 > 11, 1:31 min =  91 sec,  847 meter,  9.3 m/s,
    -------------------------------------------------
                                             10.7 m/s

Metro's stoppen gemiddels 18 seconden op een station.


Stations:

- Noord
- Noorderpark
- Centraal Station
- Rokin
- Vijzelgracht
- De Pijp
- Europaplein
- Station Zuid

OV-bedrijven in Amsterdam:

- GVB (GVB)
- Connexxion (CXX)
- EBS (EBS)
- NS (IFF:NS)

## OpenTripPlanner

Download the latest OpenTripPlanner jar from:
http://dev.opentripplanner.org/jars/otp-latest-master.jar

Build graph:

    java -Xmx4G -jar otp-latest-master.jar --build ../data

Run server:

    java -Xmx4G -jar otp-latest-master.jar --server --graphs ../data
