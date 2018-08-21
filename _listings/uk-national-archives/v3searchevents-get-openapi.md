---
swagger: "2.0"
x-collection-name: UK National Archives
x-complete: 0
info:
  title: Getty Images Search API Get Search Events
  description: Search for events.
  version: "3.0"
host: api.gettyimages.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/search/events:
    get:
      summary: Get Search Events
      description: Search for events.
      operationId: getV3SearchEvents
      x-api-path-slug: v3searchevents-get
      parameters:
      - in: header
        name: Accept-Language
        description: Specifies the language of result values
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: query
        name: date_from
        description: Filters to events that start on or after this date
      - in: query
        name: date_to
        description: Filters to events that start on or before this date
      - in: query
        name: editorial_segment
        description: Filters to events with a matching editorial segment
      - in: query
        name: fields
        description: Specifies fields to return
      - in: query
        name: page
        description: Request results starting at a page number (default is 1)
      - in: query
        name: page_size
        description: Request number of images to return in each page
      - in: query
        name: phrase
        description: Filters to events related to this phrase
      responses:
        200:
          description: OK
      tags:
      - Search
      - Events
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