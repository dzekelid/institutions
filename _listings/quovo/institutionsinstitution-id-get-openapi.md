---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 0
info:
  title: Quovo Get a single institution
  description: Provides information on a single Quovo-supported institution.
  version: 1.0.0
host: example.com
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
      summary: Get all institutions
      description: Provides information on all of Quovo's supported institutions.
      operationId: InstitutionsGet
      x-api-path-slug: institutions-get
      responses:
        200:
          description: OK
      tags:
      - Institutions
  /users/{user_id}/institution_requests:
    post:
      summary: Request a new institution
      description: Requests a new financial institution for Quovo to retrieve data
        from.
      operationId: UsersInstitutionRequestsByUserIdPost
      x-api-path-slug: usersuser-idinstitution-requests-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Request
      - New
      - Institution
  /institutions/{institution_id}:
    get:
      summary: Get a single institution
      description: Provides information on a single Quovo-supported institution.
      operationId: InstitutionsByInstitutionIdGet
      x-api-path-slug: institutionsinstitution-id-get
      parameters:
      - in: path
        name: institution_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Institution
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