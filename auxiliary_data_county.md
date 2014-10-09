---
title: "County-Level Data"

---

***
***
# Purpose

These datasets are made available to assist other researchers investigating the factors affecting Oklahoma families.  If you have questions, please post a comment at the bottom of this page.

***
***
# Datasets
The following datasets have one row for each Oklahoma County.

***
## County Characteristics
[Download](./data_phi_free/CountyCharacteristics.zip).

The dataset indicates a county's characteristics, with the following fields:

| Variable Name | Type | Variable Description |
| :------------ | :--- | :------------------- |
| CountyID | integer | Alphabetically-ordered ID of a county.  Notice that `Mc` precedes `M`. |
| CountyName | string | The name of the county. |
| GeoID | integer | The county's FIPS code, which is useful for merging with Census data, or cartographic polygons. |
| FundingC1 | bit | Indicates if the county receives funding for C1. |
| FundingOcap | bit | Indicates if the county receives funding for OCAP. |
| C1LeadNurseRegion | integer | Oklahoma's 77 counties are categorized into roughly 20 regions, each with it's own "lead nurse". |
| Urban | bit | Indicates if the county is either Oklahoma or Tulsa (because they operate differently for HV services). |
| LabelLongitude | float | The longitude of a good place to label the county with on a map. |
| LabelLatitude | float | The latitude of a good place to label the county with on a map. |
| MiechvEvaluation | bit | Indicates if the county participates in the 2011 MIECHV "Evaluation Grant". |
| MiechvFormula | bit | Indicates if the county participates in the 2011 MIECHV "Formula Grant". |
| WicNeedPopInfant | integer | The number of "infants in need", as estimated by WIC. |
| WicNeedPopTotal | integer | The number of "people in need", as estimated by WIC. |
| WicYear | integer | The of the WIC estimates of need. |

***
## C1 Counts
[Download](./data_phi_free/C1CountCounty.zip).

The dataset indicates something about C1 (i'm including this for now as a place holder)

| Variable Name | Type | Variable Description |
| :------------ | :--- | :------------------- |
| CountyID | integer | Alphabetically-ordered ID of a county.  Notice that `Mc` precedes `M`. |
| CountyName | string | The name of the county. |
| GeoID | integer | The county's FIPS code, which is useful for merging with Census data, or cartographic polygons. |
| FundingC1 | bit | Indicates if the county receives funding for C1. |
| FundingOcap | bit | Indicates if the county receives funding for OCAP. |
| C1LeadNurseRegion | integer | Oklahoma's 77 counties are categorized into roughly 20 regions, each with it's own "lead nurse". |
| Urban | bit | Indicates if the county is either Oklahoma or Tulsa (because they operate differently for HV services). |
| LabelLongitude | float | The longitude of a good place to label the county with on a map. |
| LabelLatitude | float | The latitude of a good place to label the county with on a map. |
| MiechvEvaluation | bit | Indicates if the county participates in the 2011 MIECHV "Evaluation Grant". |
| MiechvFormula | bit | Indicates if the county participates in the 2011 MIECHV "Formula Grant". |
| WicNeedPopInfant | integer | The number of "infants in need", as estimated by WIC. |
| WicNeedPopTotal | integer | The number of "people in need", as estimated by WIC. |
| WicYear | integer | The of the WIC estimates of need. |
