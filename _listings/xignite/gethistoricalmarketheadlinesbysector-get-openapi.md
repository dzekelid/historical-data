---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global News Historical Market Headlines By Sector
  description: Returns all market headlines that were published in a specified time
    frame for a specified sector.
  version: 1.0.0
host: globalnews.xignite.com
basePath: xGlobalNews.xml/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  GetHistoricalMarketHeadlines/:
    get:
      summary: Historical Market Headlines
      description: Returns all market headlines that were published in a specified
        time frame.
      operationId: ""
      x-api-path-slug: gethistoricalmarketheadlines-get
      parameters:
      - in: query
        name: EndDate
        description: The end date range
      - in: query
        name: startDate
        description: The start date range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - ""
  GetHistoricalMarketHeadlinesBySector/:
    get:
      summary: Historical Market Headlines By Sector
      description: Returns all market headlines that were published in a specified
        time frame for a specified sector.
      operationId: ""
      x-api-path-slug: gethistoricalmarketheadlinesbysector-get
      parameters:
      - in: query
        name: EndDate
        description: The end date range
      - in: query
        name: Sector
        description: The business sector to search within
      - in: query
        name: StartDate
        description: The start date range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
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