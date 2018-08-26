{
  "info": {
    "name": "Refuge Restrooms Search by location.",
    "_postman_id": "bedfecfc-4f50-4be7-a407-583aac277a9f",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "8f647b06-4885-4f48-8709-643b3e24702e",
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
          "id": "c3c0b85b-fde0-4d7f-9cec-b6ebb90d032a"
        }
      ]
    },
    {
      "id": "6fedb0ce-b439-49a5-86b0-b203b967b37c",
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
          "id": "63050e57-8fde-4ccf-821c-c690ab57773c"
        }
      ]
    },
    {
      "id": "9c97beb5-301a-45ec-8e4e-75481815b100",
      "name": "v1.restrooms.by_location.json.get",
      "request": {
        "url": "http://www.refugerestrooms.org/api/v1/restrooms/by_location.json?ada=%7B%7D&lat=%7B%7D&lng=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&unisex=%7B%7D",
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
        "description": "Search by location."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "5597785b-6113-44db-b169-2633f2ff7136"
        }
      ]
    }
  ]
}