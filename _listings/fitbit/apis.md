---
name: Fitbit
x-slug: fitbit
description: Find your fit with Fitbits family of fitness products that help you stay
  motivated and improve your health by tracking your activity, exercise, food, weight
  and sleep.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
x-kinRank: "9"
x-alexaRank: "2266"
tags: Fitbit
created: "2018-05-25"
modified: "2018-05-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitbit Get User Collection Path Apisubscriptions.json
  x-api-slug: fitbit
  description: Get a list of user's subscriptions for your application in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions.json
  tags: User,-collection-pathapiSubscriptions.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptions-json-get-openapi.md
- name: Fitbit Delete User Collection Path Apisubscriptions Subscription .json
  x-api-slug: fitbit
  description: Delete a subscription for the user and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions/{subscription-id}.json
  tags: User,-collection-pathapiSubscriptions,Subscription-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionid-json-delete-openapi.md
- name: Fitbit Post User Collection Path Apisubscriptions Subscription .json
  x-api-slug: fitbit
  description: Add a subscription for the user to get notifications and get a response
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-{collection-path}apiSubscriptions/{subscription-id}.json
  tags: User,-collection-pathapiSubscriptions,Subscription-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usercollectionpathapisubscriptionssubscriptionid-json-post-openapi.md
- name: Fitbit Get User Friends Invitations.json
  x-api-slug: fitbit
  description: Retrieve the list of invites to become freinds for a user in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/friends/invitations.json
  tags: User,-,Friends,Invitations.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsinvitations-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsinvitations-json-get-openapi.md
- name: Fitbit Get Foods Units.json
  x-api-slug: fitbit
  description: Get list of all valid Fitbit food units in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods/units.json
  tags: Foods,Units.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsunits-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsunits-json-get-openapi.md
- name: Fitbit Get Foods Food .json
  x-api-slug: fitbit
  description: Get the details of a specific food in Fitbit Food database (or private
    food for the user) in the format requested. Note, that nutritional values currently
    included in response only for the private foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods/{food-id}.json
  tags: Foods,Food-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsfoodid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foodsfoodid-json-get-openapi.md
- name: Fitbit Get Activities .json
  x-api-slug: fitbit
  description: Get the details of a specific activity in Fitbit activities database
    in the format requested. If activity has levels, also get list of activity level
    details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//activities/{id}.json
  tags: Activities,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activitiesid-json-get-openapi.md
- name: Fitbit Get Activities.json
  x-api-slug: fitbit
  description: Get a tree of all valid Fitbit public activities from the activities
    catalog as well as private custom activities the user created in the format requested.
    If activity has levels, also get a list of activity level details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//activities.json
  tags: Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activities-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/activities-json-get-openapi.md
- name: Fitbit Get User Devices.json
  x-api-slug: fitbit
  description: Retrieve the list of Fitbit devices for a user in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/devices.json
  tags: User,-,Devices.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userdevices-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userdevices-json-get-openapi.md
- name: Fitbit Post User Foods Log Goal.json
  x-api-slug: fitbit
  description: Update (create) a user's daily calorie consumption goal or Food Plan
    and get a response in the format requested. Food Plan could not be created unless
    user already has active goal (Update-Weight-Goal). Depending on the weight goal
    setup only either MAINTENANCE (in case start weight is close to target weight
    or smaller) or one of the four other "lose" food plans could be created via intensity
    POST parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/goal.json
  tags: User,-,Foods,Log,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoal-json-post-openapi.md
- name: Fitbit Get User Foods Log Goal.json
  x-api-slug: fitbit
  description: Get a user's current daily calorie consumption goal and/or Food Plan
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/goal.json
  tags: User,-,Foods,Log,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodsloggoal-json-get-openapi.md
- name: Fitbit Get User Meals.json
  x-api-slug: fitbit
  description: Get a list of meals user created in his food log in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/meals.json
  tags: User,-,Meals.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usermeals-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usermeals-json-get-openapi.md
