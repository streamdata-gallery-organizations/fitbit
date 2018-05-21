{
  "info": {
    "name": "Fitbit Get User Activities Goals Daily.json",
    "_postman_id": "ff367227-c3cb-4fc2-a54e-5742b22e19dc",
    "description": "Get a user's current daily activity goals in the format requested using units in the unit system which corresponds to the Accept-Language header provided.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "b806c00d-7c69-4d8c-a21b-20288d24d704",
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
              "id": "3efaa303-6f85-4990-8e0e-ebde7a544c82"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "202b30de-74bd-4de0-aad2-df46db6fca20",
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
              "id": "4e27ead4-a0f5-47a9-abf1-2fd08640e6a5"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "1b5f5f6b-5421-4bb8-8cd1-d6a224aa8c53",
          "name": "getUserActivitiesGoalsWeekly.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities/goals/weekly.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a user's current weekly activity goals in the format requested using units in the unit system which corresponds to the Accept-Language header provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d0eaaff-b966-43ea-81d7-1b2f9bab6ce1"
            }
          ]
        },
        {
          "id": "d3c8b10e-102f-45b0-ab2d-68f49e5d9781",
          "name": "getUserActivitiesGoalsDaily.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities/goals/daily.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a user's current daily activity goals in the format requested using units in the unit system which corresponds to the Accept-Language header provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5a05bc2-8a75-4a84-8fce-7109b9a5dcaf"
            }
          ]
        }
      ]
    }
  ]
}