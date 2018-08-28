{
  "info": {
    "name": "Data.gov API Get Spatial Zones Suggest",
    "_postman_id": "807ca932-dd0f-4717-bdbc-825cd0042aea",
    "description": "Suggest geospatial zones",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "spatial",
      "item": [
        {
          "id": "b0518f7d-0543-4baa-89b9-eb6356538e7c",
          "name": "getSpatialZonesSuggest",
          "request": {
            "url": "http://catalog.data.gov/api/3/spatial/zones/suggest?q=%7B%7D&size=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Suggest geospatial zones"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "115c6773-99aa-4f71-a4d8-330459d4e8c2"
            }
          ]
        }
      ]
    }
  ]
}