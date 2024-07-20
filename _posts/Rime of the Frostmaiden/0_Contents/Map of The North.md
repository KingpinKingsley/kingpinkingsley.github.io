---
travel-normal: 1
travel-current: .5
travel-difficult: 2
travel-slow: 1.5
travel-fast: .75
travel-mount: .5
mile-normal: 20 minutes
mile-fast: 15 minutes
mile-mount: 10 minutes
mile-slow: 30 minutes
mile-difficult: 40 minutes
---


```leaflet
id: north-map
image: [[TenTowns.jpg]]
bounds:
 - [0,0]
 - [65.859375,93.75]
height: 900px
width: 95%
lat: 24
long: 38
minZoom: 4
maxZoom: 7
defaultZoom: 5
zoomdelta: 0.5
unit: mile
scale: 1
darkMode: false
marker: Town,28.5546875,30.42185186829604,Bryn Shander
marker: Town,26.71484375,43.86715191276314,Easthaven
marker: Town,24.53515625,36.67184475084867,Good Mead
marker: Town,22.5625,32.999992882552625,Dougan's Hole
marker: Town,30.5703125,27.484358985743413,Targos
marker: Town,35.58203125,34.39058051595393,Termalaine
marker: Town,31.90234375,44.238283919042765,Caer-Dineval
marker: Town,35.328125,46.73436521350986,Caer-Konig
marker: Location of Interest,11.25,33.34372864765788,Dredavex's Ship
marker: Dungeon,13.0546875,38.906278469789484,Sunblight Stronghold
marker: Dungeon,37.625,43.812471530210516,Duergar Bunker
marker: Location of Interest,38.84375,43.093753558723684,Kelvin's Cairn
marker: Location of Interest,41.4921875,36.27342860319079,Black Cabin
```


--- start-multi-column: Map_Info_Calc
```column-settings
Number of Columns: 3
Shadow: false
Border: false
Align: Center
Largest Column: standard
```


