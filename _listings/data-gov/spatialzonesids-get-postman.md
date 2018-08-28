{
  "info": {
    "name": "Data.gov API Get Spatial Zones S",
    "_postman_id": "3450a20c-c9bd-464d-9437-d988a202e908",
    "description": "Fetch a zone list as GeoJSON",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "spatial",
      "item": [
        {
          "id": "536eae60-19a2-4769-a70e-6c1c63c471d0",
          "name": "getSpatialZonesS",
          "request": {
            "url": {
              "protocol": "http",
              "host": "catalog.data.gov",
              "path": [
                "api",
                "3",
                "spatial/zones/:ids"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch a zone list as GeoJSON"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71dd1eef-a93a-4c4b-a967-48a063b4176c"
            }
          ]
        }
      ]
    }
  ]
}