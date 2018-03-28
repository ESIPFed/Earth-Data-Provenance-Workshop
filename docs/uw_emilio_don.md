# Relevant projects from Emilio Mayorga and Don Setiawan

## 1. ODM2 (Observations Data Model 2) data model and software ecosystem
[ODM2](http://odm2.org): a data model and associated software ecosystem that explicitly track actions associated with data provenance (e.g. who manipulated the data, what institutes are involved); each action is stored as a record in a database; includes tracking of physical samples via registered IGSN’s. Describe progress and extent of community buy-in to date. 
- Schema: http://odm2.github.io/ODM2/schemas/ODM2_Current/diagrams/ODM2OverviewSimplified.html
- [CZIMEA](https://github.com/BiG-CZ/CZIMEA) (ODM2 application in EarthCube) [Poster](https://github.com/BiG-CZ/CZIMEA/blob/master/EMayorga_ECAHM2017_Poster.pdf)

## 2. NANOOS-IOOS
[NANOOS](http://nanoos.org)-IOOS: Regional-national integration of marine monitoring data, with a focus on sensor-based near-real-time observations and model forecasts. Partnering with local-regional data providers (academic, industry, local-state-tribal governments) to integrate and expose their data streams via both a user-friendly web application and open, interoperable services that are in turn integrated nationally by IOOS (US Integrated Ocean Observing System). Using a mix of standards and services families: 
- netcdf/CF/CDM/ACDD/OPeNDAP
- OGC SOS/O&M/SensorML/WMS/CSW
- ISO 19115-2
- Darwin Core/WorMS
- MMI-hosted vocabularies

Opportunities to expose some of these datastreams and currently captured provenance via PROV?

Relevant NANOOS and IOOS resources to show some of the elements of this distributed, standards-based data network:

- [NANOOS Visualization System, NVS](http://nvs.nanoos.org)
- https://ioos.noaa.gov/data/
- https://ioos.us/
- https://registry.ioos.us/harvests
- https://data.ioos.us/
- Example NANOOS SOS DescribeSensor SensorML response: [http://data.nanoos.org/52nsos/sos/kvp?service=SOS&outputFormat=text/xml; subtype="sensorML/1.0.1/profiles/ioos_sos/1.0"&version=1.0.0&request=DescribeSensor&procedure=urn:ioos:station:nanoos:nerrs_sostcmet](http://data.nanoos.org/52nsos/sos/kvp?service=SOS&version=1.0.0&request=DescribeSensor&procedure=urn%3Aioos%3Astation%3Ananoos%3Anerrs_sostcmet&outputFormat=text%2Fxml%3B%20subtype%3D%22sensorML%2F1.0.1%2Fprofiles%2Fioos_sos%2F1.0%22)
