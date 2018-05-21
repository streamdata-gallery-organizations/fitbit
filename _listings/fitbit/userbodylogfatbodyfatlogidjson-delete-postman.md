{
  "info": {
    "name": "Fitbit Delete User Body Log Fat Body Fat Log .json",
    "_postman_id": "2adb86db-2c57-4816-a80a-f89150d88a23",
    "description": "Delete user's body fat log entry with the given id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "cae153ec-ce4a-48da-ac21-66f4ca56e70f",
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
              "id": "339f80de-a150-4139-a20a-f816760492d6"
            }
          ]
        },
        {
          "id": "9f6b59ca-2f89-4f44-b9f0-653d61b805bc",
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
              "id": "2a6c109c-5aeb-4b5f-93b1-3a6d0e635186"
            }
          ]
        },
        {
          "id": "99e6b6ed-849c-40b1-8fa9-cbde895e8208",
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
              "id": "e090fd88-d0d2-4c6e-a14e-1b48077863a6"
            }
          ]
        },
        {
          "id": "e3b7de6e-df72-479c-9e99-0de76a47ca6e",
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
              "id": "201d06f2-7852-4b59-9890-dc20cb89eaec"
            }
          ]
        },
        {
          "id": "499f4d7c-4a14-4139-a8f1-dc0725332280",
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
              "id": "b4fb6ec0-b405-4bd3-9de2-2654799d18b6"
            }
          ]
        },
        {
          "id": "62fd8b2d-3eb2-445e-95c8-59440fb63782",
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
              "id": "6fbc96b9-9c3b-42ce-8e24-8eec6375ef8f"
            }
          ]
        },
        {
          "id": "15c24036-1c23-4596-a33d-f28944e3e501",
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
              "id": "3c1a44e4-6551-44d0-98c0-52451d47f938"
            }
          ]
        },
        {
          "id": "5795c984-f3c1-41f9-ac95-440ab13045bb",
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
              "id": "adfd91e1-5bd9-4f32-b016-73ef306c5912"
            }
          ]
        },
        {
          "id": "715a57bf-c1d5-4748-b207-0a07cd7f0b78",
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
              "id": "9b6d363a-20e3-42f0-b400-c38d3dc181b0"
            }
          ]
        },
        {
          "id": "b50835d9-ffaf-474f-bba0-aabf5163299f",
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
              "id": "fc9f3d96-7bcb-4398-ae13-9dc3c6571c11"
            }
          ]
        },
        {
          "id": "03d7c3ca-504a-4fd1-adbd-925bac801c6a",
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
              "id": "48c032ad-7548-4523-8bb0-d13298bd9029"
            }
          ]
        },
        {
          "id": "125b077c-2cab-4108-b05c-8fd5031c9486",
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
              "id": "1f157cc6-25ce-477e-b98e-acbde4132cd8"
            }
          ]
        },
        {
          "id": "7a20746e-e809-42ab-8e95-42a15f00d8cf",
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
              "id": "6345be66-5b85-4788-a7a3-fc5436dacb4d"
            }
          ]
        },
        {
          "id": "7722dea5-a514-4ec8-8a15-c3951faf360e",
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
              "id": "5a8157d2-7af1-4875-bee3-2a8d6381f936"
            }
          ]
        },
        {
          "id": "c1eaead8-88cd-4066-bf46-dd356db545c7",
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
              "id": "692bfd26-e05e-4a12-a3cc-aeb41e0b1bfc"
            }
          ]
        },
        {
          "id": "2632a22c-ff03-444e-89ad-17b3c8e5aebd",
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
              "id": "c5c9f179-3156-4760-b0b1-121dfd6ef147"
            }
          ]
        },
        {
          "id": "ead719f8-9b82-4740-857b-96489211675f",
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
              "id": "9b3bb4ea-f8fb-412a-b801-631af2274817"
            }
          ]
        },
        {
          "id": "0853f177-3483-4a5c-adab-0babe2fdfb56",
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
              "id": "a3989a4d-3f49-4a9d-af06-5cac76699dd8"
            }
          ]
        },
        {
          "id": "a2c3ab9c-60ea-43a2-a680-03aad0cb7220",
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
              "id": "77e87783-b8a4-414e-9ebe-e538278afc82"
            }
          ]
        },
        {
          "id": "8a10a84c-9aec-4b3b-bca8-f1a6398644a8",
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
              "id": "51ddc8b6-0fcb-4f07-b4df-8515a2a7c1ee"
            }
          ]
        },
        {
          "id": "df1a41f4-9768-412f-8a43-39e7b342c977",
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
              "id": "0dc23b66-0acc-45e5-a3ad-e2f427565ccc"
            }
          ]
        },
        {
          "id": "6ae7164e-246b-48c1-ba4b-075bb74805e2",
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
              "id": "a6e1e697-5baa-4ce6-9871-b673042e2880"
            }
          ]
        },
        {
          "id": "4f912bcd-326b-47c2-9d36-0ccd720571a1",
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
              "id": "d559ead4-dbd3-4ba9-a2da-67b719eed7b3"
            }
          ]
        },
        {
          "id": "3c59f086-f128-4584-b0c7-b333be9cff51",
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
              "id": "68d67822-d015-4b49-99ac-1070396952b5"
            }
          ]
        },
        {
          "id": "6a762f02-af05-4d36-bb3a-d0826782fe8d",
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
              "id": "65c7c95b-5c2d-437d-9c1b-55c900377dde"
            }
          ]
        },
        {
          "id": "8726f4dc-d0d6-4c43-97a8-6bd81e90ffe3",
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
              "id": "cb68780c-656c-4c9c-8267-4c1ced6205f5"
            }
          ]
        },
        {
          "id": "a0b4ee2e-2b01-4464-9465-58596fc25e26",
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
              "id": "2c0dfc2e-9182-457f-bb1a-0bafab1e28ab"
            }
          ]
        },
        {
          "id": "cb6a292c-be16-48e5-9b2b-725584cdd91b",
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
              "id": "76723dff-cb30-4051-8a1e-c7f1e4b4f237"
            }
          ]
        },
        {
          "id": "1c283017-9917-4561-abd8-a3e3932e55e2",
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
              "id": "a3c944b2-91f9-465c-8807-4e87591c1d20"
            }
          ]
        },
        {
          "id": "9945cbb8-dc95-49a4-a94c-1b7c5d490ff3",
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
              "id": "ba970d9f-7cb4-4540-84a6-e3792ceb5421"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods",
      "item": [
        {
          "id": "fec9b367-5cae-4661-9a7e-a0fcdf0502ab",
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
              "id": "386b61f1-db69-4fba-add6-0ba1146a9cb0"
            }
          ]
        },
        {
          "id": "96556919-50b4-4745-89a5-82a0a8856af5",
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
              "id": "0cfc1c50-8f2f-4507-893d-aa62c642cf10"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities",
      "item": [
        {
          "id": "e0910ab3-1c46-4b74-9800-def1dd74d697",
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
              "id": "c0e312aa-4816-434d-a189-2f6f14d43100"
            }
          ]
        }
      ]
    },
    {
      "name": "Activities.json",
      "item": [
        {
          "id": "14d0076d-5016-47ad-a41c-b41245048249",
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
              "id": "c9c8383a-405c-450c-be88-c10f1a479e5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Foods.json",
      "item": [
        {
          "id": "0314765d-5a0a-4c04-a677-572b77f0f9c9",
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
              "id": "6a51258d-38ef-4f89-8917-5dcbda74aff0"
            }
          ]
        }
      ]
    }
  ]
}