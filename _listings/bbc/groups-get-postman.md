{
  "info": {
    "name": "BBC Nitro Find metadata for curated groups: seasons, collections, galleries or franchises",
    "_postman_id": "d641c387-9281-4f75-888e-cb7fbcc15bbe",
    "description": "Long-lived curated collections of programmes and more, including Collections, Seasons, Franchises and Galleries",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Groups",
      "item": [
        {
          "id": "4049af13-00e5-4942-bafb-40829a9af670",
          "name": "listGroups",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/groups?embargoed=%7B%7D&for_descendants_of=%7B%7D&for_programme=%7B%7D&group=%7B%7D&group_type=%7B%7D&member=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Long-lived curated collections of programmes and more, including Collections, Seasons, Franchises and Galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e37f2c12-6e50-4a90-885f-23fd5263c1d5"
            }
          ]
        }
      ]
    }
  ]
}