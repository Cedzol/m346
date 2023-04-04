# KN04

## A

### Instanz Details

Instanz typen

![Type](instance_type.png)

Instanz Speicher
![Speicher](instance_speicher.png)

Instanz Userdata

![Userdata](instance_userdata.png)

Instanzen
 
 DB Instanz

![DB](db_instance.png)

Webserver Instanz
![Web](server_instance.png)
Liste der Instanzen

![List](instances.png)

### Sites

/db.php

![DB](db.png)


![index](index.png)

/info.php
![info](info.png)

adminer page nach login mit admin credentials
![Adminer](adminer.png)


#### db konfiguration

db Server: /etc/mysql/mariadb.conf.d
localhost auf 0.0.0.0 ändern

## B

### a

Der S3 Speicher ist ein Object Storage. Daten werden als Objekte abgespeichert. Diese liegen in einem grossen Verzeichnis und ohne hirarchie.

### b 

#### 4

Das bei der erstellung der Instanz mit erstellte Volume wird mti gelöscht. Andere verknüpfte Ressourcen könnten weiterhin existieren

#### 5

Bei EBS Volumes kann der Wert von "Delete on termination" auf true gesetzt werden. Das heisst das bei der Terminierung der Instanz auch die ängehängten EBS Volumes mit dem Wert auf true mitgelöscht werden. 

EBS Volumes
![EBS 2](EBS_2.png)

EBS Volume deleted
![EBS 2](EBS_deleted.png)