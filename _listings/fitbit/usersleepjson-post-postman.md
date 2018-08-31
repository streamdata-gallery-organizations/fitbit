{
  "info": {
    "name": "Fitbit Post User Sleep.json",
    "_postman_id": "9987bc6b-3eed-422f-9b0f-501e020fc20b",
    "description": "Create log entry for a sleep and get a response in the format requested.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "94165c9d-1bae-4166-b151-894a5c58e7be",
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
              "id": "100a3374-910c-4410-9f53-6d1309b24a04"
            }
          ]
        },
        {
          "id": "c73b5b6b-5ca3-4106-8443-d4aaf61e0516",
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
              "id": "d345770f-c052-4bcb-8837-b013cd266f0b"
            }
          ]
        },
        {
          "id": "056204e6-2c09-4d31-88b9-a06fcd7d947f",
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
              "id": "f28e3311-f826-42bc-8f50-bfec1bd08221"
            }
          ]
        },
        {
          "id": "a4455f6d-813a-4724-9843-c9ab39567d93",
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
              "id": "d5f0cb3c-5047-4efc-b105-641c4242597a"
            }
          ]
        },
        {
          "id": "0f4e6bdb-8802-49da-8312-8cbb37e7e051",
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
              "id": "c4944713-1c49-44ea-b237-2f5e16c3fcba"
            }
          ]
        },
        {
          "id": "8b8c5e3c-3832-4f48-aa1a-dcbb7dd83ec2",
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
              "id": "f4a33429-154f-41e9-b254-9483a007b7fb"
            }
          ]
        },
        {
          "id": "a1aa910d-9437-40f7-b9d3-fb47fe21f8b2",
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
              "id": "d0742983-f30d-4e57-9937-3a6e283eec37"
            }
          ]
        },
        {
          "id": "4833e938-2491-4b4e-88ea-ed2f93897099",
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
              "id": "1c4986ba-c4cd-45ea-964f-6c30244add38"
            }
          ]
        },
        {
          "id": "269477bf-8839-425a-b7f3-26f7ce2d9e4f",
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
              "id": "7454e1c2-3c6b-425e-b0aa-869a9161f167"
            }
          ]
        },
        {
          "id": "21f57478-0c4c-4b30-a613-b58c4587f7ba",
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
              "id": "ef9359a5-1a83-4d6f-9b78-fc341cebb227"
            }
          ]
        },
        {
          "id": "b8a86173-3dfd-4f11-ae2a-7c90c96d8d1b",
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
              "id": "e5ddd6b7-ffb2-49dc-a55f-4815dcb9b7b4"
            }
          ]
        },
        {
          "id": "bf7bacc7-049d-4122-93ba-83f00e063b52",
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
              "id": "1b24ee5e-473c-4fa4-8756-3cac81293fe1"
            }
          ]
        },
        {
          "id": "5f818430-127d-4f1e-8ee2-f720e171e4b5",
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
              "id": "213b44fa-e5e9-4bb1-9da7-10f903e3f415"
            }
          ]
        },
        {
          "id": "c2e9ecd7-d5bf-4045-892c-07299b0060a1",
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
              "id": "ed247616-0a57-49c7-93d6-52fd04f7fc38"
            }
          ]
        },
        {
          "id": "6da79d3c-a02b-4443-bc35-c08e01a6f0bf",
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
              "id": "baa745bd-fa6a-44fb-a2a7-76c856a6262e"
            }
          ]
        },
        {
          "id": "bc5e294c-8bec-4d2f-ab6b-3b318e86e2fb",
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
              "id": "1551d88e-d6d2-4b3f-9f94-ceca688081c5"
            }
          ]
        },
        {
          "id": "7874058f-d049-4eda-aff3-7f0cbac8ef3e",
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
              "id": "2a8d63ad-1d3e-4a7b-ae89-c5f456ade6b0"
            }
          ]
        },
        {
          "id": "7947f41a-7825-4e75-ba1b-24956117a88e",
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
              "id": "804d2893-1793-4b4e-9c24-fa677ea2dcf5"
            }
          ]
        },
        {
          "id": "47a21971-b296-4a1a-ac73-6d4ca72a8c6b",
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
              "id": "acc539e0-21f2-4a7d-99e4-6f3c1a30b1e8"
            }
          ]
        },
        {
          "id": "328d7fd5-ba4a-43f0-bc3e-efc9de2831e2",
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
              "id": "199a9d1a-97e3-42d5-abf2-9f517193bbfc"
            }
          ]
        },
        {
          "id": "7224f48f-fe27-4b50-9c30-c96cc4cdc4c6",
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
              "id": "13e927e1-aa76-4efc-830b-ba59d4f221e1"
            }
          ]
        },
        {
          "id": "17b79733-ddfd-4e95-bd02-4bcaee749941",
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
              "id": "ca367c66-b5be-41ee-8a2a-4b2e9666a1d0"
            }
          ]
        },
        {
          "id": "f390f9f9-64b5-483c-8d7a-47c90aa5ede5",
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
              "id": "aa9e0e85-ccfc-4169-8984-c249e5fc68fd"
            }
          ]
        },
        {
          "id": "5d899d24-23d2-4929-b002-493fcf238e8f",
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
              "id": "54553ffd-7245-42cf-9498-a0336f0fec6e"
            }
          ]
        },
        {
          "id": "ec7501a3-a5b0-4fb8-87b7-816e5d513ea5",
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
              "id": "96eda6ae-dc1d-433e-ac43-951183d6b672"
            }
          ]
        },
        {
          "id": "0f9a2e67-1311-46ac-9e5b-74b6c66011b1",
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
              "id": "25b712bd-b70a-4c68-b372-93c63b1637eb"
            }
          ]
        },
        {
          "id": "0ab58ffb-8a2e-4916-9c6f-556e93731be8",
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
              "id": "95b87c00-571d-4961-976a-b1a47703f5b9"
            }
          ]
        },
        {
          "id": "7c62ad7b-25f3-4ed7-ac2b-821e117c3233",
          "name": "getUserBodyLogWeightGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/weight/goal.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a user's current weight goal using units in the unit system that corresponds to the Accept-Language header provided in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c93aeee3-4ebf-4fae-98ea-1e65a320df84"
            }
          ]
        },
        {
          "id": "8cd86b94-db94-4af8-8b2f-b771f6c86726",
          "name": "postUserBodyLogWeightGoal.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/weight/goal.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create or update user's weight goal using units in the unit system that corresponds to the Accept-Language header provided and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cf089de-62e1-4f7b-a1a8-30e31b03eed7"
            }
          ]
        },
        {
          "id": "078d62b8-7c97-476e-a805-41abcaf3182d",
          "name": "deleteUserBodyLogFatBodyFatLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/body/log/fat/:body-fat-log-id.json"
              ],
              "variable": [
                {
                  "id": "body-fat-log-id",
                  "value": "body-fat-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's body fat log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d30ee9c8-3fb1-454e-bb90-6ba77802eed5"
            }
          ]
        },
        {
          "id": "60ba7324-fe51-4ca6-9060-f834034cc3dd",
          "name": "deleteUserBodyLogFatBodyWeightLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/body/log/fat/:body-weight-log-id.json"
              ],
              "variable": [
                {
                  "id": "body-weight-log-id",
                  "value": "body-weight-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's body weight log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06525c17-7f78-4385-b01b-5cbf2971763d"
            }
          ]
        },
        {
          "id": "f36f300a-f033-419d-bf0f-bcfc44503cdf",
          "name": "postUserBodyLogFat.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/fat.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a body fat and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa6b39cd-3977-4214-925e-428fc624d52f"
            }
          ]
        },
        {
          "id": "6d179e8e-b0fa-4eea-8d2a-427b032aa8a0",
          "name": "postUserBodyLogWeight.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body/log/weight.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a body weight using units in the unit system that corresponds to the Accept-Language header provided and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "081fa4e9-97a0-4a9f-9bac-ea93e9e2d843"
            }
          ]
        },
        {
          "id": "865ca75b-50d9-4c8d-880e-afe71c309e92",
          "name": "postUserBody.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/body.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Log body measurements using units in the unit system that corresponds to the Accept-Language header provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "966a36c1-b46b-4a3b-897c-00fe46287c05"
            }
          ]
        },
        {
          "id": "5a761d63-652a-4ae9-b2cb-df3146bda3e6",
          "name": "getUserUserBodyWeightDateStartDateOrEndDateEndDateOrPeriod.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/:user-id/body/weight/date/:start-date-or-end-date/:end-date-or-period.json"
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
              "id": "9ae25848-ca16-449e-a717-77ea3ae70951"
            }
          ]
        },
        {
          "id": "f54e1c26-68ae-42d8-8992-8591ae1ce0bd",
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
              "id": "9786c22e-b396-4d7c-a871-6a529e932ed7"
            }
          ]
        },
        {
          "id": "94dea153-7660-444f-bb7b-cdadec9f72c5",
          "name": "deleteUserBpBpLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/bp/:bp-log-id.json"
              ],
              "variable": [
                {
                  "id": "bp-log-id",
                  "value": "bp-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's blood pressure log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f424d55-d1a5-45d7-89ff-1f19417794e1"
            }
          ]
        },
        {
          "id": "27ef14e6-94d4-401c-a122-53b1deeedbd9",
          "name": "deleteUserHeartHeartLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/heart/:heart-log-id.json"
              ],
              "variable": [
                {
                  "id": "heart-log-id",
                  "value": "heart-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's heart rate log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c05ed745-9683-44c4-9d58-1be583a56b3b"
            }
          ]
        },
        {
          "id": "5919a1e8-9a5d-4267-9959-c92bc653276c",
          "name": "deleteUserSleepSleepLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/sleep/:sleep-log-id.json"
              ],
              "variable": [
                {
                  "id": "sleep-log-id",
                  "value": "sleep-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete user's sleep log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a28d8ef-3e10-46a1-a123-9a1ccdb43d8f"
            }
          ]
        },
        {
          "id": "b4bd7443-e7c4-422a-bd8a-448acf02dfd2",
          "name": "getUserUserBadges.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/:user-id/badges.json"
              ],
              "variable": [
                {
                  "id": "user-id",
                  "value": "user-id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get user's badges in the format requested. Response includes all badges for the user as seen on the Fitbit website badge locker (both activity and weight related). We return weight and distance badges based on the user's unit profile preference as on the website."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8a0e854-f6ae-4296-9155-2ce693b47dda"
            }
          ]
        },
        {
          "id": "1da8309a-e6cb-4367-b607-22a388f1c23d",
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
              "id": "90e4d07e-939a-412c-82d8-8448d729716d"
            }
          ]
        },
        {
          "id": "8d1d8c33-3ac7-4406-9a65-ffe9e4a464cc",
          "name": "deleteUserFoodsLogFoodLog.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.fitbit.com",
              "path": [
                "1",
                "user/-/foods/log/:food-log-id.json"
              ],
              "variable": [
                {
                  "id": "food-log-id",
                  "value": "food-log-id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the user's food log entry with the given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "addf695c-06a3-4bca-b8ba-3a14d1b72ed4"
            }
          ]
        },
        {
          "id": "c8bf8adf-3eb9-44df-aee4-22f62dad10b9",
          "name": "postUserGlucose.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/glucose.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a blood glucose measurement and/or HbA1c using units in the unit system which corresponds to the Accept-Language header provided and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c5284de-41f5-4f00-bfe0-f939bd9a4231"
            }
          ]
        },
        {
          "id": "d6bbc827-02c0-4585-ba56-6792c0d7fd5c",
          "name": "postUserBp.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/bp.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a blood pressure measurement and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29bc9005-09fd-4d6d-8bdd-e2e14cdbf589"
            }
          ]
        },
        {
          "id": "b178d1f0-a0f2-4a9d-a039-ffff821cc2b7",
          "name": "postUserHeart.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/heart.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a heart rate measurement and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2663f8cb-78b2-4f33-836d-89fb2343bb5c"
            }
          ]
        },
        {
          "id": "45dfcbf6-cea0-4be3-910e-b2c37f025c6b",
          "name": "postUserSleep.json",
          "request": {
            "url": "http://api.fitbit.com/1/user/-/sleep.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create log entry for a sleep and get a response in the format requested."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f648287-6bef-435d-8145-ed50d3ad5d60"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "de01286e-98a9-429e-941d-a6fc96f1d618",
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
              "id": "21252219-3f7b-4022-81ef-75940e6d3cc4"
            }
          ]
        },
        {
          "id": "4efe48f6-6f22-4216-bdd4-0e3918b50bdd",
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
              "id": "02616fe2-c2b3-4ca7-970a-e86f47e656f5"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "e064320f-0a68-4f27-9497-c86139ece7e7",
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
              "id": "f711025f-a454-425d-a739-6a1790134ed2"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "28c3f849-82a3-47e9-b747-b2cb241b462d",
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
              "id": "1f3e5f9d-0932-4a72-b6a6-a2388d1f0388"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "df385894-c2e5-46f5-ad5e-d48a31fdf579",
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
              "id": "0e7431f5-d938-4a60-bc82-4334f20f6ae3"
            }
          ]
        }
      ]
    }
  ]
}