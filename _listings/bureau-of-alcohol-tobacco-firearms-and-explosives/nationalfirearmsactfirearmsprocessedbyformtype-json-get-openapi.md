---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for National Firearms Act Firearms Processed By Form Type National Firearms
    Act Firearms Processed By Form Type
  description: National Firearms Act Firearms Processed By Form Type
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
  national-firearms-act-firearms-processed-by-form-type.json:
    get:
      summary: National Firearms Act Firearms Processed By Form Type
      description: National Firearms Act Firearms Processed By Form Type
      operationId: ""
      x-api-path-slug: nationalfirearmsactfirearmsprocessedbyformtype-json-get
      parameters:
      - in: query
        name: application_for_taxpaid_transfer_atf_form_4
      - in: query
        name: application_for_tax_exempt_transfer_3_atf_form_5
      - in: query
        name: application_for_tax_exempt_transfer_between_licensees_atf_form_3
      - in: query
        name: application_to_make_nfa_firearms_atf_form_1
      - in: query
        name: calendar_year
      - in: query
        name: exported_atf_form_9
      - in: query
        name: manufactured_and_imported_atf_form_2
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