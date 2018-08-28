---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 0
info:
  title: Data.gov API Get Spatial Coverage Level
  description: List each zone for a given level with their datasets count
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /spatial/coverage/{level}:
    get:
      summary: Get Spatial Coverage Level
      description: List each zone for a given level with their datasets count
      operationId: getSpatialCoverageLevel
      x-api-path-slug: spatialcoveragelevel-get
      parameters:
      - in: path
        name: level
      responses:
        200:
          description: OK
      tags:
      - Spatial
      - Coverage
      - Level
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