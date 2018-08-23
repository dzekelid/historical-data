---
swagger: "2.0"
x-collection-name: Europeana
x-complete: 1
info:
  title: Europeana
  description: this-swagger-api-console-provides-an-overview-of-an-interface-to-the-europeana-rest-api--you-can-build-and-test-anything-from-the-simplest-search-to-a-complex-query-using-facetlist-such-as-dates-geotags-and-permissions--for-more-help-and-information-head-to-our-comprehensive-a-hrefhttplabs-europeana-euapionline-documentationa-
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
  /search.json:
    get:
      summary: search for records
      description: Search for records.
      operationId: searchRecords
      x-api-path-slug: search-json-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: query
        name: colourpalette
        description: colourpalette
      - in: query
        name: cursor
        description: cursor
      - in: query
        name: facet
        description: facet
      - in: query
        name: landingpage
        description: landingpage
      - in: query
        name: media
        description: media
      - in: query
        name: profile
        description: profile
      - in: query
        name: qf
        description: qf
      - in: query
        name: query
        description: query
      - in: query
        name: reusability
        description: reusability
      - in: query
        name: rows
        description: rows
      - in: query
        name: sort
        description: sort
      - in: query
        name: start
        description: start
      - in: query
        name: text_fulltext
        description: text_fulltext
      - in: query
        name: thumbnail
        description: thumbnail
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Search
---