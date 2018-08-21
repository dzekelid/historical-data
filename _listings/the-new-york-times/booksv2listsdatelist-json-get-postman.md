{
  "info": {
    "name": "New York Times Best Seller List by Date",
    "_postman_id": "1cc4146a-e030-4d3a-ab63-f44b477c3e84",
    "description": "You can optionally request an overview for a specific published date using the published_date query parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "books",
      "item": [
        {
          "id": "23600201-d58e-47cc-a05b-55733af421fb",
          "name": "GET_lists-date-list-json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "books/v2/lists/:date/:list.json"
              ],
              "query": [
                {
                  "key": "api-key",
                  "value": "api-key",
                  "disabled": false
                },
                {
                  "key": "bestsellers-date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "isbn",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "list-name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "published-date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "rank",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "rank-last-week",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort-order",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "weeks-on-list",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "date",
                  "value": "date",
                  "type": "string"
                },
                {
                  "id": "list",
                  "value": "list",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can optionally request an overview for a specific published date using the published_date query parameter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6746551d-27ae-4c32-af42-81d51c57c305"
            }
          ]
        }
      ]
    }
  ]
}