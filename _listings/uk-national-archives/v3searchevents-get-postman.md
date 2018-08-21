{
  "info": {
    "name": "Getty Images Search API Get Search Events",
    "_postman_id": "4fb7311f-8904-4fe6-ba5f-355dc08d15d2",
    "description": "Search for events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Events",
      "item": [
        {
          "id": "0e2744ca-73d6-40b8-938b-fa33b317f9b4",
          "name": "getV3Events",
          "request": {
            "url": "http://api.gettyimages.com/v3/events?fields=%7B%7D&ids=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get metadata for multiple events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3a7734f-ebcc-4cca-805f-7ba87c9d16f6"
            }
          ]
        },
        {
          "id": "acf88bfb-a622-4b24-9807-02c0d2df5197",
          "name": "getV3Events",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.gettyimages.com",
              "path": [
                "v3/events/:id"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get metadata for a single event."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd598fde-9cd8-4f2e-83cc-6828ee0a7eba"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "ef21e1fa-01b9-4488-9f4b-316d29bcf50f",
          "name": "getV3SearchEvents",
          "request": {
            "url": "http://api.gettyimages.com/v3/search/events?date_from=%7B%7D&date_to=%7B%7D&editorial_segment=%7B%7D&fields=%7B%7D&page=%7B%7D&page_size=%7B%7D&phrase=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61255ec3-ca17-4ef7-ba0b-254386296c24"
            }
          ]
        }
      ]
    }
  ]
}