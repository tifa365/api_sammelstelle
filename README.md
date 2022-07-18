# API-Sammelstelle

Hier entsteht aktuell eine Sammelstelle für interessante APIs. Für die Darstellung werden dabei aktuell verschiedene Formate erprobt (s.u.).

## Liste von APIs

Die folgende Auflistung bezieht sowohl kommerzielle als auch nicht kommerzielle APIs mit und ohne Dokumentation in tabellarischer Form mit ein. 

| API | Description | Documented? | Documentation | Exemplary request |
|---|---|---|---|---|
| Aldi-Verkaufsfillialen API | Auflistung von Aldiläden im Umkreis einer festen Koordinate | No | NA | https://uberall.com/api/storefinders/ALDINORDDE_UimhY3MWJaxhjK9QdZo3Qa4chq1MAu/settings/de |
| DM Drogerien in Deutschland API | Findet die Orte von DM Drogerien im Umkreis einer Latitude/Longitue-Koordinate | No | NA | https://store-data-service.services.dmtech.com/stores/nearby/52.17093349999975,8.328556500000587/1 |
| opencorporates API | The API provides all the information available on the OpenCorporates website as data. | Yes | http://api.opencorporates.com/documentation/API-Reference | https://api.opencorporates.com/v0.4/companies/gb/00102498 |
| MediaWiki Action API | This page provides an overview of the MediaWiki Action API. | Yes | https://www.mediawiki.org/wiki/API:Main_page |  https://de.wikipedia.org/w/api.php?action=parse&page=Chaos_Computer_Club&format=json |
| Tagesschau API | Über API stehen via www.tagesschau.de aktuelle Nachrichten und Medienbeiträge im JSON-Format zur Verfügung | Yes | https://tagesschau.api.bund.dev/ |  https://www.tagesschau.de/api2/homepage/ |
| Die Zeit-API zum Coronavirus | Über die hauseigene API der Zeit stehen aktuelle Daten zum Coronavirus bereit | No | NA |  https://hsr-cdn.zeit.de/corona/get/?query=query%20DetailCountryQuery($id:%20String!)%20{%20countries(where:%20{id:%20{_eq:%20$id}})%20{%20id%20name%20lastUpdated%20population%20casesIncidence%20casesTodayLive%20casesTotal%20casesTrend%20casesLastDay%20casesLastWeek%20casesLastDayNewPublished%20casesLastUpdated%20deadTodayLive%20deadTotal%20deadTrend%20deadLastWeek%20deadLastDay%20deadLastUpdated%20patientsCovid19Trend%20patientsCovid19%20bedsCovid19Percentage%20diviLastUpdated%20hospitalizationsIncidence%20hospitalizationsIncidenceFrozen%20hospitalizationsLastWeek%20hospitalizationsLastWeekFrozen%20hospitalizationsTrend%20hospitalizationsLastUpdated%20peopleFullyVaccinatedPer100Total%20peopleVaccinatedPer100Total%20peopleBoosterVaccinatedPer100Total%20peopleFourthVaccinatedPer100Total%20peopleFullyVaccinatedTotal%20vaccinationsTrend%20vaccinationsPer100Total%20vaccinationsLastWeek%20vaccinationDosesLastUpdated%20recoveredTotal%20__typename%20}%20}%20&operationName=DetailCountryQuery&variables={%22id%22:%22DE%22} |

## Nicht mehr funktionsfähig
* https://developer.zeit.de/index/

## Weitere API-Zusammenstellungen

Weitere API-Sammlungen sind im Folgenden in Form von Links zu besonders interessanten Daten aufgelistet:

* [API-Liste](https://github.com/CorrelAid/projektzyklus-workshops/blob/main/07_datenmanagement-webdaten/api-list.md) Eine Sammlung von öffentlichen APIs von CorrelAid
* bund_dev: Eine umfangreiche Liste dokumentierter APIs von staatlichen Stellen findet sich auf [bund.dev/apis](https://bund.dev/apis). Auf diesem API-Portal des Bundes finden Sie Dokumentationen zu Programmierschnittstellen von Verwaltungsleistungen und Informationsportalen des Bundes. Die Einträge der aktuellen Liste - sowie perspektivisch auch weitere Listen dokumentierter APIs - lassen sich auch [hier](https://andreasfischer1985.github.io/code-snippets/html/js_apiCollection.html) einsehen und nach Suchbegriffen filtern.
* Public APIs: Auf der englischsprachigen Seite https://github.com/public-apis/public-apis findet sich eine umfangreiche Auflistung von APIs aus dem englischsprachigen Raum.
* [WoBike](https://github.com/ubahnverleih/WoBike) ist eine englischsprachige Sammlung von APIs zum Thema Scooter- und Bikesharing


