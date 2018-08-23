{
  "info": {
    "name": "Europeana search for records",
    "_postman_id": "eea7b457-6bb6-4052-9a24-45f11efeefea",
    "description": "Search for records.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Dataset",
      "item": [
        {
          "id": "70d4a1f6-d5c6-4cf2-bb27-05bb98eb1545",
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
              "id": "203bfad0-446b-487d-a452-d62a41974d73"
            }
          ]
        }
      ]
    },
    {
      "name": "Datasets",
      "item": [
        {
          "id": "ab1218f2-c49a-429e-9936-792c9e6148ee",
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
              "id": "dda7904e-9c97-4b6a-9ec9-c8706f4ea6d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "c9980df7-71b0-4bba-9ddb-ebf62e18af23",
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
              "id": "819757d3-e91c-475c-ae0c-8e31a21ebb1e"
            }
          ]
        },
        {
          "id": "70973f92-02ac-45e2-b65b-c4e64b61cae8",
          "name": "searchRecords",
          "request": {
            "url": "http://www.europeana.eu/v2/search.json?callback=%7B%7D&colourpalette=%7B%7D&cursor=%7B%7D&facet=%7B%7D&landingpage=%7B%7D&media=%7B%7D&profile=%7B%7D&qf=%7B%7D&query=%7B%7D&reusability=%7B%7D&rows=%7B%7D&sort=%7B%7D&start=%7B%7D&text_fulltext=%7B%7D&thumbnail=%7B%7D&wskey=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for records."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14e0fcf7-832d-4c67-8cdd-9cb97b1bef42"
            }
          ]
        }
      ]
    },
    {
      "name": "Provider",
      "item": [
        {
          "id": "4ff7d9b2-55d9-4c81-bdc5-c124453c7926",
          "name": "getProvider",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "provider/:id.json"
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
            "description": "Get information about a specific europeana provider."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a6a1f3e-beed-4a37-9a37-4ff1d598f7c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Providers",
      "item": [
        {
          "id": "35dc1417-0400-4573-a806-573ec31ddfd7",
          "name": "listProviderDatasets",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "provider/:id/datasets.json"
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
            "description": "Get the list of datasets provided by a specific provider."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c1de0a7-dba4-426d-919c-624175568f6a"
            }
          ]
        },
        {
          "id": "1be78fd3-2bc2-47b8-9370-fca68bcd0d23",
          "name": "listProviders",
          "request": {
            "url": "http://www.europeana.eu/v2/providers.json?callback=%7B%7D&countryCode=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&wskey=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the list of europeana data providers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f46efc4a-b9d5-4e85-90cc-05d8fecc4122"
            }
          ]
        }
      ]
    },
    {
      "name": "Collections",
      "item": [
        {
          "id": "3558e507-96e3-4373-a314-e91e443b54fc",
          "name": "getSingleRecordJson",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "record/:collectionId/:recordId.json"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "hierarchytimeout",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "profile",
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
                  "id": "collectionId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "recordId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a single record in json format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13e842b6-6645-4471-a338-b9aff0bd8471"
            }
          ]
        },
        {
          "id": "b44fb4af-5784-4574-baf7-56185ee400df",
          "name": "getSingleRecordJsonLD",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "record/:collectionId/:recordId.jsonld"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
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
                  "id": "collectionId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "recordId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single record in json ld format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a7d2e76-0bbb-4f04-9aaf-f389c078a99a"
            }
          ]
        },
        {
          "id": "268804ae-6e32-4af3-a560-6ec6f7afb72b",
          "name": "getSingleRecordRDF",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.europeana.eu",
              "path": [
                "v2",
                "record/:collectionId/:recordId.rdf"
              ],
              "query": [
                {
                  "key": "wskey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "collectionId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "recordId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single record in rdf format)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81d4a0c3-0987-4a78-8b2a-6008ac516234"
            }
          ]
        }
      ]
    }
  ]
}