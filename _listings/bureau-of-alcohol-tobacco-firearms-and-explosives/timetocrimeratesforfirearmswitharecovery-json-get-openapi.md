---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API Time To Crime Rates For Firearms With A Recovery Crime Rates For Firearms
  description: Crime Rates For Firearms
  version: v1
host: data.atf.gov
basePath: /resource/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  time-to-crime-rates-for-firearms-with-a-recovery.json:
    get:
      summary: Crime Rates For Firearms
      description: Crime Rates For Firearms
      operationId: ""
      x-api-path-slug: timetocrimeratesforfirearmswitharecovery-json-get
      parameters:
      - in: query
        name: average_time_to_crime
      - in: query
        name: state
      - in: query
        name: under_3_months
      - in: query
        name: year
      - in: query
        name: _1_year_to_under_3_years
      - in: query
        name: _2_years_to_under_3_years
      - in: query
        name: _3_months_to_under_7_months
      - in: query
        name: _3_years_and_over
      - in: query
        name: _7_months_to_under_1_year
      responses:
        200:
          description: OK
      tags:
      - ""
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