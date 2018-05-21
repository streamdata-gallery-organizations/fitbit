{
  "info": {
    "name": "Fitbit Get Activities.json",
    "_postman_id": "e02bf045-f430-48f9-882a-69206c757357",
    "description": "Get a tree of all valid Fitbit public activities from the activities catalog as well as private custom activities the user created in the format requested. If activity has levels, also get a list of activity level details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "cc4d80fa-7181-4182-becd-6210490a6b75",
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
              "id": "54f775eb-050b-4cfc-ada8-f70aeae0109a"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "5808d93d-913e-405e-adc0-47a73bb72889",
          "name": "getActivities.json",
          "request": {
            "url": "http://api.fitbit.com/1/activities.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a tree of all valid Fitbit public activities from the activities catalog as well as private custom activities the user created in the format requested. If activity has levels, also get a list of activity level details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9feffee4-f56d-4e47-be37-213741b1664f"
            }
          ]
        }
      ]
    }
  ]
}