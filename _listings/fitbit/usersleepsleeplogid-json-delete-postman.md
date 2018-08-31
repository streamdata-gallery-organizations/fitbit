{
  "info": {
    "name": "Fitbit Delete User Sleep Sleep Log .json",
    "_postman_id": "f3b69e99-74fe-4e01-aabf-1a0126579c7d",
    "description": "Delete user's sleep log entry with the given id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "e84cb971-0544-47e5-b0f9-dcad2ac9d654",
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
              "id": "16f7c627-2d10-4060-b174-a095647215be"
            }
          ]
        },
        {
          "id": "a6ecc900-2310-40ce-a560-28b8b30bb82b",
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
              "id": "a3d713f7-b956-4589-b13d-d4d7c5f99e31"
            }
          ]
        },
        {
          "id": "511a1e80-4c52-4d27-a132-48b9e3f7bd74",
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
              "id": "28600949-06be-46db-8f54-318d98d3da6a"
            }
          ]
        },
        {
          "id": "27f5b244-4a2c-48b5-8ece-b2aa3ada9463",
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
              "id": "fffcde37-dee4-4c17-9f6d-368193e1167b"
            }
          ]
        },
        {
          "id": "1201524e-ec38-4408-8196-66e36ed2ba85",
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
              "id": "d6bf0057-e80b-4570-8226-1944ce4e55bd"
            }
          ]
        },
        {
          "id": "80a0ffd6-c3b4-424b-b6df-7ba6f67c7aab",
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
              "id": "46936971-2f7d-467e-baaa-b95d7f2312eb"
            }
          ]
        },
        {
          "id": "92f60c53-5010-4be2-94a5-2f738d08f6b8",
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
              "id": "300cff9a-1f1f-4031-b9b9-d74c1367cc49"
            }
          ]
        },
        {
          "id": "e9cea398-1ea2-43cf-930d-45bcaf21cd1b",
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
              "id": "c63140dc-88ab-436e-bddb-b5ebc21750aa"
            }
          ]
        },
        {
          "id": "101f82fb-8c60-45c3-a0f9-0ab360cd397f",
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
              "id": "110b33a5-fc2d-4b76-8ebd-dfd14c812ff8"
            }
          ]
        },
        {
          "id": "a32147a8-d95d-47f1-9ca2-1647eb829ad5",
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
              "id": "8e68daf9-e96c-47e3-a6e8-fdc3e3d62d7f"
            }
          ]
        },
        {
          "id": "cfd3e4f8-0b0e-4002-9edf-6be35da05b5a",
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
              "id": "70df0d22-b341-4f47-a489-99c3fae868e4"
            }
          ]
        },
        {
          "id": "0eb1f7e5-23bf-45ea-9415-b3e87e4564fb",
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
              "id": "e1e197b5-384d-46bc-9694-5d32f1dd311d"
            }
          ]
        },
        {
          "id": "9e6f6b7d-b91a-4a93-97f6-259b0c3dc2f9",
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
              "id": "2e95e1cb-f2ab-4448-aa7b-c4cc7ac54983"
            }
          ]
        },
        {
          "id": "de228bcc-2318-4a60-a876-817f0beec497",
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
              "id": "cd9d9ce3-f538-434d-a154-c9e6f70f6b72"
            }
          ]
        },
        {
          "id": "85a1843a-103b-479e-b38e-57a7de28d7f1",
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
              "id": "814a131a-cdb1-42e9-8178-afa560aab5e2"
            }
          ]
        },
        {
          "id": "7cb3d010-d646-43a2-8a4d-e4717133ab28",
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
              "id": "fa6054bf-1f52-4328-a479-13b1ee0c10c2"
            }
          ]
        },
        {
          "id": "cc6acb2d-9676-4dd1-a06a-d083907a1d0a",
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
              "id": "2686182e-ac29-42cc-9e40-5e74b0ba286f"
            }
          ]
        },
        {
          "id": "b8657f82-b450-44e2-b8c8-8204823b6be0",
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
              "id": "ebb6caff-6460-476e-983c-1149d9e77912"
            }
          ]
        },
        {
          "id": "4196c357-141f-4bd4-8d0b-83044f25f862",
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
              "id": "dab6cde7-c307-4b8d-9b6d-14b820bc23b5"
            }
          ]
        },
        {
          "id": "a4b337b2-bf84-423b-a400-38681f7e1883",
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
              "id": "67e3f34c-c0a9-4412-8c91-96da7d6330e6"
            }
          ]
        },
        {
          "id": "d656d69c-c961-40ff-b174-bfa8fb67ba41",
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
              "id": "30f535b3-928e-47dc-b91e-6821e98d043b"
            }
          ]
        },
        {
          "id": "be7a97f0-99a5-415a-ba12-90e9ece925fb",
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
              "id": "f82e9ab0-1fe3-4a51-90b6-96fd6c31fd76"
            }
          ]
        },
        {
          "id": "57c2d2f6-9ad0-43cf-b802-ce66ee1c1213",
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
              "id": "6ad04056-bc96-4fa2-a335-e00d70d46bf6"
            }
          ]
        },
        {
          "id": "aad0156f-de88-4cc5-883b-697fafc3dc89",
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
              "id": "18cf8558-9eb3-4152-9de9-99df6c7d855a"
            }
          ]
        },
        {
          "id": "89583a1f-6e07-40f0-8c95-4cf8a428433b",
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
              "id": "3cc85717-9286-4cf1-8405-3cb98bb16fb8"
            }
          ]
        },
        {
          "id": "df255c4f-69ca-4996-b6e2-19600070610a",
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
              "id": "79e2ba93-f9d0-401c-89be-5ddee706d5fb"
            }
          ]
        },
        {
          "id": "7e2474c3-e446-4499-8385-b30d8a71b9db",
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
              "id": "b5a01800-eaa0-489a-9fab-03d3e03c2cfe"
            }
          ]
        },
        {
          "id": "0dad8b12-0827-4f1c-97bc-52442068cb3d",
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
              "id": "8fb24f14-b36f-4643-8d96-bd546fa606ff"
            }
          ]
        },
        {
          "id": "03621820-d32e-4bc4-b57a-47786cabe4fd",
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
              "id": "cb386f2b-cc93-4ff8-960e-a1005baac0df"
            }
          ]
        },
        {
          "id": "31df3db4-6b23-4b05-aa69-abb1d61331ef",
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
              "id": "1cf4b388-3fdd-4cf3-8baf-bc152fb6ff9a"
            }
          ]
        },
        {
          "id": "f217bf3a-a1a8-44af-8e8d-81f4746246d5",
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
              "id": "f012061a-5e03-4c5d-a7e9-b2785592155f"
            }
          ]
        },
        {
          "id": "64ca0790-6879-48fe-aa8a-1977e93695c6",
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
              "id": "abf89440-e1bd-44bc-b66d-da0a8ac437d1"
            }
          ]
        },
        {
          "id": "88f1ae4f-3ea8-40d0-aa52-ac895474b2de",
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
              "id": "1cda8b40-4ff3-4421-a8d5-d33c2730b55f"
            }
          ]
        },
        {
          "id": "51efd497-8e6c-451d-b13d-ec3fa1fa1001",
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
              "id": "d72c1417-c1b0-403a-bbd5-35b901770bba"
            }
          ]
        },
        {
          "id": "4a3d9a61-0652-4651-87cb-0d0f10b7b24a",
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
              "id": "40b10ece-19e7-418c-ad65-0eeecd58b1d4"
            }
          ]
        },
        {
          "id": "694fee3a-b898-47c7-8a2c-cd37a7340881",
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
              "id": "db37c45f-a7ce-4893-bb70-0f01f0fa3d0f"
            }
          ]
        },
        {
          "id": "57eb1e68-d542-4104-8774-6f74aa2113e3",
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
              "id": "81557d40-98fa-4e74-95fa-50f1c6103465"
            }
          ]
        },
        {
          "id": "403ed8f9-1a82-477e-a4d0-83e508c7da19",
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
              "id": "15b69330-2a71-4209-85fd-abf338b141a0"
            }
          ]
        },
        {
          "id": "a37ee8b6-f8af-4bdd-8c99-4f06a22fe485",
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
              "id": "e1ccb953-9976-495e-9a2a-5ed7df430251"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "dc00ecdb-8a46-4f0f-8204-d884708964ab",
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
              "id": "34da16b5-d335-47a7-a9c8-dddacabc624f"
            }
          ]
        },
        {
          "id": "9a557396-b82e-4eb6-ad6c-2ba4a16f5d59",
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
              "id": "ce44fc24-825d-4b0a-b399-a41ea734ffd0"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "c18e8bf2-a4cc-4119-81a4-34dbf75b63c5",
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
              "id": "c20c332a-008a-4f78-978b-3a193776ce79"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "33fed2f4-56fc-4edb-ae12-dc97b45c70ee",
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
              "id": "7044d51f-cbd1-4018-bd34-86e4a516ca42"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "b86c170f-38b2-4262-9e91-1bc67ab8b8dc",
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
              "id": "0bc16681-95ef-4cc5-9e32-cf716c378be7"
            }
          ]
        }
      ]
    }
  ]
}