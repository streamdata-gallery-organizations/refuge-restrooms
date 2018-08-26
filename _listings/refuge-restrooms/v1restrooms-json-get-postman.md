{
  "info": {
    "name": "Refuge Restrooms Get all restroom records ordered by date descending.",
    "_postman_id": "376b2fef-2424-40c0-91fa-991e09437977",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "5262f6e2-2cff-4688-bb75-f25cab45ad27",
      "name": "v1.restrooms.json.get",
      "request": {
        "url": "http://www.refugerestrooms.org/api/v1/restrooms.json?ada=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&unisex=%7B%7D",
        "method": "GET",
        "header": [
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Get all restroom records ordered by date descending."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "62232817-9d75-4cda-8915-e37c1799b05f"
        }
      ]
    }
  ]
}