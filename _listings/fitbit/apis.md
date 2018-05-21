---
name: Fitbit
x-slug: fitbit
description: Fitbit Inc. is a company headquartered in San Francisco, California,
  United States. Founded and managed by James Park and Eric Friedman, the company
  is known for its product of the same name, the Fitbit Tracker, a wireless-enabled
  wearable device that measures data such as the number of steps walked, quality of
  sleep, and other personal metrics. The average price of the Fitbit is between $60&ndash;$130,
  depending on the model. However, data cannot be downloaded off the fitbit website
  unless one pays the premium membership price of $49 per year. Intraday data analysis
  cannot be downloaded at all.
image: https://avatars2.githubusercontent.com/u/1039877?v=4
x-kinRank: "9"
x-alexaRank: ""
tags: Fitbit
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitbit Get User Collection Path Apisubscriptions.json
  x-api-slug: fitbit
  description: Get a list of user's subscriptions for your application in the format
    requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions.json
  tags: User,-collection-pathapiSubscriptions.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionsjson-get-openapi.md
- name: Fitbit Delete User Collection Path Apisubscriptions Subscription .json
  x-api-slug: fitbit
  description: Delete a subscription for the user and get a response in the format
    requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions/{subscription-id}.json
  tags: User,-collection-pathapiSubscriptions,Subscription-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionidjson-delete-openapi.md
- name: Fitbit Post User Collection Path Apisubscriptions Subscription .json
  x-api-slug: fitbit
  description: Add a subscription for the user to get notifications and get a response
    in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions/{subscription-id}.json
  tags: User,-collection-pathapiSubscriptions,Subscription-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionidjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionidjson-post-openapi.md
- name: Fitbit Get User Friends Invitations.json
  x-api-slug: fitbit
  description: Retrieve the list of invites to become freinds for a user in the format
    requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/friends/invitations.json
  tags: User,-,Friends,Invitations.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsinvitationsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsinvitationsjson-get-openapi.md
- name: Fitbit Get Foods Units.json
  x-api-slug: fitbit
  description: Get list of all valid Fitbit food units in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods/units.json
  tags: Foods,Units.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsunitsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsunitsjson-get-openapi.md
- name: Fitbit Get Foods Food .json
  x-api-slug: fitbit
  description: Get the details of a specific food in Fitbit Food database (or private
    food for the user) in the format requested. Note, that nutritional values currently
    included in response only for the private foods.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods/{food-id}.json
  tags: Foods,Food-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsfoodidjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsfoodidjson-get-openapi.md
- name: Fitbit Get Activities .json
  x-api-slug: fitbit
  description: Get the details of a specific activity in Fitbit activities database
    in the format requested. If activity has levels, also get list of activity level
    details.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//activities/{id}.json
  tags: Activities,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesidjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesidjson-get-openapi.md
- name: Fitbit Get Activities.json
  x-api-slug: fitbit
  description: Get a tree of all valid Fitbit public activities from the activities
    catalog as well as private custom activities the user created in the format requested.
    If activity has levels, also get a list of activity level details.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//activities.json
  tags: Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesjson-get-openapi.md
- name: Fitbit Get User Devices.json
  x-api-slug: fitbit
  description: Retrieve the list of Fitbit devices for a user in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/devices.json
  tags: User,-,Devices.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userdevicesjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userdevicesjson-get-openapi.md
- name: Fitbit Post User Foods Log Goal.json
  x-api-slug: fitbit
  description: Update (create) a user's daily calorie consumption goal or Food Plan
    and get a response in the format requested. Food Plan could not be created unless
    user already has active goal (Update-Weight-Goal). Depending on the weight goal
    setup only either MAINTENANCE (in case start weight is close to target weight
    or smaller) or one of the four other "lose" food plans could be created via intensity
    POST parameter.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/goal.json
  tags: User,-,Foods,Log,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoaljson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoaljson-post-openapi.md
- name: Fitbit Get User Foods Log Goal.json
  x-api-slug: fitbit
  description: Get a user's current daily calorie consumption goal and/or Food Plan
    in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/goal.json
  tags: User,-,Foods,Log,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoaljson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoaljson-get-openapi.md
- name: Fitbit Get User Meals.json
  x-api-slug: fitbit
  description: Get a list of meals user created in his food log in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/meals.json
  tags: User,-,Meals.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usermealsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usermealsjson-get-openapi.md
