---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Firearms Imports Firearms Imports
  description: Firearms Imports
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
  firearms-imports.json:
    get:
      summary: Firearms Imports
      description: Firearms Imports
      operationId: ""
      x-api-path-slug: firearmsimports-json-get
      parameters:
      - in: query
        name: calendar_year
      - in: query
        name: handguns
      - in: query
        name: rifles
      - in: query
        name: shotguns
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