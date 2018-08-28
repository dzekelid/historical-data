---
swagger: "2.0"
x-collection-name: Stripe
x-complete: 0
info:
  title: Stripe Get Balance History
  description: Returns a list of transactions that have contributed to the Stripe
    account balance (e.g., charges, transfers, and so forth). The transactions are
    returned in sorted order, with the most recent transactions appearing first.
  termsOfService: https://stripe.com/us/terms/
  contact:
    name: Stripe Dev Platform Team
    url: https://stripe.com
    email: dev-platform@stripe.com
  version: v1
host: api.stripe.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /balance/history:
    get:
      summary: Get Balance History
      description: Returns a list of transactions that have contributed to the Stripe
        account balance (e.g., charges, transfers, and so forth). The transactions
        are returned in sorted order, with the most recent transactions appearing
        first.
      operationId: getBalanceHistory
      x-api-path-slug: balancehistory-get
      parameters:
      - in: query
        name: available_on
      - in: query
        name: created
      - in: query
        name: currency
      - in: query
        name: ending_before
        description: A cursor for use in pagination
      - in: query
        name: expand
        description: Specifies which fields in the response should be expanded
      - in: query
        name: limit
        description: A limit on the number of objects to be returned
      - in: query
        name: payout
        description: For automatic Stripe payouts only, only returns transactions
          that were payed out on the specified payout ID
      - in: query
        name: source
        description: Only returns the original transaction
      - in: query
        name: starting_after
        description: A cursor for use in pagination
      - in: query
        name: type
        description: Only returns transactions of the given type
      responses:
        1:
          description: Photoset not found - The photoset id passed was not the id
            of avalid photoset owned by the calling user
        2:
          description: Photo not found - The photo id passed was not the id of a valid
            photo owned by the calling user
        95:
          description: SSL is required - SSL is required to access the Flickr API
        96:
          description: Invalid signature - The passed signature was invalid
        97:
          description: Missing signature - The call required signing but no signature
            was sent
        98:
          description: Login failed / Invalid auth token - The login details or auth
            token passed were invalid
        99:
          description: User not logged in / Insufficient permissions - The method
            requires user authentication but the user was not logged in, or the authenticated
            method call did not have the required permissions
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
      tags:
      - Balance
      - History
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---