- name: Fitbit Post Foods.json
  x-api-slug: fitbit
  description: Create new private food for a user and get a response in a format requested.
    Created private food could be found in results of Search Foods call.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods.json
  tags: Foods.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsjson-post-openapi.md
- name: Fitbit Delete User Foods Log Water Water Log .json
  x-api-slug: fitbit
  description: Delete user's water log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water/{water-log-id}.json
  tags: User,-,Foods,Log,Water,Water-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterwaterlogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterwaterlogidjson-delete-openapi.md
- name: Fitbit Post User Foods Log Water.json
  x-api-slug: fitbit
  description: Create log entry for a water using units in the unit system that corresponds
    to the Accept-Language header provided (or waterUnit) and get a response in the
    format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water.json
  tags: User,-,Foods,Log,Water.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterjson-post-openapi.md
- name: Fitbit Get User Foods Log Water Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's water log entries for a given day
    in the format requested using units in the unit system which corresponds to the
    Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water/date/{date}.json
  tags: User,-,Foods,Log,Water,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterdatedatejson-get-openapi.md
- name: Fitbit Delete User Foods Log Favorite .json
  x-api-slug: fitbit
  description: Delete the food with the given id from user's list of favorite foods.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite/{id}.json
  tags: User,-,Foods,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteidjson-delete-openapi.md
- name: Fitbit Post User Foods Log Favorite .json
  x-api-slug: fitbit
  description: Add the food with the given id to user's list of favorite foods.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite/{id}.json
  tags: User,-,Foods,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteidjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteidjson-post-openapi.md
- name: Fitbit Get User Activities Goals Weekly.json
  x-api-slug: fitbit
  description: Get a user's current weekly activity goals in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/weekly.json
  tags: User,-,Activities,Goals,Weekly.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsweeklyjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsweeklyjson-get-openapi.md
- name: Fitbit Get User Activities Goals Daily.json
  x-api-slug: fitbit
  description: Get a user's current daily activity goals in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/daily.json
  tags: User,-,Activities,Goals,Daily.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsdailyjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsdailyjson-get-openapi.md
- name: Fitbit Delete User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteidjson-delete-openapi.md
- name: Fitbit Post User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Adds the activity with the given id to user's list of favorite activities.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteidjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteidjson-post-openapi.md
- name: Fitbit Get User Foods Log Favorite.json
  x-api-slug: fitbit
  description: Get a list of a user's favorite foods in the format requested. A user
    marks a food as favorite on the user's Food Tab tab. A favorite food in the list
    provides a quick way to log the food via the Log Food endpoint.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite.json
  tags: User,-,Foods,Log,Favorite.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoritejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoritejson-get-openapi.md
- name: Fitbit Get User Foods Log Frequent.json
  x-api-slug: fitbit
  description: Get a list of a user's frequent foods in the format requested. A frequent
    food in the list provides a quick way to log the food via the Log Food endpoint.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/frequent.json
  tags: User,-,Foods,Log,Frequent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfrequentjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfrequentjson-get-openapi.md
- name: Fitbit Get User Foods Log Recent.json
  x-api-slug: fitbit
  description: Get a list of a user's recent foods in the format requested. A recent
    food provides a quick way to log the food via the Log Food endpoint.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/recent.json
  tags: User,-,Foods,Log,Recent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogrecentjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogrecentjson-get-openapi.md
- name: Fitbit Get User Activities Favorite.json
  x-api-slug: fitbit
  description: Get a list of a user's favorite activities in the format requested.
    A user marks an activity as favorite on the user's Activities Tab. The activity
    ids in the list can be used to create a new activity log entry via the Log Activity.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/favorite.json
  tags: User,-,Activities,Favorite.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfavoritejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfavoritejson-get-openapi.md
- name: Fitbit Get User Activities Frequent.json
  x-api-slug: fitbit
  description: Get a list of a user's frequent activities in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. A frequent activity record contains the distance and duration values
    recorded the last time the activity was logged. The record retrieved can therefore
    be used to log the activity via the Log Activity with the same or adjusted values
    for distance and duration.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/frequent.json
  tags: User,-,Activities,Frequent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfrequentjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfrequentjson-get-openapi.md
