{
  "info": {
    "name": "Fitbit Get User Collection Path Apisubscriptions.json",
    "_postman_id": "c71ffcd7-5b00-4002-9ff8-cc4d04f398d3",
    "description": "Get a list of user's subscriptions for your application in the format requested.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "167c619c-e9c2-4574-bbcd-0f477fa59d3a",
          "name": "getUserCollectionPathApisubscriptions.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-:collection-pathapiSubscriptions.json"
              ],
              "variable": [
                {
                  "id": "collection-path",
                  "value": "collection-path",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of user's subscriptions for your application in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c164585-66cc-491f-a7f9-7e441a402a07"
            }
          ]
        }
      ]
    }
  ]
}