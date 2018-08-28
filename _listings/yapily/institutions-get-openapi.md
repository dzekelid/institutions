---
swagger: "2.0"
x-collection-name: Yapily
x-complete: 0
info:
  title: Yapily Retrieves the list of institutions available in Yapily
  description: Retrieves the list of institutions available in yapily.
  version: 1.0.0
host: api.yapily.com:443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /institutions:
    get:
      summary: Retrieves the list of institutions available in Yapily
      description: Retrieves the list of institutions available in yapily.
      operationId: getInstitutionsUsingGET
      x-api-path-slug: institutions-get
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - List
      - Institutions
      - Available
      - In
      - Yapily
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