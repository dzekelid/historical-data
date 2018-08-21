---
swagger: "2.0"
x-collection-name: Europeana
x-complete: 0
info:
  title: Europeana basic search function following the OpenSearch specification
  description: Basic search function following the opensearch specification.
  termsOfService: http://www.europeana.eu/portal/en/rights.html
  contact:
    name: http://labs.europeana.eu/api
  version: 1.0.0
host: www.europeana.eu
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /opensearch.rss:
    get:
      summary: basic search function following the OpenSearch specification
      description: Basic search function following the opensearch specification.
      operationId: openSearch
      x-api-path-slug: opensearch-rss-get
      parameters:
      - in: query
        name: count
        description: count
      - in: query
        name: searchTerms
        description: searchTerms
      - in: query
        name: startIndex
        description: startIndex
      responses:
        200:
          description: OK
      tags:
      - Search
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