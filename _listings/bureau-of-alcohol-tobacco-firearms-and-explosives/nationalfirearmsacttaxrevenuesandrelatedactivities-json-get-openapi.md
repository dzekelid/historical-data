---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for National Firearms Act Tax Revenues And Related Activities National
    Firearms Act Tax Revenues And Related Activities
  description: National Firearms Act Tax Revenues And Related Activities
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
  national-firearms-act-tax-revenues-and-related-activities.json:
    get:
      summary: National Firearms Act Tax Revenues And Related Activities
      description: National Firearms Act Tax Revenues And Related Activities
      operationId: ""
      x-api-path-slug: nationalfirearmsacttaxrevenuesandrelatedactivities-json-get
      parameters:
      - in: query
        name: enforcement_support_certifications
      - in: query
        name: enforcement_support_records_checks
      - in: query
        name: fical_year
      - in: query
        name: occupational_tax_paid
      - in: query
        name: transfer_and_making_tax_paid
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