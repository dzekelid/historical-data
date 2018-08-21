{
  "info": {
    "name": "BBC Nitro Information about the linear services used for broadcast transmissions",
    "_postman_id": "46e12680-0b9b-46b9-b28b-c3101eb0ae80",
    "description": "The services feed exposes the linear broadcast \"services\" from PIPs. These are the actual services which broadcast programmes (eg bbc_one_oxford is the service for BBC One in Oxford).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Services",
      "item": [
        {
          "id": "7fc4c6ad-2f7b-42c3-b786-2476d8de7b0a",
          "name": "listServices",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/services?end_from=%7B%7D&end_to=%7B%7D&mid=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&q=%7B%7D&service_type=%7B%7D&sid=%7B%7D&start_from=%7B%7D&start_to=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The services feed exposes the linear broadcast \"services\" from PIPs. These are the actual services which broadcast programmes (eg bbc_one_oxford is the service for BBC One in Oxford)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c83a1b23-0fdc-484b-ad43-3bfff3e3fdff"
            }
          ]
        }
      ]
    }
  ]
}