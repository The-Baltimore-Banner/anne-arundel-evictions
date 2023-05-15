# 2023 Anne Arundel Evictions
================
- [Overview](#overview)
- [Methodology](#method)
- [License](#license)


## Overview


The Forest has filed at least 6,344 eviction cases in the past 52 months, likely an undercount because dismissed cases don’t get entered into public records. Yet records show Hendersen-Webb has filed at least six evictions for each unit at The Forest since 2019, according to a Baltimore Banner analysis of electronically available failure-to-pay-rent cases.


One in three evictions at all large multifamily apartment complexes in the county takes place in the 1.5 square miles of monotonous apartment complexes around the University of Maryland Medical Center where The Forest is located, according to the Banner analysis.


The complex is a focal point of a crisis facing low-income tenants throughout Maryland. he population includes a high number of single mothers and Black women, who are caught at the breaking point of the affordability crisis: The lowest prices in the county are still out of reach.


The three complexes that make up The Forest have three of the four highest eviction filings rates in the county. On average, Hendersen-Webb files evictions for 13% of its units each month. Before the pandemic upended business as usual, it filed against 28% of its units each month.


Read the story: [Inside the eviction epicenter of Anne Arundel County](www.thebaltimorebanner.com//community/housing/eviction-anne-arundel-county-glen-burnie-TMT674HSCVAMVHGORXG4Y2IIRY/).


<a id="method"></a>


## Methodology
### How we analyzed evictions in Anne Arundel County


This analysis of eviction filings is an analysis of case details pages systematically reviewed on the [Maryland Judiciary's Case Search website](https://casesearch.courts.state.md.us/casesearch/inquiry-index.jsp). Case files prior to 2022 were reviewed in Summer 2022. Case files from 2022 and the first four months of 2023 were reviewed in May 2023. Raw data has been restructured to remove the names of defendants. Some data points in this story cannot be recreated accurately without this data. If you have questions about that part of the analysis, please email [Ryan Little](mailto:ryan.little@thebaltimorebanner.com).


Defendant addresses were used to identify the parcel of land where an eviction was filed for. Addresses were geocoded using [Geocodio](https://www.geocod.io/). About 92% of addresses were geocoded to the rooftop accuracy. This is much higher than is to be expected. Geocodio documentation expects 7 in 10 addresses to be geocoded at this level. All other evictions were not included in this analysis since they could not be accurately tied to a property.


Geocoded evictions were tied to parcels using the [Anne Arundel County Parcel Database](https://opendata.aacounty.org/datasets/AnneArundelMD::parcels-12/explore). Multifamily parcels were identified using the "m" entry in "asst_use_code". Large parcels were defined as those with 10 or more units. Parcels were named for their "asst_first_owner" name. Dwelling unit counts were taken from this database.


Hendersen-Webb-owned properties could be identified using the "madr_line_1" column but this was not always possible with all other multifamily complexes.


ACS 5-year data from 2021 was used for Census analysis. Pearson correlations were used to identify Census data that correlates with filings and unit filings rates.


Parcels that span multiple Census tracts were split into those census tracts based on the share of their overlapping area. If 40% of a parcel was in a given census tract, 40% of its dwelling units and evictions were assigned to that tract.


<a id="license"></a>


## License


Copyright 2023, The Venetoulis Institute for Local Journalism


Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:


1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.


2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.


3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
