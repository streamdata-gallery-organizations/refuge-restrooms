---
swagger: "2.0"
x-collection-name: Refuge Restrooms
x-complete: 0
info:
  title: Refuge Restrooms Get all restroom records ordered by date descending.
  description: ""
  version: v1
host: www.refugerestrooms.org
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/restrooms.json:
    get:
      summary: Get all restroom records ordered by date descending.
      description: ""
      operationId: v1.restrooms.json.get
      x-api-path-slug: v1restrooms-json-get
      parameters:
      - in: query
        name: ada
        description: Only return restrooms that are ADA accessible
      - in: query
        name: offset
        description: Pad a number of results
      - in: query
        name: page
        description: Page offset to fetch
      - in: query
        name: per_page
        description: Number of results to return per page
      - in: query
        name: unisex
        description: Only return restrooms that are unisex
      responses:
        200:
          description: OK
      tags:
      - ""
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