---
name: Europeana
x-slug: europeana
description: Explore 51,990,182 artworks, artefacts, books, videos and sounds from
  more than 3,500 museums, galleries, libraries and archives across Europe.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
x-kinRank: "9"
x-alexaRank: "68066"
tags: Historical Data
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/europeana/apis.md
specificationVersion: "0.14"
apis:
- name: Europeana - basic search function following the OpenSearch specification
  x-api-slug: opensearch-rss-get
  description: Basic search function following the opensearch specification.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2/
  tags: Museums, Art, History, Library, Museum, API LIfeyclessss, Stack Network, API
    Provider, Profiles, General Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/europeana/opensearch-rss-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/europeana/opensearch-rss-get-openapi.md
- name: Europeana - search for records
  x-api-slug: search-json-get
  description: Search for records.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2/
  tags: Museums, Art, History, Library, Museum, API LIfeyclessss, Stack Network, API
    Provider, Profiles, General Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/europeana/search-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/europeana/search-json-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://eu.vat.api.api.gallery.streamdata.io
- type: x-api-stack
  url: http://europeana.stack.network
- type: x-base
  url: http://www.europeana.eu/api/
- type: x-blog
  url: http://blog.europeana.eu/
- type: x-blog-rss
  url: http://blog.europeana.eu/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/europeana
- type: x-developer
  url: http://europeana.eu/portal/api-introduction.html
- type: x-github
  url: https://github.com/europeana
- type: x-twitter
  url: https://twitter.com/EuropeanaEU
- type: x-website
  url: http://europeana.eu/portal/
- type: x-website
  url: http://europeana.eu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---