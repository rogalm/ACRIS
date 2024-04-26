# Passenger Seamless Travel Technical Realilsation
Export from ACRIS Semantic Model from Enterprise Architect. <br>
# Passenger Seamless Travel Domain Model <br>
## Address
Version: 4.6.0
Description: Information about a unique location for 1) a physical or geographical location or 2) an Internet or IP address. 

Information about the place where a person or organization can be found or communicated with

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Number ` | String | Information about the unique number of the address. It could be a house number or e-mail address |
| ` Street ` | String | Information about the residence street of a passenger party |
| ` City ` | String | Information about the residence city of a passenger party |
| ` County ` | String | Information about the residence country of a passenger party |
| ` State ` | String | Information about the residence state of a passenger party |
| ` Province ` | String | Information about the residence province of a passenger party |
| ` Country ` | String | Information about the residence country of a passenger party |
| ` Post Code ` | String | Information about the residence post code or zip code of a passenger party |
| ` Address Category ` | Address Category | Information about the use of an address, such as business, residential. |
## Application
Version: 4.6.0
Description: Information about the software components that deliver information services to a person or other software components

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | Integer | Information that identifies an application |
| ` Description ` | Integer | Information that describes an application |
| ` System ` | System | Information that describes the system that hosts the application |
## Bag Item
Version: 4.6.0
Description: A bag is a logistic item owned by the passenger but transported and managed by the Airline and Airports.


| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Cabin Class ` | String | Information about a logistic item that indicates the travel class category of the owner as assigned by the Airline. It may also be known as the passenger class of a bag. This information is unique to every airline. |
| ` Checked Weight ` | Integer | Information that describes the checked weight of a logistic item |
| ` Check-in Date ` | Date Time Period | Information about the date that the bag was identified at a check in desk. |
| ` Check-in Location ` | String | Information that describes the location where the check-in event for the bag occurred. |
| ` Description ` | String | Information that describes the bag |
| ` Check-in Time ` | Time | Information about the time that the bag was identified at a check in desk. |
| ` Format Code ` | String | Format code for Boarding pass issued, can only be M for Multiple, see Reso 792 |
| ` Reclaim Location ` | Location | Information about the reclaim location for the bag |
| ` Identifier ` | String | Information that identifies the bag for example the bag tag |
| ` Description ` | String | Additional information that describes the bag |
| ` Number ` | String | Information about the document number that identifies the bag. |
| ` Global Unique Identifier ` | Integer | Information about an identifier assigned by the business to a logistic item which is unique throughout the entire item management process |
| ` Handler ` | String | Information about the handling agent associated with the logistic item. |
| ` Height ` | Integer | Information about the height physical dimension of a logistic item. |
| ` Length ` | Integer | Information about the length physical dimension of the bag |
| ` Owner ` | Passenger Party | Information about the owner of the bag |
| ` Scan Date ` | Date Time Period | Information about the date that a logistic item was scanned |
| ` Scan Time ` | Time | Information about the time that a logistic item was scanned |
| ` Volume ` | Integer | Information about the volume of the bag |
| ` Width ` | String | Information about the measured width of the bag |
## Bag Item Information Request
Version: 1.0
Description: Information request about passenger bags at the Airport
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String |  |
| ` Description ` | String |  |
| ` Date ` | DateTime |  |
## Flight Information Request
Version: 2.6.0
Description: 
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Request Date ` | Date |  |
| ` Request Time ` | Time |  |
## Location
Version: 4.6.0
Description: Information about a geographic position, line or area.

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Arrival Airport ` | String | Information about the place or port at which a passenger arrives |
| ` Departure Airport ` | String | Information about the place or port from which a passenger departs |
| ` Description ` | String | The description assigned by the business to the location |
| ` Type ` | Location Type | The list of types of location |
## Location Type
Version: 4.6.0
Description: Location type may be Geopolitical or Geospatial.
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Geopolitical ` | String | This is the geopolitical category for a location |
| ` Geospatial ` | String | This is the geospatial category for a location |
## System
Version: 4.6.0
Description: Information about instrumentality that combines interrelated interacting artifacts designed to work as a coherent entity.

For example, the expression, "the system consists of a motor and a small computer" indicates that the system comprises of two artefacts.

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | Integer | Information that identifies a system |
| ` Description ` | Integer | Information that describes a system |
## Weather
Version: 1.0
Description: 
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String |  |
| ` Location ` | String |  |
| ` Observation ` | String |  |
| ` Sampling ` | String |  |
| ` Date ` | DateTime |  |
| ` Procedure ` | String |  |
| ` Feature Of Interest ` | String |  |
| ` Air Temperature ` | String |  |
| ` Dewpoint Temperature ` | String |  |
| ` Vertical Visibility ` | String |  |
| ` Wind Direction ` | String |  |
| ` Horizontal Visibility ` | String |  |
| ` Wind Speed ` | String |  |
| ` Cloud Condition ` | String |  |
## Airline Party
Version: 4.6.0
Description: Information about an organisation that operates scheduled flights utilising Aircrafts as resources
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` ICAO Identifer ` | String | Information about a unique identifier assigned by ICAO to identify the Airline |
| ` IATA Identifier ` | String | Information about a unique identifier assigned by ICAO to identify the Airline |
| ` Description ` | String | Information that describes the Airline |
| ` Operational Location ` | String | Information that describes the operational base location of the Airline |
| ` Country ` | String | Information that describes the country of registration of the Airline |
| ` Contact ` | String | Information about the  Airline contact details - telephone, email, etc |
| ` Type ` | String | Information about the  type of Airline - Marketing or Operating Airline |
## Passenger Party
Version: 4.6.0
Description: Information about individuals, identifiable groups that purchase and use air transport services. Examples include transfer and final destination passengers
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Date Of Birth ` | Time Period | Information about the date of birth of a party |
| ` Gender ` | String | Information on the gender of a passenger party |
| ` Citizenship ` | String | Information on the status of a citizen with rights and duties |
| ` Place Of Birth ` | String | Information about the place of birth of a party |
| ` Country ` | String | Primary country of residence |
| ` Description ` | String | Information that describes the party |
| ` Contact ` | String | Information about the Party contact Details - telephone, email, etc. |
| ` Nationality ` | String | Information on the status of belonging to a particular nation by birth or naturalisation. |
| ` Number ` | Integer | A unique number assigned by the business or any other authority to track a Passenger Party. |
| ` Status ` | Aircraft Movement Status | Information regarding status of passenger. See Resolution 792 attachment C for the values to be used |
## Airport Facility
Version: 4.6.0
Description: Information about a building or infrastructure used to provide a air transport service.

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Arrival Airport ` | String | Information about the destination of flights |
| ` Capacity ` | Integer | Information about the maximum capacity level of the Airport |
| ` Departure Airport ` | String | Information about the originating Airport |
| ` Description ` | String | Information about the description of the Airport |
| ` Embarkation Airport ` | String | Information about the Airport where the Passenger boarded the flight |
| ` Type ` | FacilityType | Information about the  subdivision of the Airport facilities involved in the provision of services |
## Date Time Period
Version: 4.6.0
Description: The information about the specific day of an event, a type of  (category of) Time.

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Year ` | String | Year identifier in YYYY format. |
| ` Month Numeric ` | Integer | Month number in the calendar year, 1 through 12. |
| ` Month Name ` | String | Month name |
| ` Week Number Within Current Year ` | Integer | Week number within the current year, 1 through 53 (ie 52+1). |
| ` Week Number Within Current Month ` | Integer | Week number within the current month |
| ` Day Of The Year ` | Integer | Day number within the current year, 1 through 366. |
| ` Day Of The Month ` | Integer | Day number within the current month, 1 through 31. |
| ` Day Of The Week Name ` | String | Day of the week, Sunday through Saturday. |
| ` Day Of The Week Number ` | Integer | Day number within the current week, 1 through 7. |
## Day Time Period
Version: 4.6.0
Description: A particular day of the week (Mon-Sun)
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Mon ` |  |  |
| ` Tue ` |  |  |
| ` Wed ` |  |  |
| ` Thu ` |  |  |
| ` Fri ` |  |  |
| ` Sat ` |  |  |
| ` Sun ` |  |  |
## Aircraft Movement
Version: 4.6.0
Description: Information relating to planned or spontaneous change in location or movement of an Aircraft which is of interest to Heathrow Airport
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Actual Time Of Arrival ` | DateTime | ATA. The actual time of arrival of an inbound flight |
| ` Actual Time Of Departure ` | DateTime | ATD. The actual time of departure for an outbound flight |
| ` Aircarft Terminal ` | String | Terminal where the aircraft is located. |
| ` Airline Party Identifier ` | String | The Airline number that may be combined with the Flight number as proposed in the IATA standards |
| ` Code ` | String | A business defined code assigned to the movement |
| ` Departure Date ` | Date Time Period | Information about the date of departure of a flight ( type of aircraft movement) |
| ` Description ` | String | Free text |
| ` Duration ` | Integer | The estimated flight duration time (the time  from off blocks to block time). |
| ` End Date ` | DateTime | Information about the end date of the movement |
| ` IATA Identifier ` | String | Information about the IATA identification code for the flight. It is a combination of the IATA Identifier for the Airline and Flight Number |
| ` IATA Number ` | Integer | Information about the IATA number for the flight |
| ` ICAO Identifier ` | String | The ICAO identification for the flight. A single alphanumeric string giving an ICAO compliant representation of the main Flight Identifier. This will include a 3 character ICAO carrier code, flight number stripped of leading zeroes where necessary and an optional suffix character. Most flights using BAA Airports use IATA Flight Identifiers but certain users such as Air Traffic Control may wish to see information presented in ICAO format and such users can be shown the contents of this element rather than the main Flight Identifier. |
| ` ICAO Number ` | Integer | Information about the  ICAO number for the flight. |
| ` Scheduled Time ` | DateTime | Informationn about the scheduled time for the flight |
| ` Scheduled Time Of Arrival ` | DateTime  | Information about the scheduled date and time of arrival (STA) for an outbound flight (always UTC unless explicitly used within a public container such as with Advance Passenger Information). |
| ` Scheduled Time Of Departure ` | DateTime | Information about the scheduled date and time of departure (STD) for an outbound flight (always UTC unless explicitly used within a public container such as with Advance Passenger Information). |
| ` Start Date ` | DateTime | Information about the start date of the flight. The scheduled flight origin date based on the flight not the flight leg.  This date must not change once intialized in an AIDX message. |
## Airline Party Information Request
Version: 4.6.0
Description: A subset of Airline information requested by a Passenger

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the Airline data |
| ` Description ` | String | Information that describes the Airline information |
## Airport Facility Information Request
Version: 4.6.0
Description: A subset of information requested by the passenger that describes the Airport. Examples include security waiting times and information on lost items

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the Airport information |
| ` Description ` | String | Information that describes the Airport information |
## Flight Service Bookmark
Version: 4.6.0
Description: Information about the search results of a query on flight information that may be saved by the passenger
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the bookmark |
| ` Description ` | String | Information that describes the bookmark |
## Lost and Found Item
Version: 4.6.0
Description: Information about a collection of data and information with identified boundaries. Examples include paper documents and digital / electronic messages

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Description ` | String | Information that describes content. |
| ` Format Code ` | String | Format code for Boarding pass issued, can only be M for Multiple, see Reso 792 |
| ` Identifier ` | String | Information about the Identifier of information content e.g. the passport or visa number |
| ` Number ` | String | Information about the document number. |
## Passenger Party Credentials
Version: 4.6.0
Description: Information that describes the certification, privileges and access rights of a passenger. Examples include access privileges provided by the VISA and Passports 

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identify the privileges associated with a certifying document e.g. the passport or visa number |
| ` Description ` | String | Information that describes the privileges associated with a certifying document |
| ` Privileges ` | String | detailed information about the commitment and privileges provided by the document |
| ` Type ` | String | Information about the type of passenger credential |
## Passenger Party Planned Movement
Version: 4.6.0
Description: A collection of data and information that describes the passenger itinerary.  Examples include final destination, time of arrival etc

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Time Of Arrival ` | Time Period | Information on time of arrival at destination |
| ` Weather Condition ` | Weather Information Request | Information that describes the weather condition at destination of travel |
| ` Destination ` | String | Information that describes the destination |
| ` Identifier ` | String | The Identifier of information content |
## Passenger Party Travel Document
Version: 4.6.0
Description: Information that identifies a person and the privileges provided by a certification authority including a government agency. Examples include the passport information and other travel documents

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the travel document |
| ` Description ` | String | Information that describes the travel document |
| ` Type ` | String | Information that describes the type of travel document |
| ` Certification Authority ` | String |  |
| ` Expiry Date ` | Date Time Period | Information about the expiry date for the passport or visa |
| ` Issued Date ` | Date Time Period | Information about the document number. |
## Reservation Request
Version: 4.6.0
Description: Information about the reservation request made by a passenger
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the reservation request made by a passenger |
| ` Description ` | String | Information that describes the reservation request made by the passenger |
| ` Date ` | Date Time Period | Information about the date the reservation was made |
| ` Time ` | Time Period | Information about the time the reservation was made |
## Security Queue Waiting
Version: 4.6.0
Description: Information about a collection of data and information with identified boundaries. Examples include paper documents and digital / electronic messages
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Description ` | String | Information that describes content. |
| ` Format Code ` | String | Format code for Boarding pass issued, can only be M for Multiple, see Reso 792 |
| ` Identifier ` | String | Information about the Identifier of information content e.g. the passport or visa number |
| ` Number ` | String | Information about the document number. |
## Service Bookmark
Version: 4.6.0
Description: Information about the search results of a query on service information that may be saved by the passenger

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information about the service bookmark |
| ` Description ` | String | Information that describes the service bookmark |
## Service Information Request
Version: 4.6.0
Description: Information request about the collection of business services available at the Airport
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information identifier |
| ` Description ` | String | Information that describe the service information |
| ` Date ` | DateTime |  |
## Weather Information Request
Version: 4.6.0
Description: A passenger request for information about the weather condition of interest to the Passenger. This includes the general weather condition and the temperature

| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies the weather information |
| ` Description ` | String | Information that describes the weather information |
| ` Date ` | DateTime |  |
## Retail Service
Version: 4.6.0
Description: Information about the products, proposals, expected or agreed duties, functions or activities which BAA offers to other Parties.
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | Information that identifies an offering |
| ` Description ` | String | Information that describes an offering |
## Aircraft Movement Status
Version: 4.6.0
Description: Information that describes the condition of a flight based on the values of its attributes
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | Integer | Information that identifies the condition or status of a flight |
| ` Name ` | String | Information about the business name for the flight status |
| ` Description ` | String | Information that describes the condition or status of a flight |
## Bag Item Status
Version: 4.6.0
Description: Information that describes the condition of a bag based on the values of its attributes
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | Integer | Information that identifies the condition or state of a bag |
| ` Name ` | String | The business name for the status or condition of the bag |
| ` Description ` | String | Information that describes the condition or state of a bag |
## Service
Version: 4.6.0
Description: Information about the expected or agreed duties, functions or activities which BAA offers to other Parties.
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Identifier ` | String | The identifier for the service |
| ` Type ` | Service Type | The type of the service e.g. check-in, security |
| ` Description ` | String | The description of the service |
| ` IATA Service Type ` | IATA Service Type | Information about IATA classification codes for Services |
| ` Status ` | Service Status |  |
## Time Period
Version: 4.6.0
Description: Information about the start and end time for business events of interest to Heathrow Airport.
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Date ` | Date Time Period | Information about the categories of date items |
| ` Duration ` | Integer | It is the difference between the start time and end time, typically in seconds |
| ` Effective Date ` | DateTime | Indicates the starting date. |
| ` End ` | DateTime | The end time of the incident |
| ` Expire Date ` | DateTime | Indicates the ending date. |
| ` Start ` | DateTime | The start time of the incident |
| ` Day Of the Week ` | Day Time Period | Information about the day of the week |
## Service Type
Version: 4.6.0
Description: This is the type of service provided by a Party
| Term                | Type     | Description  |
| ------------------- | ----------- | ------------ |
| ` Code ` | String | Information about the code of the service category |
| ` Description ` | String | Information about the description of the service category |
