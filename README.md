# Predict-Crime-Rate-in-Chicago


1. The Chicago Crime dataset contains a summary of the reported crimes occurred in the City of Chicago from 2001 to 2017.
2. Dataset has been obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.
3. Dataset contains the following columns:
   ID: Unique identifier for the record.
   Case Number: The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.
   Date: Date when the incident occurred.
   Block: address where the incident occurred
   IUCR: The Illinois Uniform Crime Reporting code.
   Primary Type: The primary description of the IUCR code.
   Description: The secondary description of the IUCR code, a subcategory of the primary description.
   Location Description: Description of the location where the incident occurred.
   Arrest: Indicates whether an arrest was made.
   Domestic: Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
   Beat: Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police          beat car.
   District: Indicates police district where the incident occurred.
   Ward: The ward (City Council district) where incident occurred.
   Community Area: Indicates the community area where the incident occurred. Chicago has 77 community areas.
   FBI Code: Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS).
   X Coordinate: The x coordinate of the location where the incident occurred in State of Illinois.
   Y Coordinate: The y coordinate of the location where the incident occurred in State of Illinois.
   Year: Year the incident occurred.
   Updated On: Date and time the record was last updated.
   Latitude: The latitude of the location where the incident occurred. This location is shifted from the actual location for partial               redaction but falls on the same block.
   Longitude: The longitude of the location where the incident occurred. This location is shifted from the actual location for partial             redaction but falls on the same block.
   Location: The location where the incident occurred

# Project Implementation

1. Prophet is open source software released by Facebook’s Core Data Science team.
2. Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly,          weekly, and daily seasonality, plus holiday effects.
3. Prophet works best with time series that have strong seasonal effects and several seasons of historical data.
4. For more information, please check this out:
   https://research.fb.com/prophet-forecasting-at-scale/
   https://facebook.github.io/prophet/docs/quick_start.html#python-api