- name: Fitbit Post Foods.json
  x-api-slug: fitbit
  description: Create new private food for a user and get a response in a format requested.
    Created private food could be found in results of Search Foods call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//foods.json
  tags: Foods.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foods-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/foods-json-post-openapi.md
- name: Fitbit Delete User Foods Log Water Water Log .json
  x-api-slug: fitbit
  description: Delete user's water log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water/{water-log-id}.json
  tags: User,-,Foods,Log,Water,Water-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-openapi.md
- name: Fitbit Post User Foods Log Water.json
  x-api-slug: fitbit
  description: Create log entry for a water using units in the unit system that corresponds
    to the Accept-Language header provided (or waterUnit) and get a response in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water.json
  tags: User,-,Foods,Log,Water.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwater-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwater-json-post-openapi.md
- name: Fitbit Get User Foods Log Water Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's water log entries for a given day
    in the format requested using units in the unit system which corresponds to the
    Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/water/date/{date}.json
  tags: User,-,Foods,Log,Water,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-openapi.md
- name: Fitbit Delete User Foods Log Favorite .json
  x-api-slug: fitbit
  description: Delete the food with the given id from user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite/{id}.json
  tags: User,-,Foods,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-openapi.md
- name: Fitbit Post User Foods Log Favorite .json
  x-api-slug: fitbit
  description: Add the food with the given id to user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite/{id}.json
  tags: User,-,Foods,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavoriteid-json-post-openapi.md
- name: Fitbit Get User Activities Goals Weekly.json
  x-api-slug: fitbit
  description: Get a user's current weekly activity goals in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/weekly.json
  tags: User,-,Activities,Goals,Weekly.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-openapi.md
- name: Fitbit Get User Activities Goals Daily.json
  x-api-slug: fitbit
  description: Get a user's current daily activity goals in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/daily.json
  tags: User,-,Activities,Goals,Daily.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-openapi.md
- name: Fitbit Delete User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit Post User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit Get User Foods Log Favorite.json
  x-api-slug: fitbit
  description: Get a list of a user's favorite foods in the format requested. A user
    marks a food as favorite on the user's Food Tab tab. A favorite food in the list
    provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/favorite.json
  tags: User,-,Foods,Log,Favorite.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfavorite-json-get-openapi.md
- name: Fitbit Get User Foods Log Frequent.json
  x-api-slug: fitbit
  description: Get a list of a user's frequent foods in the format requested. A frequent
    food in the list provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/frequent.json
  tags: User,-,Foods,Log,Frequent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfrequent-json-get-openapi.md
- name: Fitbit Get User Foods Log Recent.json
  x-api-slug: fitbit
  description: Get a list of a user's recent foods in the format requested. A recent
    food provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/recent.json
  tags: User,-,Foods,Log,Recent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogrecent-json-get-openapi.md
- name: Fitbit Get User Activities Favorite.json
  x-api-slug: fitbit
  description: Get a list of a user's favorite activities in the format requested.
    A user marks an activity as favorite on the user's Activities Tab. The activity
    ids in the list can be used to create a new activity log entry via the Log Activity.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/favorite.json
  tags: User,-,Activities,Favorite.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfavorite-json-get-openapi.md
- name: Fitbit Get User Activities Frequent.json
  x-api-slug: fitbit
  description: Get a list of a user's frequent activities in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. A frequent activity record contains the distance and duration values
    recorded the last time the activity was logged. The record retrieved can therefore
    be used to log the activity via the Log Activity with the same or adjusted values
    for distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/frequent.json
  tags: User,-,Activities,Frequent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesfrequent-json-get-openapi.md
- name: Fitbit Get User Activities Recent.json
  x-api-slug: fitbit
  description: Get a list of a user's recent activities in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
    A recent activity record contains the distance and duration values recorded the
    last time the activity was logged. The record retrieved can therefore be used
    to log the activity via the Log Activity with the same or adjusted values for
    distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/recent.json
  tags: User,-,Activities,Recent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesrecent-json-get-openapi.md