#### Ten Towns
[[Bryn Shander]]
[[Caer-Dineval]]
[[Caer-Konig]]
[[Dougan's Hole]]
[[Easthaven]]
[[Good Mead]]
[[Targos]]
[[Termalaine]]



--- column-end ---

#### Locations
[[Kelvin's Cairn]]
[[Black Cabin]]
[[The Ferry Hideout]]
[[Unknown Hero's Tomb]]
[[Dredavex's Ship]]


--- column-end ---


#### Dungeons
[[Duergar Bunker]]
[[Maud's Cave]]
[[Duhg's Cave]]
[[Sunblight Stronghold]]


--- end-multi-column





## Travel Times

**Replace the referenced page as necessary to see full travel times.**

1 mile every: 20 minutes (Normal), 15 minutes (Fast), 10 minutes (Lightspeed), 30 minutes (Slow), 40 minutes (Difficult Terrain).

[Website Calculator](https://www.omnicalculator.com/everyday-life/speed)

--- start-multi-column: Travel_Calc
```column-settings
Number of Columns: 5
Shadow: false
Border: false
Align: Center
Largest Column: standard
```


| Normal/Walking |              Duration               |  
| :------------: | :---------------------------------: |
|     Bremen     |   `=[[Bryn Shander]].travel-bremen`   | 
|  Bryn Shander  |    `=[[Bryn Shander]].travel-bryn`    |  
|  Caer-Dineval  |  `=[[Bryn Shander]].travel-dineval`   | 
|   Caer-Konig   |   `=[[Bryn Shander]].travel-konig`    |  
| Dougan's Hole  |   `=[[Bryn Shander]].travel-dougan`   | 
|   Easthaven    | `=[[Bryn Shander]].travel-easthaven`  |  
|   Good Mead    |    `=[[Bryn Shander]].travel-good`    | 
|   Lonelywood   | `=[[Bryn Shander]].travel-lonelywood` | 
|     Targos     |   `=[[Bryn Shander]].travel-targos`   |  
|   Termalaine   | `=[[Bryn Shander]].travel-termalaine` | 





--- column-end ---


|   Mount/Niles |                        Duration                        |
|:-------------:|:------------------------------------------------------:|
|    Bremen     |   `=[[Bryn Shander]].travel-bremen * this.travel-mount`   |
| Bryn Shander  |    `=[[Bryn Shander]].travel-bryn * this.travel-mount`    | 
| Caer-Dineval  |  `=[[Bryn Shander]].travel-dineval * this.travel-mount`   |
|  Caer-Konig   |   `=[[Bryn Shander]].travel-konig * this.travel-mount`    |
| Dougan's Hole |   `=[[Bryn Shander]].travel-dougan * this.travel-mount`   |
|   Easthaven   | `=[[Bryn Shander]].travel-easthaven * this.travel-mount`  |
|   Good Mead   |    `=[[Bryn Shander]].travel-good * this.travel-mount`    |
|  Lonelywood   | `=[[Bryn Shander]].travel-lonelywood * this.travel-mount` |
|    Targos     |   `=[[Bryn Shander]].travel-targos * this.travel-mount`   |
|  Termalaine   | `=[[Bryn Shander]].travel-termalaine * this.travel-mount` |

*Niles Ranger bonus halves travel time.*

--- column-end ---



|  Fast/Mount   |                        Duration                        |
| :-----------: | :----------------------------------------------------: |
|    Bremen     |   `=[[Bryn Shander]].travel-bremen * this.travel-fast`   |
| Bryn Shander  |    `=[[Bryn Shander]].travel-bryn * this.travel-fast`    |
| Caer-Dineval  |  `=[[Bryn Shander]].travel-dineval * this.travel-fast`   |
|  Caer-Konig   |   `=[[Bryn Shander]].travel-konig * this.travel-fast`    |
| Dougan's Hole |   `=[[Bryn Shander]].travel-dougan * this.travel-fast`   |
|   Easthaven   | `=[[Bryn Shander]].travel-easthaven * this.travel-fast`  |
|   Good Mead   |    `=[[Bryn Shander]].travel-good * this.travel-fast`    |
|  Lonelywood   | `=[[Bryn Shander]].travel-lonelywood * this.travel-fast` |
|    Targos     |   `=[[Bryn Shander]].travel-targos * this.travel-fast`   |
|  Termalaine   | `=[[Bryn Shander]].travel-termalaine * this.travel-fast` |

*Niles is absent as a variable.*

--- column-end ---



|     Slow      |                        Duration                        | 
| :-----------: | :----------------------------------------------------: | 
|    Bremen     |   `=[[Bryn Shander]].travel-bremen * this.travel-slow`   |  
| Bryn Shander  |    `=[[Bryn Shander]].travel-bryn * this.travel-slow`    |  
| Caer-Dineval  |  `=[[Bryn Shander]].travel-dineval * this.travel-slow`   |
|  Caer-Konig   |   `=[[Bryn Shander]].travel-konig * this.travel-slow`    | 
| Dougan's Hole |   `=[[Bryn Shander]].travel-dougan * this.travel-slow`   | 
|   Easthaven   | `=[[Bryn Shander]].travel-easthaven * this.travel-slow`  | 
|   Good Mead   |    `=[[Bryn Shander]].travel-good * this.travel-slow`    | 
|  Lonelywood   | `=[[Bryn Shander]].travel-lonelywood * this.travel-slow` | 
|    Targos     |   `=[[Bryn Shander]].travel-targos * this.travel-slow`   | 
|  Termalaine   | `=[[Bryn Shander]].travel-termalaine * this.travel-slow` | 



--- column-end ---


|   Difficult   |                          Duration                           |  
| :-----------: | :---------------------------------------------------------: |
|    Bremen     |   `=[[Bryn Shander]].travel-bremen * this.travel-difficult`   | 
| Bryn Shander  |    `=[[Bryn Shander]].travel-bryn * this.travel-difficult`    | 
| Caer-Dineval  |  `=[[Bryn Shander]].travel-dineval * this.travel-difficult`   | 
|  Caer-Konig   |   `=[[Bryn Shander]].travel-konig * this.travel-difficult`    |  
| Dougan's Hole |   `=[[Bryn Shander]].travel-dougan * this.travel-difficult`   | 
|   Easthaven   | `=[[Bryn Shander]].travel-easthaven * this.travel-difficult`  | 
|   Good Mead   |    `=[[Bryn Shander]].travel-good * this.travel-difficult`    |  
|  Lonelywood   | `=[[Bryn Shander]].travel-lonelywood * this.travel-difficult` | 
|    Targos     |   `=[[Bryn Shander]].travel-targos * this.travel-difficult`   | 
|  Termalaine   | `=[[Bryn Shander]].travel-termalaine * this.travel-difficult` | 


--- end-multi-column

## Overland Travel

Calculations cover how long it take to go a varying distance in the Tundra of The North.

| Miles |      Difficult/Tundra       |       Niles/Mount        |
|:-----:|:---------------------------:|:------------------------:|
|   1   | `=1 * this.mile-difficult`  | `=1 * this.mile-mount`  |
|   2   | `=2 * this.mile-difficult`  | `=2 * this.mile-mount`  |
|   3   | `=3 * this.mile-difficult`  | `=3 * this.mile-mount`  |
|   4   | `=4 * this.mile-difficult`  | `=4 * this.mile-mount`  |
|   5   | `=5 * this.mile-difficult`  | `=5 * this.mile-mount`  |
|   6   | `=6 * this.mile-difficult`  | `=6 * this.mile-mount`  |
|   7   | `=7 * this.mile-difficult`  | `=7 * this.mile-mount`  |
|   8   | `=8 * this.mile-difficult`  | `=8 * this.mile-mount`  |
|   9   | `=9 * this.mile-difficult`  | `=9 * this.mile-mount`  | 
|  10   | `=10 * this.mile-difficult` | `=10 * this.mile-mount` |
|  11   | `=11 * this.mile-difficult` | `=11 * this.mile-mount` |
|  12   | `=12 * this.mile-difficult` | `=12 * this.mile-mount` |
|  13   | `=13 * this.mile-difficult` | `=13 * this.mile-mount` |
|  14   | `=14 * this.mile-difficult` | `=14 * this.mile-mount` |
|  15   | `=15 * this.mile-difficult` | `=15 * this.mile-mount` |
|  16   | `=16 * this.mile-difficult` | `=16 * this.mile-mount` |
