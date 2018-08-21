---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Top Categories Reported On Firearm Traces with a Recovery Top Categories
    Reported On Firearm Traces
  description: Top Categories Reported On Firearm Traces
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
  top-categories-reported-on-firearm-traces-with-a-recovery.json:
    get:
      summary: Top Categories Reported On Firearm Traces
      description: Top Categories Reported On Firearm Traces
      operationId: ""
      x-api-path-slug: topcategoriesreportedonfirearmtraceswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: categories
      - in: query
        name: count
      - in: query
        name: notes
      - in: query
        name: state
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