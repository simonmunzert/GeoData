# Frei verfügbare öffentliche Daten
Jan-Philipp Kolb  
22 Februar 2017  




## Datenzugang

- Public-Use-File (PUF) Datei zur öffentlichen Nutzung - meist stark anonymisierte Daten
(Beispiele: [FDZ](www.forschungsdatenzentrum.de), [Statistik Portal](www.statistik-portal.de), [Meine Region](www.infothek.statistik.rlp.de/lis/MeineRegion/index.asp) )

- Scientific-Use-File (SUF) - Datei zur wissenschaftlichen Nutzung - anonymisierte Daten, die zu wissenschaftlichen Zwecken und zur Sekundäranalyse genutzt werden können. 
 
- On-Site-Nutzung - Arbeitsplätze für Gastwissenschaftler - Kontrollierte Datenfernverarbeitung


## Zensus Atlas

<https://ergebnisse.zensus2011.de/>

![Zensus Datenbank](figure/Zensusdtb.PNG)


## Forschungsdatenzentren

- Bspw. FDZ der statistischen Ämter:

<http://www.forschungsdatenzentrum.de/>

- Es werden hauptsächlich Public Use Files angeboten, 

- teilweise können Gewichtungsfaktoren verwendet werden um regionale Ergebnisse zu bekommen

- In der Regel ist Darstellung in Karten aber schwierig

## Weitere Amtliche Datenquellen

- Genesis

<https://www-genesis.destatis.de/genesis/online>

- Daneben gibt es Angebote der Landesämter bspw:

<https://www.statistik.rlp.de/regionaldaten/>

## Eurostat Daten

Sie können eine Statistik der Sparquote bei [Eurostat](http://ec.europa.eu/eurostat/web/euro-indicators/peeis) downloaden.

<http://ec.europa.eu/eurostat/web/euro-indicators/peeis>




```r
library(xlsx)
HHsr <- read.xlsx2("HHsavingRate.xls",1)
```



|geo                      |X2012Q3 |X2012Q4 |X2013Q1 |X2013Q2 |X2013Q3 |
|:------------------------|:-------|:-------|:-------|:-------|:-------|
|Euro area (19 countries) |9.82    |11.86   |11.37   |16.28   |10.34   |
|EU (28 countries)        |8.67    |10.92   |9.42    |14.63   |8.38    |
|Belgium                  |12.52   |9.33    |13.99   |19.03   |12.07   |
|Czech Republic           |10.16   |14.81   |9.46    |10.44   |10.12   |


## Datahub.io

- Viele Daten vorhanden, 
- bspw. zum UNESCO [Weltkulturerbe](http://datahub.io/dataset/unesco-world-heritage-sites/resource/d4116195-44d8-4bc1-9f91-9b570870dc19)
- Funktioniert nur im Windows Explorer ?????!!!!









|   |name_en                 | longitude| latitude|category_short |
|:--|:-----------------------|---------:|--------:|:--------------|
|4  |Butrint                 |     20.03|    39.75|C              |
|5  |Al Qal'a of Beni Hammad |      4.79|    35.82|C              |
|6  |M'Zab Valley            |      3.68|    32.48|C              |
|7  |DjÃ©mila                |      5.74|    36.32|C              |
|8  |Timgad                  |      6.63|    35.45|C              |