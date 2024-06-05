# EWSS-CAMF-table
Common Alert Message Format Tables (for Japan)

### Common (International)

|Field|Name|File|
|---|---|---|
|A1|Message Type|[MessageType.json](MessageType.json)|
|A2|Country / Region name|[CountryRegionName.json](CountryRegionName.json)|
|A3|Provider identifier|[ProviderIdentifier.json](ProviderIdentifier.json)|
|A4|Hazard category and type|[HazardCategoryAndType.json](HazardCategoryAndType.json)|
|A5|Severity|[Severity.json](Severity.json)|
|A6|Hazard onset - week number|[HazardOnsetWeekNumber.json](HazardOnsetWeekNumber.json)|
|A7|Hazard onset - time of the week|[HazardOnsetTimeOfTheWeek.json](HazardOnsetTimeOfTheWeek.json)|
|A8|Hazard duration|[HazardDuration.json](HazardDuration.json)|
|A9|Selection of Guidance to react library|[SelectionOfGuidanceToReactLibrary.json](SelectionOfGuidanceToReactLibrary.json)|
|A10|Version of library|[VersionOfLibrary.json](VersionOfLibrary.json)|
|A11|Guidance to react library (International)|[GuidanceToReactLibrary_IC-A.json](GuidanceToReactLibrary_IC-A.json) (List-A)<br>[GuidanceToReactLibrary_IC-B.json](GuidanceToReactLibrary_IC-B.json) (List-B)|
|A12|Ellipse centre latitude|[EllipseCentreLatitude.json](EllipseCentreLatitude.json)|
|A13|Ellipse centre longitude|[EllipseCentreLongitude.json](EllipseCentreLongitude.json)|
|A14|Ellipse semi-major axis|[EllipseSemiMajorMinorAxis.json](EllipseSemiMajorMinorAxis.json)|
|A15|Ellipse semi-minor axis|[EllipseSemiMajorMinorAxis.json](EllipseSemiMajorMinorAxis.json)|
|A16|Ellipse azimuth angle|[EllipseAzimuthAngle.json](EllipseAzimuthAngle.json)|
|A17|Main subjects for specific settings|[MainSubjectForSpecificSettings.json](MainSubjectForSpecificSettings.json)|

### for Japan (L-Alert/J-Alert/Municipality-transmitted information)

|Field|Name|File|
|---|---|---|
|A11|Guidance to react library (Japan)|[GuidanceToReactLibrary_JP.json](GuidanceToReactLibrary_JP.json)|
|EX1|Target Area Code|[MunicipalityCode.json](MunicipalityCode.json)|
|EX2|Evacuate Direction Type|[EvacuateDirectionType.json](EvacuateDirectionType.json)|
|EX3|Additional Ellipse Centre Latitude|[AdditionalEllipseCentreLatitude.json](AdditionalEllipseCentreLatitude.json)|
|EX4|Additional Ellipse Centre Longitude|[AdditionalEllipseCentreLongitude.json](AdditionalEllipseCentreLongitude.json)|
|EX5|Additional Ellipse Semi-Major Axis|[EllipseSemiMajorMinorAxis.json](EllipseSemiMajorMinorAxis.json)|
|EX6|Additional Ellipse Semi-Minor Axis|[EllipseSemiMajorMinorAxis.json](EllipseSemiMajorMinorAxis.json)|
|EX7|Additional Ellipse Azimuth|[AdditionalEllipseAzimuth.json](AdditionalEllipseAzimuth.json)|
|EX8|Target Area Code List Type|[TargetAreaCodeListType.json](TargetAreaCodeListType.json)|
|EX9|Target Area Code List|[PrefectureCode.json](PrefectureCode.json) (if EX8=0 Prefecture)<br>[MunicipalityCode.json](MunicipalityCode.json) (if EX8=1 Municipality)

## WIP

|Field|Name|
|---|---|
|B1|Improved resolution of main ellipse|
|B2|Position of centre of hazard|
|B3|Secondary ellipse definition|
|B4-1|Quantitative or detailed information for Earthquake|
|B4-2|Quantitative or detailed information for Tsunami / tidal wave|
|B4-3|Quantitative or detailed information for Cold wave / heat wave|
|B4-4|Quantitative or detailed information for Tropical cyclone (hurricane)|
|B4-5|Quantitative or detailed information for Tropical cyclone (typhoon)|
|B4-6|Quantitative or detailed information for Tropical cyclone (typhoon)|
|B4-7|Quantitative or detailed information for Tornado|
|B4-8|Quantitative or detailed information for Storm or thunderstorm|
|B4-9|Quantitative or detailed information for Hail|
|B4-10|Quantitative or detailed information for Rainfall|
|B4-11|Quantitative or detailed information for Snowfall|
|B4-12|Quantitative or detailed information for Flood|
|B4-13|Quantitative or detailed information for Lightning|
|B4-14|Quantitative or detailed information for Wind chill/frost|
|B4-15|Quantitative or detailed information for Derecho|
|B4-16|Quantitative or detailed information for Fog|
|B4-17|Quantitative or detailed information for Snow storm / blizzard|
|B4-18|Quantitative or detailed information for Drought|
|B4-19|Quantitative or detailed information for Avalanche risk|
|B4-20|Quantitative or detailed information for Ash fall|
|B4-21|Quantitative or detailed information for Wind/wave/storm surge|
|B4-22|Quantitative or detailed information for Geomagnetic or solar storm|
|B4-23|Quantitative or detailed information for Terrorism|
|B4-24|Quantitative or detailed information for Forest fire / risk of fire|
|B4-25|Quantitative or detailed information for Contaminated drinking water/marine pollution|
|B4-26|Quantitative or detailed information for UV radiation|
|B4-27|Quantitative or detailed information for Risk of infection / pandemic|
|B4-28|Quantitative or detailed information for Noise pollution|
|B4-29|Quantitative or detailed information for Air pollution|
|B4-30|Quantitative or detailed information for Marine pollution / river pollution|
|B4-31|Quantitative or detailed information for Outage of Gas supply/IT systems/Power systems/Emergency number/Telephone line|
|B4-32|Quantitative or detailed information for Radiological hazard, nuclear hazard and nuclear power station accident|
|B4-33|Quantitative or detailed information for Chemical hazard|
|B4-34|Quantitative or detailed information for Biological hazard|
|B4-35|Quantitative or detailed information for Explosive hazard|
|C1|Refined latitude of centre of main ellipse|
|C2|Refined longitude of centre of main ellipse|
|C3|Refined semi-major axis length|
|C4|Refined semi-minor axis length|
|C5|Delta latitude from main ellipse centre|
|C6|Delta longitude from main ellipse centre|
|C7|Shift of second ellipse centre|
|C8|Homothetic factor of second ellipse|
|C9|Bearing angle of second ellipse|
|C10|Guidance library for second ellipse|

## Reference

 - [COMMON ALERT MESSAGE FORMAT SPECIFICATION Issue 1.0 | January 2024](https://www.gsc-europa.eu/sites/default/files/sites/all/files/EWSS-CAMF_v1.0.pdf)

 - [Quasi-Zenith Satellite System Interface Specification DCX Service (IS-QZSS-DCX-001)](https://qzss.go.jp/technical/download/ps-is-qzss.html)