- name: Fitbit Get User User Sleep Minutesasleep Date Start Date Or End Date End Date
    Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/sleep/minutesAsleep/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Sleep,MinutesAsleep,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepminutesasleepdatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepminutesasleepdatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit Get User User Foods Log Caloriesin Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/foods/log/caloriesIn/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Foods,Log,CaloriesIn,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit Post User Body Log Fat Goal.json
  x-api-slug: fitbit
  description: Create or updates user's fat goal and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/goal.json
  tags: User,-,Body,Log,Fat,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoal-json-post-openapi.md
- name: Fitbit Get User Body Log Fat Goal.json
  x-api-slug: fitbit
  description: Get a user's current fat goal in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/goal.json
  tags: User,-,Body,Log,Fat,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatgoal-json-get-openapi.md
- name: Fitbit Post User Body Log Weight Goal.json
  x-api-slug: fitbit
  description: Create or update user's weight goal using units in the unit system
    that corresponds to the Accept-Language header provided and get a response in
    the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/goal.json
  tags: User,-,Body,Log,Weight,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoal-json-post-openapi.md
- name: Fitbit Get User Body Log Weight Goal.json
  x-api-slug: fitbit
  description: Get a user's current weight goal using units in the unit system that
    corresponds to the Accept-Language header provided in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/goal.json
  tags: User,-,Body,Log,Weight,Goal.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightgoal-json-get-openapi.md
- name: Fitbit Delete User Body Log Fat Body Fat Log .json
  x-api-slug: fitbit
  description: Delete user's body fat log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/{body-fat-log-id}.json
  tags: User,-,Body,Log,Fat,Body-fat-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-openapi.md
- name: Fitbit Delete User Body Log Fat Body Weight Log .json
  x-api-slug: fitbit
  description: Delete user's body weight log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/{body-weight-log-id}.json
  tags: User,-,Body,Log,Fat,Body-weight-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-openapi.md
- name: Fitbit Post User Body Log Fat.json
  x-api-slug: fitbit
  description: Create log entry for a body fat and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat.json
  tags: User,-,Body,Log,Fat.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfat-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfat-json-post-openapi.md
- name: Fitbit Post User Body Log Weight.json
  x-api-slug: fitbit
  description: Create log entry for a body weight using units in the unit system that
    corresponds to the Accept-Language header provided and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight.json
  tags: User,-,Body,Log,Weight.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweight-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweight-json-post-openapi.md
- name: Fitbit Post User Body.json
  x-api-slug: fitbit
  description: Log body measurements using units in the unit system that corresponds
    to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body.json
  tags: User,-,Body.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbody-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbody-json-post-openapi.md
- name: Fitbit Get User User Body Weight Date Start Date Or End Date End Date Or Period
    .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/body/weight/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Body,Weight,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodyweightdatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodyweightdatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit Get User User Activities Calories Date Start Date Or End Date End Date
    Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/calories/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Activities,Calories,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit Delete User Bp Bp Log .json
  x-api-slug: fitbit
  description: Delete user's blood pressure log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp/{bp-log-id}.json
  tags: User,-,Bp,Bp-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpbplogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpbplogid-json-delete-openapi.md
- name: Fitbit Delete User Heart Heart Log .json
  x-api-slug: fitbit
  description: Delete user's heart rate log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart/{heart-log-id}.json
  tags: User,-,Heart,Heart-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartheartlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartheartlogid-json-delete-openapi.md
- name: Fitbit Delete User Sleep Sleep Log .json
  x-api-slug: fitbit
  description: Delete user's sleep log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/sleep/{sleep-log-id}.json
  tags: User,-,Sleep,Sleep-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepsleeplogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleepsleeplogid-json-delete-openapi.md
