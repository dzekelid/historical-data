---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Top Recovery Cities For Firearms With A Recovery Top Recovery Cities
    For Firearms
  description: Top Recovery Cities For Firearms
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
  top-recovery-cities-for-firearms-with-a-recovery.json:
    get:
      summary: Top Recovery Cities For Firearms
      description: Top Recovery Cities For Firearms
      operationId: ""
      x-api-path-slug: toprecoverycitiesforfirearmswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: city
      - in: query
        name: notes_if_any
      - in: query
        name: state
      - in: query
        name: traces
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