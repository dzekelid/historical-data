{
  "info": {
    "name": "BBC Nitro Discover details of on-demand availability for programmes and their versions",
    "_postman_id": "9a274378-78c2-4f7a-ba77-bb27829ec948",
    "description": "Discover details of on-demand availability for programmes and their versions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "a77ae4bd-6307-48be-9c65-29a15bc4b319",
          "name": "getAPI",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get API definition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4b772a6-fdf3-4e38-a474-241cc3d3ed43"
            }
          ]
        }
      ]
    },
    {
      "name": "Availabilities",
      "item": [
        {
          "id": "b376ae76-79d0-496a-bd46-c58265765734",
          "name": "listAvailability",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/availabilities?availability=%7B%7D&debug=%7B%7D&descendants_of=%7B%7D&media_set=%7B%7D&page=%7B%7D&page_size=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&territory=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Discover details of on-demand availability for programmes and their versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f2c153a-a5a1-49f8-8f56-f641d75c87a3"
            }
          ]
        }
      ]
    }
  ]
}