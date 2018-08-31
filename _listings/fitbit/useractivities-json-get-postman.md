{
  "info": {
    "name": "Fitbit Get User Activities.json",
    "_postman_id": "0593c847-2004-421d-ac43-b34c6e79dc00",
    "description": "Get user's activity statistics in the format requested using units in the unit system which corresponds to the Accept-Language header provided. Response contains both lifetime statistics from the tracker device and total numbers including the manual activity log entries as seen on the Fitbit website dashboard.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "198df7f5-6fcd-4746-b531-28999bf5cd8b",
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
              "id": "28f7ed35-b1a4-4c49-a531-9c447246c526"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "027ca27a-af7c-4411-ac2d-03ce9d1e5e87",
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
              "id": "0a4c0cde-ce83-4fc1-a1e2-caa22611c188"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "154dbee1-2c56-47a3-906f-6c25e2c7345a",
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
              "id": "d6cc6ff1-ba46-4c63-be49-acdcc39391c1"
            }
          ]
        },
        {
          "id": "35d9e5ec-b5ef-4aca-b17e-88eb148526d2",
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
              "id": "e4a6bb07-a239-4dfe-afc4-7a74090ecbb9"
            }
          ]
        },
        {
          "id": "3c7850c1-2a20-463b-9a00-efd35b3531b0",
          "name": "postUserActivitiesLogFavorite.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/activities/log/favorite/:id.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the activity with the given id to user's list of favorite activities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54270a6d-c15d-45e3-a995-16118ef6bb4c"
            }
          ]
        },
        {
          "id": "112acffe-b145-4ea9-b9ab-4233169ca68a",
          "name": "deleteUserActivitiesLogFavorite.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/activities/log/favorite/:id.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the activity with the given id from user's list of favorite activities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d0e284b-36cb-4f13-bb8f-bcc54f2e3b6a"
            }
          ]
        },
        {
          "id": "32ab6a48-35a9-45a7-be92-6416a399b46b",
          "name": "getUserActivitiesFavorite.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities/favorite.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's favorite activities in the format requested. A user marks an activity as favorite on the user's Activities Tab. The activity ids in the list can be used to create a new activity log entry via the Log Activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e059e239-4d91-4592-ab9a-6d2d08ca8759"
            }
          ]
        },
        {
          "id": "a984bd8e-c0b3-4755-9197-30d5982db7ad",
          "name": "getUserActivitiesFrequent.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities/frequent.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's frequent activities in the format requested using units in the unit system which corresponds to the Accept-Language header provided. A frequent activity record contains the distance and duration values recorded the last time the activity was logged. The record retrieved can therefore be used to log the activity via the Log Activity with the same or adjusted values for distance and duration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "651f03d6-53a3-4f17-8c85-75b2340c71ad"
            }
          ]
        },
        {
          "id": "408cd7e2-40e2-44c8-8f17-6c4dbc7b1b15",
          "name": "getUserActivitiesRecent.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities/recent.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's recent activities in the format requested using units in the unit system which corresponds to the Accept-Language header provided. A recent activity record contains the distance and duration values recorded the last time the activity was logged. The record retrieved can therefore be used to log the activity via the Log Activity with the same or adjusted values for distance and duration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9314cea8-4071-49ec-a1bd-23e408ba3aed"
            }
          ]
        },
        {
          "id": "c04b7b5a-b00a-4495-911d-776d94ac5b89",
          "name": "getUserUserActivitiesCaloriesDateStartDateOrEndDateEndDateOrPeriod.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/:user-id/activities/calories/date/:start-date-or-end-date/:end-date-or-period.json"
              ],
              "variable": [
                {
                  "id": "user-id",
                  "value": "user-id",
                  "type": "string"
                },
                {
                  "id": "start-date-or-end-date",
                  "value": "start-date-or-end-date",
                  "type": "string"
                },
                {
                  "id": "end-date-or-period",
                  "value": "end-date-or-period",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get time series in the specified range for a given resource in the format requested using units in the unit system which corresponds to the Accept-Language header provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e9b4445-fc85-46a2-9c09-a825b06585de"
            }
          ]
        },
        {
          "id": "b2906575-1a62-4a43-ba3f-24e47aac7728",
          "name": "deleteUserActivitiesActivityLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/activities/:activity-log-id.json"
              ],
              "variable": [
                {
                  "id": "activity-log-id",
                  "value": "activity-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's activity log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fad02a9a-7900-4470-b5af-dd5759881626"
            }
          ]
        },
        {
          "id": "5300149c-a3a6-45c1-8e80-d392ea6334a0",
          "name": "getUserActivities.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/activities.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get user's activity statistics in the format requested using units in the unit system which corresponds to the Accept-Language header provided. Response contains both lifetime statistics from the tracker device and total numbers including the manual activity log entries as seen on the Fitbit website dashboard."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b034acb3-e75a-4d03-b94a-31bc4c92a5ad"
            }
          ]
        }
      ]
    }
  ]
}