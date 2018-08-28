---
swagger: "2.0"
x-collection-name: ATTOM
x-complete: 0
info:
  title: Attom Data Solutions API Returns home sale information for properties within
    a geography.
  description: Get a list of home sale snapshots within a Onboard GeoID that sold
    within a date range and specified sale amount.
  version: 1.0.0
host: search.onboard-apis.com
basePath: /communityapi/v2.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /salestrend/snapshot:
    get:
      summary: Returns sales trends for a given zip code in yearly intervals
      description: Get the average sale price, median sale price, and count of sales
        for the past 2 years in yearly intervals.
      operationId: getSalesTrendByYear
      x-api-path-slug: salestrendsnapshot-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: endmonth
        description: The end month to search from
      - in: query
        name: endyear
        description: The end year to search from
      - in: query
        name: geoid
        description: A list of geographies that this property belongs to
      - in: query
        name: interval
        description: The interval to search from
      - in: query
        name: startmonth
        description: The start month to search from
      - in: query
        name: startyear
        description: The start year to search from
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Sales
      - Trendsa
      - Given
      - Zip
      - Code
      - In
      - Yearly
      - Intervals
  /sale/snapshot:
    get:
      summary: Returns home sale information for properties within a geography.
      description: Get a list of home sale snapshots within a Onboard GeoID that sold
        within a date range and specified sale amount.
      operationId: getHomeSaleSnapshotsGeoId
      x-api-path-slug: salesnapshot-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: query
        name: address1
        description: The first line of the mailing address
      - in: query
        name: address2
        description: The second line of the mailing address
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: endsalesearchdate
        description: The standardized date for search purposes
      - in: query
        name: geoid
        description: A list of geographies that this property belongs to
      - in: query
        name: maxsaleamt
        description: The recorded amount of the sale transaction
      - in: query
        name: minsaleamt
        description: The recorded amount of the sale transaction
      - in: query
        name: propertytype
        description: A specific property classification such as Detached Single Family
      - in: query
        name: radius
      - in: query
        name: startsalesearchdate
        description: The standardized date for search purposes
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Home
      - Sale
      - Informationproperties
      - Within
      - Geography
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---