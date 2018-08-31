{
  "info": {
    "name": "Fitbit Post User Body Log Fat Goal.json",
    "_postman_id": "f283d685-6a81-48dc-9ccc-a04b6e01526e",
    "description": "Create or updates user's fat goal and get a response in the format requested.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "64931a1e-6b69-4334-940e-e8a997e0d2b1",
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
              "id": "442320ec-7530-42eb-a4db-06ccf7d2ef5d"
            }
          ]
        },
        {
          "id": "9cfe529a-e736-4ac5-b075-86b69563a98d",
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
              "id": "53382d24-9291-4d7d-9a54-13ab3a78f100"
            }
          ]
        },
        {
          "id": "20c49d8e-212a-4b6a-ae24-3117990fa60d",
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
              "id": "afad8d63-0a78-4afc-8759-c9efd41475f1"
            }
          ]
        },
        {
          "id": "8fcfd151-727c-4798-961d-822a80dca191",
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
              "id": "3e9f6948-c5cf-4c31-a83b-4f11b02bd42e"
            }
          ]
        },
        {
          "id": "34258fde-9c14-4234-81e6-1f33562e5776",
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
              "id": "a9c93640-0dbb-43e8-9fae-f7fb0bd84c34"
            }
          ]
        },
        {
          "id": "17458611-a85e-40a0-9ed5-687736e3a199",
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
              "id": "a71224c6-4fb2-4121-bc4c-32c6f11fa427"
            }
          ]
        },
        {
          "id": "cd09b74a-1b89-4bf3-8d25-3f1143109c0e",
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
              "id": "cd5a2c72-5734-494d-a54b-88f7cc7fb835"
            }
          ]
        },
        {
          "id": "a7415248-0e30-483d-b584-2a9a7c3e1f7b",
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
              "id": "4c88a40a-5a2f-4f44-a7fb-432f3a79a99c"
            }
          ]
        },
        {
          "id": "ea0db012-7d5f-453c-8e93-32861db7a6a7",
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
              "id": "f2b8e001-08b6-4c92-ac63-8a0a14e32e6d"
            }
          ]
        },
        {
          "id": "7ce25101-9e62-4936-b291-c187fc993e36",
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
              "id": "babd3dc1-e658-4e0b-98e9-23f2878ffeaa"
            }
          ]
        },
        {
          "id": "17bd5c1a-dd36-46b2-b5e1-3a51a05d901c",
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
              "id": "0f2eadc0-86a0-4c48-a952-83178207460f"
            }
          ]
        },
        {
          "id": "ec1a05de-2145-411e-96cf-d99e8134b4a4",
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
              "id": "767c73a8-250b-4f9b-8cf1-162bcbdec2bc"
            }
          ]
        },
        {
          "id": "d1e4b45c-f95d-469f-a0cc-ee20de681826",
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
              "id": "05e9bbae-c572-444a-92da-eaaa526f0be1"
            }
          ]
        },
        {
          "id": "86697102-a7f6-4267-8f99-c5702518b3d4",
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
              "id": "e14820ab-0e58-49b8-b185-292c0e5e4ad6"
            }
          ]
        },
        {
          "id": "235678b9-fcbf-4145-8acb-66a42eb066a2",
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
              "id": "ea489832-05ec-455f-af2c-1c6949e4435b"
            }
          ]
        },
        {
          "id": "3272dbc2-1fea-4975-ac31-0227409aec08",
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
              "id": "95561ce1-7d6b-4096-8a32-03eee1713bbe"
            }
          ]
        },
        {
          "id": "1719c7d2-2db3-4a21-ad86-9830216b5e91",
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
              "id": "89782d1d-8d32-400d-8213-c5a550926c1e"
            }
          ]
        },
        {
          "id": "02b7e01e-e6a1-4d51-bc16-3a647d8d6ad3",
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
              "id": "a726611f-35e4-4fc9-8231-5a1807d71291"
            }
          ]
        },
        {
          "id": "31ec0bb2-6cee-4941-85b7-ff3758b1c4e4",
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
              "id": "b3d06fc8-62de-468d-ba1c-4a76c4231894"
            }
          ]
        },
        {
          "id": "44dadf69-d2db-4611-ad99-533e87f265d4",
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
              "id": "794725d1-3e59-4b50-a040-ebf4a1096ebd"
            }
          ]
        },
        {
          "id": "1fa22fdc-dfe1-4470-bdb3-becaef97eccc",
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
              "id": "23b573ef-3f0c-40a1-8a46-d94350f91b7c"
            }
          ]
        },
        {
          "id": "22826702-beb3-42b9-b47d-9cfcdc2768b2",
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
              "id": "b8ef92cd-519a-4d1f-9e5e-a7b64b6741d6"
            }
          ]
        },
        {
          "id": "8f6cb3f8-b769-45cb-b42d-e160fcfa102c",
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
              "id": "f30533d7-3001-4f6f-8094-39d65a1e851d"
            }
          ]
        },
        {
          "id": "a97d50dc-0911-4bf1-8583-dd5327e7fc5d",
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
              "id": "6f928d6d-1510-41ac-9c12-45afab71a65b"
            }
          ]
        },
        {
          "id": "820c3064-539e-4bce-8074-e693bae20d91",
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
              "id": "e99a1beb-17c3-4414-a641-921689582593"
            }
          ]
        },
        {
          "id": "fcb800ad-a9bd-4c8e-a8f3-143436019f43",
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
              "id": "9efbcf1e-e5c8-4641-80aa-64c6012d2dc5"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "957aea07-4097-4b2a-abcb-0e628d9b4d73",
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
              "id": "addfad70-f108-4819-ba1a-6630ba53b62b"
            }
          ]
        },
        {
          "id": "7e327289-e76f-413b-b37b-df371f8f2345",
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
              "id": "dadca473-cfcb-45a5-8465-2602cc5a2c16"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "96913cad-98eb-4ef8-9d4b-548bddf79965",
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
              "id": "3931e31d-74e9-44a3-b93a-df5800801319"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "ed4df8a8-15e7-4d6b-a236-118f297bdfc9",
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
              "id": "e65fbb91-e515-4df4-8137-40aa93222d6c"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "64f1de3f-cacc-4dd9-818e-019168ee171a",
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
              "id": "5dda0a11-0929-4415-aa68-c4ddacf8f4e6"
            }
          ]
        }
      ]
    }
  ]
}