- name: Fitbit Get User Activities Recent.json
  x-api-slug: fitbit
  description: Get a list of a user's recent activities in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
    A recent activity record contains the distance and duration values recorded the
    last time the activity was logged. The record retrieved can therefore be used
    to log the activity via the Log Activity with the same or adjusted values for
    distance and duration.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/recent.json
  tags: User,-,Activities,Recent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesrecentjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesrecentjson-get-openapi.md
- name: Fitbit Get User User Sleep Minutesasleep Date Start Date Or End Date End Date
    Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/sleep/minutesAsleep/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Sleep,MinutesAsleep,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepminutesasleepdatestartdateorenddateenddateorperiodjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepminutesasleepdatestartdateorenddateenddateorperiodjson-get-openapi.md
- name: Fitbit Get User User Foods Log Caloriesin Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/foods/log/caloriesIn/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Foods,Log,CaloriesIn,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiodjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiodjson-get-openapi.md
- name: Fitbit Post User Body Log Fat Goal.json
  x-api-slug: fitbit
  description: Create or updates user's fat goal and get a response in the format
    requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/goal.json
  tags: User,-,Body,Log,Fat,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoaljson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoaljson-post-openapi.md
- name: Fitbit Get User Body Log Fat Goal.json
  x-api-slug: fitbit
  description: Get a user's current fat goal in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/goal.json
  tags: User,-,Body,Log,Fat,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoaljson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoaljson-get-openapi.md
- name: Fitbit Post User Body Log Weight Goal.json
  x-api-slug: fitbit
  description: Create or update user's weight goal using units in the unit system
    that corresponds to the Accept-Language header provided and get a response in
    the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/goal.json
  tags: User,-,Body,Log,Weight,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoaljson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoaljson-post-openapi.md
- name: Fitbit Get User Body Log Weight Goal.json
  x-api-slug: fitbit
  description: Get a user's current weight goal using units in the unit system that
    corresponds to the Accept-Language header provided in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/goal.json
  tags: User,-,Body,Log,Weight,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoaljson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoaljson-get-openapi.md
- name: Fitbit Delete User Body Log Fat Body Fat Log .json
  x-api-slug: fitbit
  description: Delete user's body fat log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/{body-fat-log-id}.json
  tags: User,-,Body,Log,Fat,Body-fat-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyfatlogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyfatlogidjson-delete-openapi.md
- name: Fitbit Delete User Body Log Fat Body Weight Log .json
  x-api-slug: fitbit
  description: Delete user's body weight log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/{body-weight-log-id}.json
  tags: User,-,Body,Log,Fat,Body-weight-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyweightlogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyweightlogidjson-delete-openapi.md
- name: Fitbit Post User Body Log Fat.json
  x-api-slug: fitbit
  description: Create log entry for a body fat and get a response in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat.json
  tags: User,-,Body,Log,Fat.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatjson-post-openapi.md
- name: Fitbit Post User Body Log Weight.json
  x-api-slug: fitbit
  description: Create log entry for a body weight using units in the unit system that
    corresponds to the Accept-Language header provided and get a response in the format
    requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight.json
  tags: User,-,Body,Log,Weight.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightjson-post-openapi.md
- name: Fitbit Post User Body.json
  x-api-slug: fitbit
  description: Log body measurements using units in the unit system that corresponds
    to the Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body.json
  tags: User,-,Body.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodyjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodyjson-post-openapi.md
- name: Fitbit Get User User Body Weight Date Start Date Or End Date End Date Or Period
    .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/body/weight/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Body,Weight,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodyweightdatestartdateorenddateenddateorperiodjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodyweightdatestartdateorenddateenddateorperiodjson-get-openapi.md
- name: Fitbit Get User User Activities Calories Date Start Date Or End Date End Date
    Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/calories/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Activities,Calories,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiodjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiodjson-get-openapi.md
- name: Fitbit Delete User Bp Bp Log .json
  x-api-slug: fitbit
  description: Delete user's blood pressure log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp/{bp-log-id}.json
  tags: User,-,Bp,Bp-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpbplogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpbplogidjson-delete-openapi.md
- name: Fitbit Delete User Heart Heart Log .json
  x-api-slug: fitbit
  description: Delete user's heart rate log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart/{heart-log-id}.json
  tags: User,-,Heart,Heart-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartheartlogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartheartlogidjson-delete-openapi.md
