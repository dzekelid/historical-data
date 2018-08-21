{
  "info": {
    "name": "Europeana basic search function following the OpenSearch specification",
    "_postman_id": "bfe146c1-b918-4e96-b127-c0e880ca33b4",
    "description": "Basic search function following the opensearch specification.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Dataset",
      "item": [
        {
          "id": "00065f15-d389-488f-8adf-503a1f40430a",
          "name": "getDataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "dataset/:id.json"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "wskey",
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
            "body": {
              "mode": "raw"
            },
            "description": "Get information about a specific dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "123f5808-0875-4dfb-875c-ce46136af220"
            }
          ]
        }
      ]
    },
    {
      "name": "Datasets",
      "item": [
        {
          "id": "93df16c5-10c4-4143-abb0-650eb9a312c7",
          "name": "listDatasets",
          "request": {
            "url": "http://www.europeana.eu/v2/datasets.json?callback=%7B%7D&countryCode=%7B%7D&edmDatasetName=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&status=%7B%7D&wskey=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the list of europeana datasets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d88debf4-eef7-456c-b8dd-d563df8a65a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "a076b9ee-ad7b-4f71-9c04-7eb0218a7514",
          "name": "openSearch",
          "request": {
            "url": "http://www.europeana.eu/v2/opensearch.rss?count=%7B%7D&searchTerms=%7B%7D&startIndex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Basic search function following the opensearch specification."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05b0938b-f3fe-4048-a363-ab6fd70b8eeb"
            }
          ]
        }
      ]
    }
  ]
}