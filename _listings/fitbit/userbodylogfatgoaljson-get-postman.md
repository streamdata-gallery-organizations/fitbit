{
  "info": {
    "name": "Fitbit Get User Body Log Fat Goal.json",
    "_postman_id": "162091c8-5bf6-427b-8c8d-b275ef1c0a9c",
    "description": "Get a user's current fat goal in the format requested.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "023b2481-e171-47a3-86ef-eaeff20d6da1",
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
              "id": "ef5fa62d-4b58-480e-af1d-26306fdf2c6d"
            }
          ]
        },
        {
          "id": "89e001d3-3e2c-4eed-8c0c-4cc89130825c",
          "name": "postUserCollectionPathApisubscriptionsSubscription.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-:collection-pathapiSubscriptions/:subscription-id.json"
              ],
              "variable": [
                {
                  "id": "collection-path",
                  "value": "collection-path",
                  "type": "string"
                },
                {
                  "id": "subscription-id",
                  "value": "subscription-id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a subscription for the user to get notifications and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e48e8259-6fe6-4e49-91be-6f8cb342b665"
            }
          ]
        },
        {
          "id": "c40cb304-d579-4455-9dc0-f91102133d0f",
          "name": "deleteUserCollectionPathApisubscriptionsSubscription.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-:collection-pathapiSubscriptions/:subscription-id.json"
              ],
              "variable": [
                {
                  "id": "collection-path",
                  "value": "collection-path",
                  "type": "string"
                },
                {
                  "id": "subscription-id",
                  "value": "subscription-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a subscription for the user and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cf27d35-4f44-4391-be60-5b919cd64983"
            }
          ]
        },
        {
          "id": "a974826c-0122-4a7b-a18a-a8ac98adda80",
          "name": "getUserFriendsInvitations.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/friends/invitations.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve the list of invites to become freinds for a user in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0aec9a9-df0b-42a9-8ae6-f6ecf00fc119"
            }
          ]
        },
        {
          "id": "55c0e7ee-692c-459c-b48f-9fdad77e994c",
          "name": "getUserDevices.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/devices.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve the list of Fitbit devices for a user in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "248b83d7-eabb-40c6-9852-4fc40ce6c80c"
            }
          ]
        },
        {
          "id": "fbfd0dac-8987-42fa-8cb6-51aaa9c5a89f",
          "name": "getUserFoodsLogGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/goal.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a user's current daily calorie consumption goal and/or Food Plan in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6ccd957-70e9-469c-b528-304e32245a5d"
            }
          ]
        },
        {
          "id": "330ea653-740c-4690-9b1c-ef58460a1c15",
          "name": "postUserFoodsLogGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/goal.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Update (create) a user's daily calorie consumption goal or Food Plan and get a response in the format requested. Food Plan could not be created unless user already has active goal (Update-Weight-Goal). Depending on the weight goal setup only either MAINTENANCE (in case start weight is close to target weight or smaller) or one of the four other \"lose\" food plans could be created via intensity POST parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6082bdb9-be63-4b35-b63f-61cf4a7c6b0b"
            }
          ]
        },
        {
          "id": "59e05094-7a11-46a1-b648-1b4fecc657f2",
          "name": "getUserMeals.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/meals.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of meals user created in his food log in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca40764b-01a2-4106-8b79-49043a969b86"
            }
          ]
        },
        {
          "id": "b9cb224f-6452-4af9-981c-3f1bd44f25f8",
          "name": "deleteUserFoodsLogWaterWaterLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/foods/log/water/:water-log-id.json"
              ],
              "variable": [
                {
                  "id": "water-log-id",
                  "value": "water-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's water log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0181677b-354c-46f4-83a1-2c22a800735d"
            }
          ]
        },
        {
          "id": "21c6e604-ae51-4ba4-b79e-90764eaa1dc2",
          "name": "postUserFoodsLogWater.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/water.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a water using units in the unit system that corresponds to the Accept-Language header provided (or waterUnit) and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0519d27b-7bc1-4e50-b49a-d152d8afd76c"
            }
          ]
        },
        {
          "id": "d0aa45c6-e427-4731-bb57-8f2e404961dd",
          "name": "getUserFoodsLogWaterDateDate.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/foods/log/water/date/:date.json"
              ],
              "variable": [
                {
                  "id": "date",
                  "value": "date",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a summary and list of a user's water log entries for a given day in the format requested using units in the unit system which corresponds to the Accept-Language header provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a16518ed-7ff5-47ab-8b85-e74cb806d209"
            }
          ]
        },
        {
          "id": "bbe6ea4f-90be-4b40-870c-f67e0443edfc",
          "name": "postUserFoodsLogFavorite.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/foods/log/favorite/:id.json"
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
            "description": "Add the food with the given id to user's list of favorite foods."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdcea22b-37f6-4e77-ad6a-bd845af96a94"
            }
          ]
        },
        {
          "id": "d2971bde-40ee-4e46-81e1-13bb1fb08c02",
          "name": "deleteUserFoodsLogFavorite.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/foods/log/favorite/:id.json"
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
            "description": "Delete the food with the given id from user's list of favorite foods."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89f3b27c-6d52-4592-88e3-b4daac0cb093"
            }
          ]
        },
        {
          "id": "ff03b456-a0e7-49ec-920b-65612f759409",
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
              "id": "dff3fca0-3789-45dc-a687-0348aa4ab6c7"
            }
          ]
        },
        {
          "id": "92f10532-d06c-4829-8c4f-8a596543ef64",
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
              "id": "5f93cb4d-902c-499b-ba3b-dc634c8b0a90"
            }
          ]
        },
        {
          "id": "cf8c56d5-c6cd-4123-8ec1-e3658d7157de",
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
              "id": "0f91bba6-eb7c-4046-a0d2-42fc3131d890"
            }
          ]
        },
        {
          "id": "25e7aa7f-078c-406a-9ca4-96b7bfcf608b",
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
              "id": "d95d593e-d17a-420a-9d3e-2a74fdaea528"
            }
          ]
        },
        {
          "id": "f1df206a-1b16-4103-9180-15a55b2b99ad",
          "name": "getUserFoodsLogFavorite.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/favorite.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's favorite foods in the format requested. A user marks a food as favorite on the user's Food Tab tab. A favorite food in the list provides a quick way to log the food via the Log Food endpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31dc07f7-400e-4766-a003-f6cefd0d6c45"
            }
          ]
        },
        {
          "id": "0c3d56de-dfdb-4499-ae68-121f87556299",
          "name": "getUserFoodsLogFrequent.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/frequent.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's frequent foods in the format requested. A frequent food in the list provides a quick way to log the food via the Log Food endpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc97c1c5-eb6e-42bb-8e94-f62c428bacd0"
            }
          ]
        },
        {
          "id": "bac33a1e-9de8-4cdb-aacc-cd2ee1483927",
          "name": "getUserFoodsLogRecent.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/foods/log/recent.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of a user's recent foods in the format requested. A recent food provides a quick way to log the food via the Log Food endpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4f811ae-42f5-4d3f-8484-70275ebf4de2"
            }
          ]
        },
        {
          "id": "67d935db-936e-4217-9bc9-2659b9a3be5f",
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
              "id": "1b967a68-fd7f-4126-955d-7e86a5b2892b"
            }
          ]
        },
        {
          "id": "a8292c10-5f44-4e4a-aa87-e3d32cf5a187",
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
              "id": "19bbf9a4-b32a-496d-8ce6-085fd18c4e4f"
            }
          ]
        },
        {
          "id": "69b4a6a9-2258-456d-929a-6ed3120d9f30",
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
              "id": "788ee0b6-5f08-42b7-a13c-d3c75831a56c"
            }
          ]
        },
        {
          "id": "6d106b0f-3fdb-467d-a307-aa454025160c",
          "name": "getUserUserSleepMinutesasleepDateStartDateOrEndDateEndDateOrPeriod.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/:user-id/sleep/minutesAsleep/date/:start-date-or-end-date/:end-date-or-period.json"
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
              "id": "62d6f097-852b-46f5-847e-d110991a5eee"
            }
          ]
        },
        {
          "id": "57f8573c-3a24-4ddf-b4b2-fae1a50ae2a0",
          "name": "getUserUserFoodsLogCaloriesinDateStartDateOrEndDateEndDateOrPeriod.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/:user-id/foods/log/caloriesIn/date/:start-date-or-end-date/:end-date-or-period.json"
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
              "id": "ea12d6e2-62dc-4f27-8658-2f8a6037ed80"
            }
          ]
        },
        {
          "id": "85badaef-70cf-4f00-abb5-f97e7bb17ab8",
          "name": "getUserBodyLogFatGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/fat/goal.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a user's current fat goal in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acd0c2f0-1f6d-46e0-becf-49c5ab29bf34"
            }
          ]
        },
        {
          "id": "12e06142-9d03-4aeb-8e28-fb396fc7a8a4",
          "name": "postUserBodyLogFatGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/fat/goal.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create or updates user's fat goal and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fa0be29-c79f-4c0f-a0bb-59037c1fe241"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "588a2687-b541-4190-a9cf-f956801dc075",
          "name": "getFoodsUnits.json",
          "request": {
            "url": "http://api.fitbit.com/1/foods/units.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get list of all valid Fitbit food units in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd9a5e78-48e4-45be-a5fb-4728b6112e76"
            }
          ]
        },
        {
          "id": "435d4f87-e8ca-4424-9e70-a1f36d39845b",
          "name": "getFoodsFood.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "foods/:food-id.json"
              ],
              "variable": [
                {
                  "id": "food-id",
                  "value": "food-id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the details of a specific food in Fitbit Food database (or private food for the user) in the format requested. Note, that nutritional values currently included in response only for the private foods."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a9d2543-95da-40f1-84f0-5b32a80b141c"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "55a118f4-d858-46f1-a5e4-8648378a889d",
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
              "id": "f4b13af2-5922-40aa-9f75-1ba8d78ac3df"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "4f7f16c2-ce39-41ef-b392-b95153ae2b3d",
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
              "id": "37912cd7-7093-491d-afd0-60bd06e4b197"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "68137429-7213-4e80-89f2-9cafc06e487e",
          "name": "postFoods.json",
          "request": {
            "url": "http://api.fitbit.com/1/foods.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create new private food for a user and get a response in a format requested. Created private food could be found in results of Search Foods call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ada35d9-5715-41ff-84ef-298e89260403"
            }
          ]
        }
      ]
    }
  ]
}