- name: Fitbit Delete User Sleep Sleep Log .json
  x-api-slug: fitbit
  description: Delete user's sleep log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/sleep/{sleep-log-id}.json
  tags: User,-,Sleep,Sleep-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepsleeplogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepsleeplogidjson-delete-openapi.md
- name: Fitbit Get User User Badges.json
  x-api-slug: fitbit
  description: Get user's badges in the format requested. Response includes all badges
    for the user as seen on the Fitbit website badge locker (both activity and weight
    related). We return weight and distance badges based on the user's unit profile
    preference as on the website.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/badges.json
  tags: User,User-id,Badges.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbadgesjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbadgesjson-get-openapi.md
- name: Fitbit Delete User Activities Activity Log .json
  x-api-slug: fitbit
  description: Delete user's activity log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/{activity-log-id}.json
  tags: User,-,Activities,Activity-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesactivitylogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesactivitylogidjson-delete-openapi.md
- name: Fitbit Delete User Foods Log Food Log .json
  x-api-slug: fitbit
  description: Delete the user's food log entry with the given id.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/{food-log-id}.json
  tags: User,-,Foods,Log,Food-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfoodlogidjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfoodlogidjson-delete-openapi.md
- name: Fitbit Post User Glucose.json
  x-api-slug: fitbit
  description: Create log entry for a blood glucose measurement and/or HbA1c using
    units in the unit system which corresponds to the Accept-Language header provided
    and get a response in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/glucose.json
  tags: User,-,Glucose.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosejson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosejson-post-openapi.md
- name: Fitbit Post User Bp.json
  x-api-slug: fitbit
  description: Create log entry for a blood pressure measurement and get a response
    in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp.json
  tags: User,-,Bp.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpjson-post-openapi.md
- name: Fitbit Post User Heart.json
  x-api-slug: fitbit
  description: Create log entry for a heart rate measurement and get a response in
    the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart.json
  tags: User,-,Heart.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartjson-post-openapi.md
- name: Fitbit Post User Sleep.json
  x-api-slug: fitbit
  description: Create log entry for a sleep and get a response in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/sleep.json
  tags: User,-,Sleep.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepjson-post-openapi.md
- name: Fitbit Post User Foods Log.json
  x-api-slug: fitbit
  description: Create log entry for a food. You need to select one of the unit ids
    to create a food log entry. It is possible to fetch unit ids allowed for specific
    food via previous calls to endpoints that retrieve food lists of the user. Each
    unit id maps to a unit in the list returned via the Get Food Units API call.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log.json
  tags: User,-,Foods,Log.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogjson-post-openapi.md
- name: Fitbit Get User Activities.json
  x-api-slug: fitbit
  description: Get user's activity statistics in the format requested using units
    in the unit system which corresponds to the Accept-Language header provided. Response
    contains both lifetime statistics from the tracker device and total numbers including
    the manual activity log entries as seen on the Fitbit website dashboard.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesjson-get-openapi.md
- name: Fitbit Post User Activities.json
  x-api-slug: fitbit
  description: Create log entry for an activity using units in the unit system which
    corresponds to the Accept-Language header provided (or using optional custom distanceUnit).
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesjson-post-openapi.md
- name: Fitbit Get User Friends Leaderboard.json
  x-api-slug: fitbit
  description: Get a leaderboard of user's friends progress in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. Authorized user himself is also included in the response.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/friends/leaderboard.json
  tags: User,-,Friends,Leaderboard.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsleaderboardjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsleaderboardjson-get-openapi.md
- name: Fitbit Get User User Friends.json
  x-api-slug: fitbit
  description: Get user's friends in the format requested using units in the unit
    system which corresponds to the Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/friends.json
  tags: User,User-id,Friends.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfriendsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfriendsjson-get-openapi.md
- name: Fitbit Get User Glucose Date Date .json
  x-api-slug: fitbit
  description: Get a list of user's blood glucose and HbA1C measurements for a given
    day in the format requested using units in the unit system which corresponds to
    the Accept-Language header provided. Glucose measurement log entries are available
    only to authorized user. We always include all glucose trackers in the response
    body (with zero glucose value for the days with no measurements) to allow to seamlessly
    fetch a list of all additional user created custom trackers.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/glucose/date/{date}.json
  tags: User,-,Glucose,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosedatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosedatedatejson-get-openapi.md
