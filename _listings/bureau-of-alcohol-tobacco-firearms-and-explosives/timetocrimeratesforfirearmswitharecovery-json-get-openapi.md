---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API Time To Crime Rates For Firearms With A Recovery Crime Rates For Firearms
  description: Crime Rates For Firearms
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
  actions-on-federal-firearms-license-applications.json:
    get:
      summary: Actions On Federal Firearms License Applications
      description: Actions On Federal Firearms License Applications
      operationId: getActionsOnFederalFirearmsLicenseApplications.json
      x-api-path-slug: actionsonfederalfirearmslicenseapplications-json-get
      parameters:
      - in: query
        name: applications_abandoned
      - in: query
        name: applications_denied
      - in: query
        name: applications_withdrawn
      - in: query
        name: fiscal_year
      - in: query
        name: original_applications_processed
      responses:
        200:
          description: OK
      tags:
      - Actions
      - "On"
      - Federal
      - Firearms
      - License
      - Applications
      - Json
  firearms-imports.json:
    get:
      summary: Firearms Imports
      description: Firearms Imports
      operationId: ""
      x-api-path-slug: firearmsimports-json-get
      parameters:
      - in: query
        name: calendar_year
      - in: query
        name: handguns
      - in: query
        name: rifles
      - in: query
        name: shotguns
      responses:
        200:
          description: OK
      tags:
      - ""
  firearms-manufacturers-exports.json:
    get:
      summary: Firearms Manufacturers Exports
      description: Firearms Manufacturers Exports
      operationId: ""
      x-api-path-slug: firearmsmanufacturersexports-json-get
      parameters:
      - in: query
        name: calendar_year
      - in: query
        name: misc_firearms
      - in: query
        name: pistols
      - in: query
        name: revolvers
      - in: query
        name: rifles
      - in: query
        name: shotguns
      - in: query
        name: total_firearms
      responses:
        200:
          description: OK
      tags:
      - ""
  firearms-types-with-a-recovery.json:
    get:
      summary: Firearms Types
      description: Firearms Types
      operationId: ""
      x-api-path-slug: firearmstypeswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: notes_if_any
      - in: query
        name: number_of_recoveries
      - in: query
        name: state
      - in: query
        name: types
      - in: query
        name: year
      responses:
        200:
          description: OK
      tags:
      - ""
  importation-applications.json:
    get:
      summary: Importation Applications
      description: Importation Applications
      operationId: ""
      x-api-path-slug: importationapplications-json-get
      parameters:
      - in: query
        name: fiscal_year
      - in: query
        name: licensed_importer
      - in: query
        name: military
      - in: query
        name: other
      responses:
        200:
          description: OK
      tags:
      - ""
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
  pistols-firearms-manufacturing-report.json:
    get:
      summary: Pistol Manufacturing Report
      description: Pistol Manufacturing Report
      operationId: ""
      x-api-path-slug: pistolsfirearmsmanufacturingreport-json-get
      parameters:
      - in: query
        name: license_name
      - in: query
        name: premise_city
      - in: query
        name: premise_location
      - in: query
        name: premise_state
      - in: query
        name: premise_street
      - in: query
        name: pstl_22_sum
      - in: query
        name: pstl_25_sum
      - in: query
        name: pstl_32_sum
      - in: query
        name: pstl_380_sum
      - in: query
        name: pstl_50_sum
      - in: query
        name: pstl_totl_sum
      - in: query
        name: rds_key
      - in: query
        name: year
      responses:
        200:
          description: OK
      tags:
      - ""
  top-categories-reported-on-firearm-traces-with-a-recovery.json:
    get:
      summary: Top Categories Reported On Firearm Traces
      description: Top Categories Reported On Firearm Traces
      operationId: ""
      x-api-path-slug: topcategoriesreportedonfirearmtraceswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: categories
      - in: query
        name: count
      - in: query
        name: notes
      - in: query
        name: state
      - in: query
        name: year
      responses:
        200:
          description: OK
      tags:
      - ""
  top-recovery-cities-for-firearms-with-a-recovery.json:
    get:
      summary: Top Recovery Cities For Firearms
      description: Top Recovery Cities For Firearms
      operationId: ""
      x-api-path-slug: toprecoverycitiesforfirearmswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: city
      - in: query
        name: notes_if_any
      - in: query
        name: state
      - in: query
        name: traces
      - in: query
        name: year
      responses:
        200:
          description: OK
      tags:
      - ""
  time-to-crime-rates-for-firearms-with-a-recovery.json:
    get:
      summary: Crime Rates For Firearms
      description: Crime Rates For Firearms
      operationId: ""
      x-api-path-slug: timetocrimeratesforfirearmswitharecovery-json-get
      parameters:
      - in: query
        name: average_time_to_crime
      - in: query
        name: state
      - in: query
        name: under_3_months
      - in: query
        name: year
      - in: query
        name: _1_year_to_under_3_years
      - in: query
        name: _2_years_to_under_3_years
      - in: query
        name: _3_months_to_under_7_months
      - in: query
        name: _3_years_and_over
      - in: query
        name: _7_months_to_under_1_year
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