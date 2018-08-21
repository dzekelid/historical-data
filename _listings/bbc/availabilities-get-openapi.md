---
swagger: "2.0"
x-collection-name: BBC
x-complete: 0
info:
  title: BBC Nitro Discover details of on-demand availability for programmes and their
    versions
  description: Discover details of on-demand availability for programmes and their
    versions
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /availabilities:
    get:
      summary: Discover details of on-demand availability for programmes and their
        versions
      description: Discover details of on-demand availability for programmes and their
        versions
      operationId: listAvailability
      x-api-path-slug: availabilities-get
      parameters:
      - in: query
        name: availability
        description: filter for subset of availabilities
      - in: query
        name: debug
        description: Turn on debug information (undocumented)
      - in: query
        name: descendants_of
        description: filter for subset of availabilities that have PID as ancestor
      - in: query
        name: media_set
        description: filter for subset of availabilities with media set
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: sort
        description: 'Sorts:* scheduled_start: sort chronologically by scheduled start
          time/date, ascending'
      - in: query
        name: sort_direction
        description: Sort direction
      - in: query
        name: territory
        description: filter for availabilities in given territory
      responses:
        200:
          description: OK
      tags:
      - Availabilities
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