- name: Fitbit Get User Bp Date Date .json
  x-api-slug: fitbit
  description: Get an average value and a list of user's blood pressure log entries
    for a given day in the format requested. Blood pressure log entries are available
    only to authorized user. Blood pressure log entries in response are sorted exactly
    the same as they are presented on the Fitbit website.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp/date/{date}.json
  tags: User,-,Bp,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpdatedatejson-get-openapi.md
- name: Fitbit Get User Heart Date Date .json
  x-api-slug: fitbit
  description: Get an average values and a list of user's heart rate log entries for
    a given day in the format requested. Heart rate data available only to the authorized
    user. Heart rate log entries in response are sorted exactly the same as they are
    presented on the Fitbit website. We always include all heart rate trackers in
    the "average" section of the response body (with zero average values for the days
    with no measurements) to allow to seamlessly fetch a list of all additional user
    created custom trackers.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart/date/{date}.json
  tags: User,-,Heart,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartdatedatejson-get-openapi.md
- name: Fitbit Get User User Sleep Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's sleep log entries for a given day
    in the format requested. Endpoint returns summary for all sleep log entries for
    the given day (including naps). If you need data only for the main sleep you can
    fetch entry with "isMainSleep" = true or use Get-Time-Series calls.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/sleep/date/{date}.json
  tags: User,User-id,Sleep,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepdatedatejson-get-openapi.md
- name: Fitbit Get User User Foods Log Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's food log entries for a given day
    in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/foods/log/date/{date}.json
  tags: User,User-id,Foods,Log,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogdatedatejson-get-openapi.md
- name: Fitbit Get User User Activities Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's activities and activity log entries
    for a given day in the format requested using units in the unit system which corresponds
    to the Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/date/{date}.json
  tags: User,User-id,Activities,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiesdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiesdatedatejson-get-openapi.md
- name: Fitbit Get User Body Log Fat Date Date .json
  x-api-slug: fitbit
  description: Get a list of all user's body fat log entries for a given day in the
    format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/date/{date}.json
  tags: User,-,Body,Log,Fat,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatdatedatejson-get-openapi.md
- name: Fitbit Get User Body Log Weight Date Date .json
  x-api-slug: fitbit
  description: Get a list of all user's body weight log entries for a given day in
    the format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/date/{date}.json
  tags: User,-,Body,Log,Weight,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightdatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightdatedatejson-get-openapi.md
- name: Fitbit Get User User Body Date Date .json
  x-api-slug: fitbit
  description: Get a summary of a user's body measurements for a given day in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/body/date/{date}.json
  tags: User,User-id,Body,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodydatedatejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodydatedatejson-get-openapi.md
- name: Fitbit Post User Profile.json
  x-api-slug: fitbit
  description: Update user's profile using units in the unit system that corresponds
    to the Accept-Language header provided and get a response in the format requested.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/profile.json
  tags: User,-,Profile.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userprofilejson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userprofilejson-post-openapi.md
- name: Fitbit Get User User Profile.json
  x-api-slug: fitbit
  description: Get user's profile in the format requested using units in the unit
    system which corresponds to the Accept-Language header provided.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/profile.json
  tags: User,User-id,Profile.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridprofilejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridprofilejson-get-openapi.md
- name: Fitbit
  x-api-slug: fitbit
  description: Fitbit Inc. is a company headquartered in San Francisco, California,
    United States. Founded and managed by James Park and Eric Friedman, the company
    is known for its product of the same name, the Fitbit Tracker, a wireless-enabled
    wearable device that measures data such as the number of steps walked, quality
    of sleep, and other personal metrics. The average price of the Fitbit is between
    $60&ndash;$130, depending on the model. However, data cannot be downloaded off
    the fitbit website unless one pays the premium membership price of $49 per year.
    Intraday data analysis cannot be downloaded at all.
  image: https://avatars2.githubusercontent.com/u/1039877?v=4
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Fitbit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/openapi.md
x-common:
- type: x-apijson--authoritative
  url: https://www.fitbit.com/apis.json
- type: x-apigee-console
  url: https://wiki.fitbit.com/display/API/API+Explorer
- type: x-blog
  url: http://blog.fitbit.com
- type: x-blog-rss
  url: http://blog.fitbit.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/fitbit
- type: x-github
  url: https://github.com/fitbit
- type: x-rate-limits
  url: https://wiki.fitbit.com/display/API/Rate+Limit
- type: x-twitter
  url: https://twitter.com/fitbit
- type: x-website
  url: http://dev.fitbit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---