---
swagger: "2.0"
x-collection-name: Intrinio
x-complete: 0
info:
  title: Intrinio API Institutional Owners by Security
  description: https://api.intrinio.com/securities/institutional_ownership?identifier={symbol}
  version: 1.0.0
host: api.intrinio.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /securities/institutional_ownership:
    get:
      summary: Institutional Owners by Security
      description: https://api.intrinio.com/securities/institutional_ownership?identifier={symbol}
      operationId: institutional-owners-by-security
      x-api-path-slug: securitiesinstitutional-ownership-get
      parameters:
      - in: query
        name: identifier
        description: 'the stock market ticker symbol associated with the companies
          common stock securities or the Central Index Key issued by the SEC, which
          is the unique identifier all company filings are issued under:'
        type: string
      - in: query
        name: page_number
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Securities
      - Institutional Ownership
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