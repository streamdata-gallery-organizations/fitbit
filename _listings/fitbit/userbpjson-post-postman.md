{
  "info": {
    "name": "Fitbit Post User Bp.json",
    "_postman_id": "d3759cbd-08b4-48d6-80de-c95b57566c8b",
    "description": "Create log entry for a blood pressure measurement and get a response in the format requested.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "c6bafe1e-3599-4bb1-b622-9dc815fead3f",
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
              "id": "cee521e1-8d88-4f4e-994f-4feff995b7bf"
            }
          ]
        },
        {
          "id": "97f0e7a2-bcfe-4724-bc1e-56496a4764a8",
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
              "id": "ea8b1c1c-3168-4e7d-8ea6-dbca54300693"
            }
          ]
        },
        {
          "id": "f51c560a-bce6-4595-b4ca-8ee882de84bc",
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
              "id": "87a62584-5ce4-4fb2-898f-2439b824e38a"
            }
          ]
        },
        {
          "id": "6ab7e62b-af90-4c3d-9a7a-fdee56021a2e",
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
              "id": "c17089ee-7dfe-411a-9c51-c38a737dcd97"
            }
          ]
        },
        {
          "id": "a97f61ba-17e0-4571-879d-5900be8cc3fe",
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
              "id": "1fcd43f2-1ea8-4287-ad5a-bfce877e5930"
            }
          ]
        },
        {
          "id": "a5bf8af2-ec1e-4d8e-8ca8-6d01aab7d5ad",
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
              "id": "f1e5dd56-df2e-475a-aa7f-6dce05a01af1"
            }
          ]
        },
        {
          "id": "d0a74254-09f4-437f-99ae-1abd9dfab146",
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
              "id": "6fd97e1b-5cd1-435a-9b7f-be609473edd0"
            }
          ]
        },
        {
          "id": "625ae391-48b5-4d79-9ac9-4818fce4b861",
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
              "id": "16a72ad9-bef7-419f-b411-7033023d99ea"
            }
          ]
        },
        {
          "id": "1587ca5f-e6d5-49d5-aca8-59d7334ec355",
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
              "id": "da39de61-a0f4-4544-94b9-ba7303ad004c"
            }
          ]
        },
        {
          "id": "8ad90b78-a3d2-4576-b667-9fe6d86dee91",
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
              "id": "9cab06d4-3c51-4048-99bb-a5e43729a2d4"
            }
          ]
        },
        {
          "id": "2cbdbe11-dbc6-46b8-89f8-07cf5836f312",
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
              "id": "f646d324-20bd-452d-acc4-ba99edcc4ee8"
            }
          ]
        },
        {
          "id": "6a48567f-08e6-47ff-a77f-2ff15b0b850c",
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
              "id": "246b9cbe-5196-4c4c-9847-c975330b984a"
            }
          ]
        },
        {
          "id": "d12e67e9-d8e4-447e-8afb-8e9c7ef2fc59",
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
              "id": "fc8c4701-4be3-4217-ab49-b79605729e03"
            }
          ]
        },
        {
          "id": "b2fc7394-8f0a-4e0d-941c-4327dbb2b397",
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
              "id": "327d51b6-780d-482e-bdfd-0f0d698b4c23"
            }
          ]
        },
        {
          "id": "a013fc09-795e-45fb-9df8-3c54c3cb7486",
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
              "id": "6c8d9cda-082b-4795-b422-c029d1e3ed2e"
            }
          ]
        },
        {
          "id": "95f660ce-2674-45df-99da-6e52f1f729f3",
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
              "id": "0478ae0f-679b-4c49-93f9-672d0c4c7588"
            }
          ]
        },
        {
          "id": "f055cee5-47ed-4aa8-bb17-0b457f2c38d5",
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
              "id": "4b7a9b9d-9041-48cb-bb57-3c2b255cfe06"
            }
          ]
        },
        {
          "id": "04649df5-7e1d-4d9f-8196-33ddd491ec4d",
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
              "id": "cc712ba5-d767-4946-9712-28f33c0bf37c"
            }
          ]
        },
        {
          "id": "a8bc2d86-51c7-4c62-9efb-f4aec0172217",
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
              "id": "b0cedffb-f7ac-4dcd-a889-695890dccb70"
            }
          ]
        },
        {
          "id": "f98d1d82-c8fd-4c65-b312-79367630a8e1",
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
              "id": "cc3182c2-27a5-4541-9778-3630ec0e70a4"
            }
          ]
        },
        {
          "id": "c1cdc9f7-7eee-4b4d-a1ae-0f1859441bce",
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
              "id": "14ec6d2c-7dec-4e9f-b8fb-7c12c84c2fdc"
            }
          ]
        },
        {
          "id": "a44d40a4-7a43-446c-99d6-b3cd1f7ca5dd",
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
              "id": "ece340b8-4562-460c-8cab-0827b6a96ad0"
            }
          ]
        },
        {
          "id": "78cfccc2-531e-4d7a-824c-ca3b7c3c0899",
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
              "id": "62a84638-bfd6-4f5e-b9c9-e8f029b40a80"
            }
          ]
        },
        {
          "id": "65a7a608-5282-4fb5-9aa6-e9af5f57f64f",
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
              "id": "b2f0e6a1-2d9d-45b7-8a7f-c53143528350"
            }
          ]
        },
        {
          "id": "0017b1a0-3d89-4890-a76c-106e8db8fb54",
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
              "id": "4a016b59-9f63-455e-9f14-3401c6b7aa51"
            }
          ]
        },
        {
          "id": "47a56d29-a69e-4fc6-8cc7-eb62e3b40ce9",
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
              "id": "186b1dad-262d-42c4-a985-aa351a0636d6"
            }
          ]
        },
        {
          "id": "332ea0a8-ffc2-4916-84ab-5dd9739ab715",
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
              "id": "44b0a1fa-fb5a-494a-a27d-54d06fbe869a"
            }
          ]
        },
        {
          "id": "f07608d1-473f-4336-8833-16495490706c",
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
              "id": "bdc2e489-3b79-4ed2-bde9-d2215b4b62ce"
            }
          ]
        },
        {
          "id": "f3496bdb-e9ef-43e2-a526-b5043ee63f80",
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
              "id": "88d4a55c-df2b-428b-9181-4c465f331422"
            }
          ]
        },
        {
          "id": "32201091-5032-4015-aa71-ea4cd3443799",
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
              "id": "5962bcdc-318e-410f-ac36-9f7a51590648"
            }
          ]
        },
        {
          "id": "a3b91b7a-6ada-404c-959e-f5d553cc154b",
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
              "id": "f98e3e7e-3fc5-4a18-93cd-7d8cbce5f8d1"
            }
          ]
        },
        {
          "id": "16cfd456-f95a-4cad-a92a-d08b03cb758d",
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
              "id": "6257c253-672b-4e22-be2c-3edf7b0c3226"
            }
          ]
        },
        {
          "id": "9b15310f-71de-4d9c-bf0c-a789213384ef",
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
              "id": "09793cd3-e766-4ea1-95f4-99cc3e737f77"
            }
          ]
        },
        {
          "id": "f634eda3-2ad9-4492-a10d-5620034028bf",
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
              "id": "30782f51-6a8c-45fa-a12b-59d0fb1817d7"
            }
          ]
        },
        {
          "id": "516facb5-73c3-4b08-b4b1-ddedf0539104",
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
              "id": "dcbbe6b6-8ee9-405c-a5ef-bb7bf9429fe5"
            }
          ]
        },
        {
          "id": "1736543f-15e2-42cb-b92f-2cbc100bc026",
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
              "id": "4ae153f4-4b71-4c8e-859e-3a08dbdecf63"
            }
          ]
        },
        {
          "id": "32ad0ff0-ea90-4a46-ac34-ae37a390b728",
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
              "id": "6f847953-6a4b-45e6-ab66-6eb474daa283"
            }
          ]
        },
        {
          "id": "0a1a11a5-a238-404a-96c6-4447384483c5",
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
              "id": "03501322-4787-4c4d-9b55-7fca6cd9d61e"
            }
          ]
        },
        {
          "id": "bb3772f3-7d67-4114-87f5-e9bd12fef1a6",
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
              "id": "4331e951-649b-49d6-887e-e89eadcb49fc"
            }
          ]
        },
        {
          "id": "ab67e3e5-f183-4c1b-8b50-9c5b5ab9c779",
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
              "id": "c64c5ad1-f4f6-4e89-a894-dd6d78fc7070"
            }
          ]
        },
        {
          "id": "44937e08-294a-4fe3-81f3-58d34d0b6999",
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
              "id": "89d9f86b-4399-4476-b6a8-50375b99088b"
            }
          ]
        },
        {
          "id": "f315ec65-5df7-4dd6-b6ae-44abd8946462",
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
              "id": "88da07a4-1430-4dcc-b28e-e467ee2ac86c"
            }
          ]
        },
        {
          "id": "2e81aa5a-2156-4d78-a406-66e6527dac16",
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
              "id": "998262fb-be29-46ff-ae17-4b2d857ab5dc"
            }
          ]
        },
        {
          "id": "873ccd3d-0df2-4076-a40f-694a3f8301d0",
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
              "id": "4189981e-fcec-43f0-892b-d220c4c2627c"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "02df10fe-0de4-4e1d-9051-795e78ce1977",
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
              "id": "2b3a6c5b-41f9-47e0-808b-76475f5b971e"
            }
          ]
        },
        {
          "id": "003d5f54-6bd6-407a-a2a8-e823ef3e0299",
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
              "id": "3f2d2fce-839f-4a81-ab7d-8251071f4dc5"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "056e0950-3a51-4e35-ba1c-c6e08c0d1163",
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
              "id": "804a38b8-dbc8-42bb-a677-1cdf259405bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "4aabfc27-7bba-48f8-81a7-99f9f2bc7bf8",
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
              "id": "b9d885a9-34b6-4de9-9e89-ba30e8039cf3"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "adb2e4e4-92f1-4db2-b2d7-733020a5ee2b",
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
              "id": "ff38b124-549f-443f-a746-f3bd7c7a508c"
            }
          ]
        }
      ]
    }
  ]
}