- name: Fitbit Get User User Badges.json
  x-api-slug: fitbit
  description: Get user's badges in the format requested. Response includes all badges
    for the user as seen on the Fitbit website badge locker (both activity and weight
    related). We return weight and distance badges based on the user's unit profile
    preference as on the website.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/badges.json
  tags: User,User-id,Badges.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbadges-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbadges-json-get-openapi.md
- name: Fitbit Delete User Activities Activity Log .json
  x-api-slug: fitbit
  description: Delete user's activity log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/{activity-log-id}.json
  tags: User,-,Activities,Activity-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-openapi.md
- name: Fitbit Delete User Foods Log Food Log .json
  x-api-slug: fitbit
  description: Delete the user's food log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log/{food-log-id}.json
  tags: User,-,Foods,Log,Food-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-openapi.md
- name: Fitbit Post User Glucose.json
  x-api-slug: fitbit
  description: Create log entry for a blood glucose measurement and/or HbA1c using
    units in the unit system which corresponds to the Accept-Language header provided
    and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/glucose.json
  tags: User,-,Glucose.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucose-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucose-json-post-openapi.md
- name: Fitbit Post User Bp.json
  x-api-slug: fitbit
  description: Create log entry for a blood pressure measurement and get a response
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp.json
  tags: User,-,Bp.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbp-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbp-json-post-openapi.md
- name: Fitbit Post User Heart.json
  x-api-slug: fitbit
  description: Create log entry for a heart rate measurement and get a response in
    the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart.json
  tags: User,-,Heart.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheart-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheart-json-post-openapi.md
- name: Fitbit Post User Sleep.json
  x-api-slug: fitbit
  description: Create log entry for a sleep and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/sleep.json
  tags: User,-,Sleep.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleep-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/usersleep-json-post-openapi.md
- name: Fitbit Post User Foods Log.json
  x-api-slug: fitbit
  description: Create log entry for a food. You need to select one of the unit ids
    to create a food log entry. It is possible to fetch unit ids allowed for specific
    food via previous calls to endpoints that retrieve food lists of the user. Each
    unit id maps to a unit in the list returned via the Get Food Units API call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/foods/log.json
  tags: User,-,Foods,Log.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslog-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfoodslog-json-post-openapi.md
- name: Fitbit Get User Activities.json
  x-api-slug: fitbit
  description: Get user's activity statistics in the format requested using units
    in the unit system which corresponds to the Accept-Language header provided. Response
    contains both lifetime statistics from the tracker device and total numbers including
    the manual activity log entries as seen on the Fitbit website dashboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivities-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivities-json-get-openapi.md
- name: Fitbit Post User Activities.json
  x-api-slug: fitbit
  description: Create log entry for an activity using units in the unit system which
    corresponds to the Accept-Language header provided (or using optional custom distanceUnit).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivities-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useractivities-json-post-openapi.md
- name: Fitbit Get User Friends Leaderboard.json
  x-api-slug: fitbit
  description: Get a leaderboard of user's friends progress in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. Authorized user himself is also included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/friends/leaderboard.json
  tags: User,-,Friends,Leaderboard.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsleaderboard-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userfriendsleaderboard-json-get-openapi.md
- name: Fitbit Get User User Friends.json
  x-api-slug: fitbit
  description: Get user's friends in the format requested using units in the unit
    system which corresponds to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/friends.json
  tags: User,User-id,Friends.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfriends-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfriends-json-get-openapi.md
- name: Fitbit Get User Glucose Date Date .json
  x-api-slug: fitbit
  description: Get a list of user's blood glucose and HbA1C measurements for a given
    day in the format requested using units in the unit system which corresponds to
    the Accept-Language header provided. Glucose measurement log entries are available
    only to authorized user. We always include all glucose trackers in the response
    body (with zero glucose value for the days with no measurements) to allow to seamlessly
    fetch a list of all additional user created custom trackers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/glucose/date/{date}.json
  tags: User,-,Glucose,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosedatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userglucosedatedate-json-get-openapi.md
