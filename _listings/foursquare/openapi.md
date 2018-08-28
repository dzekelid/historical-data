swagger: "2.0"
x-collection-name: Foursquare
x-complete: 1
info:
  title: Foursquare
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /venues/timeseries:
    get:
      summary: Get Venues Timeseries
      description: /venues/suggestcompletion
      operationId: venuessuggestcompletion
      x-api-path-slug: venuestimeseries-get
      parameters:
      - in: query
        name: endAt
        description: The end of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: startAt
        description: The start of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: venueId
        description: A comma-separated list of venue ids to retrieve series data for
      responses:
        200:
          description: OK
      tags:
      - Venues
      - Timeseries
  /venues/{VENUE_ID}/stats:
    get:
      summary: Get Venues Stats
      description: /venues/{VENUE_ID}/similar
      operationId: venuesvenue-idsimilar
      x-api-path-slug: venuesvenue-idstats-get
      parameters:
      - in: query
        name: endAt
        description: The end of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: startAt
        description: The start of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: VENUE_ID
        description: The venue id to retrieve stats for
      - in: path
        name: VENUE_ID
      responses:
        200:
          description: OK
      tags:
      - Venues
      - Stats