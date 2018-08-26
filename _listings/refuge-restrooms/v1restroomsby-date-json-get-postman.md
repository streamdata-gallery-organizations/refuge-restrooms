{
  "info": {
    "name": "Refuge Restrooms Search for restroom records updated or created on or after a given date",
    "_postman_id": "90068c48-cd2f-4477-873a-0a91a955a4f7",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "5c45f197-afe4-4b6f-9583-7efc003fd1a3",
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
          "id": "9497f21e-6b61-45c1-89e9-d221dc65f7d6"
        }
      ]
    },
    {
      "id": "5e7b96b1-b6b4-4f11-be44-b542ab4c52c0",
      "name": "v1.restrooms.by_date.json.get",
      "request": {
        "url": "http://www.refugerestrooms.org/api/v1/restrooms/by_date.json?ada=%7B%7D&day=%7B%7D&month=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&unisex=%7B%7D&updated=%7B%7D&year=%7B%7D",
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
        "description": "Search for restroom records updated or created on or after a given date"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "dfa2e717-748f-4d50-bb0b-3d2815c61b1c"
        }
      ]
    }
  ]
}