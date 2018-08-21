{
  "info": {
    "name": "BBC Nitro Build schedules and find metadata for TV and radio broadcasts and webcasts",
    "_postman_id": "b316f129-87d8-4535-9ac0-6778c9681a73",
    "description": "Dates, Times, Schedules: when and where are programmes being shown?",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Schedules",
      "item": [
        {
          "id": "9e29bd47-d104-4dbd-ae03-e70acee9099f",
          "name": "listSchedules",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/schedules?authority=%7B%7D&descendants_of=%7B%7D&end_from=%7B%7D&end_to=%7B%7D&format=%7B%7D&genre=%7B%7D&group=%7B%7D&id=%7B%7D&id_type=%7B%7D&item=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&people=%7B%7D&pid=%7B%7D&q=%7B%7D&repeat=%7B%7D&schedule_day=%7B%7D&schedule_day_from=%7B%7D&schedule_day_to=%7B%7D&service_master_brand=%7B%7D&sid=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&start_from=%7B%7D&start_to=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Dates, Times, Schedules: when and where are programmes being shown?"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8974bf8d-afa7-4358-841a-c2834613aced"
            }
          ]
        }
      ]
    }
  ]
}