{
  "info": {
    "name": "Stripe Get Balance History",
    "_postman_id": "c7a07099-d1b5-4884-b8d3-1087fa5affc6",
    "description": "Returns a list of transactions that have contributed to the Stripe account balance (e.g., charges, transfers, and so forth). The transactions are returned in sorted order, with the most recent transactions appearing first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "balance",
      "item": [
        {
          "id": "d703cff0-857d-4615-9ac7-9ae09114f3ba",
          "name": "getBalanceHistory",
          "request": {
            "url": "http://api.stripe.com/v1/balance/history?available_on=%7B%7D&created=%7B%7D&currency=%7B%7D&ending_before=%7B%7D&expand=%7B%7D&limit=%7B%7D&payout=%7B%7D&source=%7B%7D&starting_after=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of transactions that have contributed to the Stripe account balance (e"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4d90bb1-b885-41b6-9de2-c837c5d6bac0"
            }
          ]
        }
      ]
    }
  ]
}