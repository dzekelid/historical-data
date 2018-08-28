---
name: BBC
x-slug: bbc
description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
  educates and entertains - wherever you are, whatever your age.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
x-kinRank: "7"
x-alexaRank: "93"
tags: Historical Data
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/apis.md
specificationVersion: "0.14"
apis:
- name: BBC Nitro - Discover details of on-demand availability for programmes and
    their versions
  x-api-slug: availabilities-get
  description: Discover details of on-demand availability for programmes and their
    versions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/availabilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/availabilities-get-openapi.md
- name: BBC Nitro - Build schedules and find metadata for TV and radio broadcasts
  x-api-slug: broadcasts-get
  description: Fetch metadata about linear Broadcasts and Services, allowing the generation
    of Television and Radio schedules and other datasets for broadcast items. Use
    /schedules instead of this feed as it is more efficient. Broadcasts will be deprecated
    in the future.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/broadcasts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/broadcasts-get-openapi.md
- name: 'BBC Nitro - Find metadata for curated groups: seasons, collections, galleries
    or franchises'
  x-api-slug: groups-get
  description: Long-lived curated collections of programmes and more, including Collections,
    Seasons, Franchises and Galleries
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/groups-get-openapi.md
- name: 'BBC Nitro - Start here for programmes metadata: Brands, Series, Episodes
    and Clips'
  x-api-slug: programmes-get
  description: Fetch metadata about Programmes (brands, series, episodes, clips).
    By applying different filter restrictions this feed can be used in many ways,
    for example to retrieve all series belonging to a brand, all the episodes and/or
    clips for a specific series, or any TLEO objects for a masterbrand. Other filters
    permit restricting to specific formats and/or genres, and you can request specific
    versions (for example Signed or Audio-Described). Parameters may be combined in
    any way suitable for your application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/programmes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/programmes-get-openapi.md
- name: BBC Nitro - Build schedules and find metadata for TV and radio broadcasts
    and webcasts
  x-api-slug: schedules-get
  description: 'Dates, Times, Schedules: when and where are programmes being shown?'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/schedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/schedules-get-openapi.md
- name: BBC Nitro - Information about the linear services used for broadcast transmissions
  x-api-slug: services-get
  description: The services feed exposes the linear broadcast "services" from PIPs.
    These are the actual services which broadcast programmes (eg bbc_one_oxford is
    the service for BBC One in Oxford).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/services-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/services-get-openapi.md
- name: 'BBC Nitro - Metadata on editorial programme versions: original, signed, audio-described,
    etc'
  x-api-slug: versions-get
  description: 'The versions feed exposes editorial "Versions" of programmes. These
    are concepts used to capture different presentations of an overall programme:
    for example, versions of a programme may include one with sign language, one with
    audio description, one edited for content and more. Versions are also important
    to understand for broadcasts: a linear broadcast or an ondemand is always of a
    specific version, not merely of a programme.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/versions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/historical-data/master/_listings/bbc/versions-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://barclays.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bbc.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bbc-news
- type: x-email
  url: dataprotection@bbc.com
- type: x-email
  url: bbcworldwidelearning@bbc.com
- type: x-twitter
  url: https://twitter.com/BBCNews
- type: x-website
  url: http://www.bbc.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---