{
  "info": {
    "name": "BBC Nitro Start here for programmes metadata: Brands, Series, Episodes and Clips",
    "_postman_id": "b3e39702-2cee-4b01-a055-4bd731e27b85",
    "description": "Fetch metadata about Programmes (brands, series, episodes, clips). By applying different filter restrictions this feed can be used in many ways, for example to retrieve all series belonging to a brand, all the episodes and/or clips for a specific series, or any TLEO objects for a masterbrand. Other filters permit restricting to specific formats and/or genres, and you can request specific versions (for example Signed or Audio-Described). Parameters may be combined in any way suitable for your application.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Programme",
      "item": [
        {
          "id": "35da5075-f22c-4c2f-ae0d-0a345866fb97",
          "name": "listProgrammeDetails",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/programme_details?page=%7B%7D&page_size=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exposes programme information for a single pid"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0cbe61e-6322-4b48-9dac-24cda3277323"
            }
          ]
        }
      ]
    },
    {
      "name": "Programmes",
      "item": [
        {
          "id": "f5536753-94e8-424c-8595-de3782fbb2a0",
          "name": "listProgrammes",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/programmes?audio_described=%7B%7D&availability=%7B%7D&availability_entity_type=%7B%7D&availability_from=%7B%7D&availability_type=%7B%7D&children_of=%7B%7D&descendants_of=%7B%7D&duration=%7B%7D&embargoed=%7B%7D&entity_type=%7B%7D&format=%7B%7D&genre=%7B%7D&group=%7B%7D&initial_letter=%7B%7D&initial_letter_end=%7B%7D&initial_letter_start=%7B%7D&initial_letter_strict=%7B%7D&item=%7B%7D&master_brand=%7B%7D&media_set=%7B%7D&media_type=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&payment_type=%7B%7D&people=%7B%7D&pid=%7B%7D&promoted_for=%7B%7D&q=%7B%7D&signed=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&tag_name=%7B%7D&tag_scheme=%7B%7D&tleo=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch metadata about Programmes (brands, series, episodes, clips). By applying different filter restrictions this feed can be used in many ways, for example to retrieve all series belonging to a brand, all the episodes and/or clips for a specific series, or any TLEO objects for a masterbrand. Other filters permit restricting to specific formats and/or genres, and you can request specific versions (for example Signed or Audio-Described). Parameters may be combined in any way suitable for your application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53bf9e20-84c6-417c-ac09-29bf49fef57f"
            }
          ]
        }
      ]
    }
  ]
}