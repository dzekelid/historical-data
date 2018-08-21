---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Pistols - Firearms Manufacturing Report Pistol Manufacturing Report
  description: Pistol Manufacturing Report
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
  pistols-firearms-manufacturing-report.json:
    get:
      summary: Pistol Manufacturing Report
      description: Pistol Manufacturing Report
      operationId: ""
      x-api-path-slug: pistolsfirearmsmanufacturingreport-json-get
      parameters:
      - in: query
        name: license_name
      - in: query
        name: premise_city
      - in: query
        name: premise_location
      - in: query
        name: premise_state
      - in: query
        name: premise_street
      - in: query
        name: pstl_22_sum
      - in: query
        name: pstl_25_sum
      - in: query
        name: pstl_32_sum
      - in: query
        name: pstl_380_sum
      - in: query
        name: pstl_50_sum
      - in: query
        name: pstl_totl_sum
      - in: query
        name: rds_key
      - in: query
        name: year
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