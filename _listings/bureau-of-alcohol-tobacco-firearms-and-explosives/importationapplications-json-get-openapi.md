---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Importation Applications Importation Applications
  description: Importation Applications
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
  importation-applications.json:
    get:
      summary: Importation Applications
      description: Importation Applications
      operationId: ""
      x-api-path-slug: importationapplications-json-get
      parameters:
      - in: query
        name: fiscal_year
      - in: query
        name: licensed_importer
      - in: query
        name: military
      - in: query
        name: other
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