- name: Fitbit Get User Bp Date Date .json
  x-api-slug: fitbit
  description: Get an average value and a list of user's blood pressure log entries
    for a given day in the format requested. Blood pressure log entries are available
    only to authorized user. Blood pressure log entries in response are sorted exactly
    the same as they are presented on the Fitbit website.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/bp/date/{date}.json
  tags: User,-,Bp,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbpdatedate-json-get-openapi.md
- name: Fitbit Get User Heart Date Date .json
  x-api-slug: fitbit
  description: Get an average values and a list of user's heart rate log entries for
    a given day in the format requested. Heart rate data available only to the authorized
    user. Heart rate log entries in response are sorted exactly the same as they are
    presented on the Fitbit website. We always include all heart rate trackers in
    the "average" section of the response body (with zero average values for the days
    with no measurements) to allow to seamlessly fetch a list of all additional user
    created custom trackers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/heart/date/{date}.json
  tags: User,-,Heart,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userheartdatedate-json-get-openapi.md
- name: Fitbit Get User User Sleep Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's sleep log entries for a given day
    in the format requested. Endpoint returns summary for all sleep log entries for
    the given day (including naps). If you need data only for the main sleep you can
    fetch entry with "isMainSleep" = true or use Get-Time-Series calls.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/sleep/date/{date}.json
  tags: User,User-id,Sleep,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridsleepdatedate-json-get-openapi.md
- name: Fitbit Get User User Foods Log Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's food log entries for a given day
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/foods/log/date/{date}.json
  tags: User,User-id,Foods,Log,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-openapi.md
- name: Fitbit Get User User Activities Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's activities and activity log entries
    for a given day in the format requested using units in the unit system which corresponds
    to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/date/{date}.json
  tags: User,User-id,Activities,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-openapi.md
- name: Fitbit Get User Body Log Fat Date Date .json
  x-api-slug: fitbit
  description: Get a list of all user's body fat log entries for a given day in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/fat/date/{date}.json
  tags: User,-,Body,Log,Fat,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogfatdatedate-json-get-openapi.md
- name: Fitbit Get User Body Log Weight Date Date .json
  x-api-slug: fitbit
  description: Get a list of all user's body weight log entries for a given day in
    the format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/body/log/weight/date/{date}.json
  tags: User,-,Body,Log,Weight,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userbodylogweightdatedate-json-get-openapi.md
- name: Fitbit Get User User Body Date Date .json
  x-api-slug: fitbit
  description: Get a summary of a user's body measurements for a given day in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/body/date/{date}.json
  tags: User,User-id,Body,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodydatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridbodydatedate-json-get-openapi.md
- name: Fitbit Post User Profile.json
  x-api-slug: fitbit
  description: Update user's profile using units in the unit system that corresponds
    to the Accept-Language header provided and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/profile.json
  tags: User,-,Profile.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userprofile-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/userprofile-json-post-openapi.md
- name: Fitbit Get User User Profile.json
  x-api-slug: fitbit
  description: Get user's profile in the format requested using units in the unit
    system which corresponds to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/profile.json
  tags: User,User-id,Profile.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridprofile-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/useruseridprofile-json-get-openapi.md
- name: Fitbit
  x-api-slug: fitbit
  description: Find your fit with Fitbits family of fitness products that help you
    stay motivated and improve your health by tracking your activity, exercise, food,
    weight and sleep.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://dev.fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Fitbit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/fitbit/master/_listings/fitbit/openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://www.fitbit.com/apis.json
- type: x-apigee-console
  url: https://wiki.fitbit.com/display/API/API+Explorer
- type: x-blog
  url: http://blog.fitbit.com
- type: x-blog-rss
  url: http://blog.fitbit.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/fitbit
- type: x-crunchbase
  url: https://crunchbase.com/organization/fitbit
- type: x-email
  url: privacy@fitbit.com
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