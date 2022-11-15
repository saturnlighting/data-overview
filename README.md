SATURN data overview
================

This repository presents an overview of the different datasets that
could be used for the SATURN project.

# Variables and datasets

The main variables of the SATURN project are cycling levels and road
lighting. Road safety and crime are relevant. Other interesting
variables are individual variables such as gender, age, income, and
environmental variables such as infrastructure and spatial deprivation.

<table class="table" style="margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
Dataset
</th>
<th style="text-align:left;">
Variable
</th>
<th style="text-align:left;">
Geographical coverage
</th>
<th style="text-align:left;">
Years
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Traffic counts (Department for Tranport)
</td>
<td style="text-align:left;">
cycling levels
</td>
<td style="text-align:left;">
Great Britain
</td>
<td style="text-align:left;">
1993-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
STRAVA
</td>
<td style="text-align:left;">
cycling levels
</td>
<td style="text-align:left;">
Global
</td>
<td style="text-align:left;">
2010-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
National Travel Survey (NTS)
</td>
<td style="text-align:left;">
cycling levels
</td>
<td style="text-align:left;">
Residents of England within Great Britain
</td>
<td style="text-align:left;">
2010-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
Active Lives Adult Survey (ALS)
</td>
<td style="text-align:left;">
cycling levels
</td>
<td style="text-align:left;">
England
</td>
<td style="text-align:left;">
2017-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
Transport for London (TfL) counters
</td>
<td style="text-align:left;">
cycling levels
</td>
<td style="text-align:left;">
London
</td>
<td style="text-align:left;">
2013-2022
</td>
</tr>
<tr>
<td style="text-align:left;">
OSM (openinfra project `oi_is_lit()` function)
</td>
<td style="text-align:left;">
road lighting
</td>
<td style="text-align:left;">
Global
</td>
<td style="text-align:left;">
2012-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
nightlight-data
</td>
<td style="text-align:left;">
road lighting
</td>
<td style="text-align:left;">
Glasgow and Edinburgh areas
</td>
<td style="text-align:left;">
2021, 2022
</td>
</tr>
<tr>
<td style="text-align:left;">
VIIRS satellite imagery
</td>
<td style="text-align:left;">
light levels
</td>
<td style="text-align:left;">
global
</td>
<td style="text-align:left;">
2014-present
</td>
</tr>
<tr>
<td style="text-align:left;">
STATS19
</td>
<td style="text-align:left;">
road safety
</td>
<td style="text-align:left;">
Great Britain
</td>
<td style="text-align:left;">
1979-2021
</td>
</tr>
<tr>
<td style="text-align:left;">
FARS (Fatality Analysis Reporting System)
</td>
<td style="text-align:left;">
road safety
</td>
<td style="text-align:left;">
US
</td>
<td style="text-align:left;">
1975-2020
</td>
</tr>
<tr>
<td style="text-align:left;">
DATA POLICE UK
</td>
<td style="text-align:left;">
crime
</td>
<td style="text-align:left;">
England, Wales and Northern Ireland
</td>
<td style="text-align:left;">
2013-2022
</td>
</tr>
<tr>
<td style="text-align:left;">
STRAVA
</td>
<td style="text-align:left;">
individual variables (e.g. gender, age, etc.)
</td>
<td style="text-align:left;">
Global
</td>
<td style="text-align:left;">
2010-2022
</td>
</tr>
<tr>
<td style="text-align:left;">
OSM
</td>
<td style="text-align:left;">
cycling infrastructure
</td>
<td style="text-align:left;">
Global
</td>
<td style="text-align:left;">
2015-2018
</td>
</tr>
<tr>
<td style="text-align:left;">
IMD
</td>
<td style="text-align:left;">
spatial deprivation
</td>
<td style="text-align:left;">
England
</td>
<td style="text-align:left;">
2019
</td>
</tr>
<tr>
<td style="text-align:left;">
Near Miss project data
</td>
<td style="text-align:left;">
Near misses
</td>
<td style="text-align:left;">
England
</td>
<td style="text-align:left;">
???
</td>
</tr>
</tbody>
</table>
<!-- # Cycling levels -->
<!-- One of the main challenges of the SATURN project is which dataset to choose as a proxy for cycling levels. Several possibilities are being considered. The following table shows the pros and cons of each of them. -->

# Relevant links

- Traffic counts: <https://roadtraffic.dft.gov.uk/downloads>,
  <https://github.com/ITSLeeds/dftTrafficCounts>

- STRAVA Metro data
  <https://www.ubdc.ac.uk/data-services/data-catalogue/transport-and-mobility-data/strava-metro-data/>

- National Travel Survey
  <https://www.gov.uk/government/collections/national-travel-survey-statistics>

- Active Lives Survey
  <https://www.sportengland.org/research-and-data/data/active-lives>

- TfL cycle counts <https://cycling.data.tfl.gov.uk/>

- Safer Active project:
  <https://saferactive.github.io/trafficalmr/articles/report3.html>,
  <https://saferactive.github.io/trafficalmr/articles/report4.html>,
  <https://github.com/saferactive/saferactive/blob/master/code/tests/bradford-and-beyond.md>

- Lighting presence
  <https://udsleeds.github.io/openinfra/reference/oi_is_lit.html>;
  <http://ubdc.gla.ac.uk/dataset/nightlight-data>

- VIIRS link:
  <https://developers.google.com/earth-engine/datasets/catalog/NOAA_VIIRS_DNB_MONTHLY_V1_VCMSLCFG>

- Road safety:
  <https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data>,
  <https://cran.r-project.org/web/packages/stats19/index.html>,
  <https://elipousson.github.io/crashapi/>,
  <https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars>

- Crime: <https://data.police.uk/data/archive/>;
  <https://github.com/njtierney/ukpolice>

- Infrastructure: <https://github.com/udsleeds/openinfra/issues/105>,
  <https://github.com/udsleeds/openinfra/blob/main/data-small/atf-funds.csv>
