Zugchat

    
# Usercases: 
## Tasche vergessen
## Wo ist der Zug
## ZugTinder
## Umstiegshilfe Adhoc
## Carpooling zum/vom Bahnhof
## Zuginfos
## Bahnhof/steig/gleis Infos
## Essen bestellen
## opendataportal
## ansprechpartnersuche



# TechStack
Synapse-Server-Config
Elements
Bridge
Bots

# Naming
Grosse Frage nach Art der Namen

* https://github.com/public-transport/why-linked-open-transit-data
* https://linkedconnections.org/

Es können Aliase genutzt werden.
Es können Informationen zwischen Räumen gespiegelt werden. (geteilte Züge)

## Navigation
Es kann Bot geben welche für die Orientierung von Verfügbaren Räumen Übersicht gibt.

z.B.in #BB-RE-5
```
> !list-live
< #BB-RE-5-93511,#RE-5-93359,RE-5-93509
```


![](images/ProductNummer-Zugnummer.png)
# Bridges

* https://github.com/matrix-org/matrix-appservice-bridge/blob/develop/HOWTO.md
* https://github.com/spantaleev/matrix-docker-ansible-deploy/issues/186

# Data

## SollFahrplan
    https://download-data.deutschebahn.com/static/datasets/regiohack-tempdata/paket_3_2_soll_fahrplan.zip 2.3 GB / 53GB

## GTFS Positionen

* https://developer.geops.io/apis/realtime/ 

## Tools: 
* csvkit