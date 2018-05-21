{
  "info": {
    "name": "Fitbit Get Activities .json",
    "_postman_id": "d67a4a91-4f94-4977-bc86-b0be1500343c",
    "description": "Get the details of a specific activity in Fitbit activities database in the format requested. If activity has levels, also get list of activity level details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "d3823180-8b98-45d9-a342-a60793186380",
          "name": "getActivities.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "activities/:id.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the details of a specific activity in Fitbit activities database in the format requested. If activity has levels, also get list of activity level details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6094a1cc-51fb-4177-94a3-5b0c2672d9cc"
            }
          ]
        }
      ]
    }
  ]
}