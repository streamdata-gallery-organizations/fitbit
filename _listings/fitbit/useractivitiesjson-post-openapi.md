---
swagger: "2.0"
x-collection-name: Fitbit
x-complete: 0
info:
  title: Fitbit Post User Activities.json
  description: Create log entry for an activity using units in the unit system which
    corresponds to the Accept-Language header provided (or using optional custom distanceUnit).
  version: 1.0.0
host: api.fitbit.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/-{collection-path}apiSubscriptions.json:
    get:
      summary: Get User Collection Path Apisubscriptions.json
      description: Get a list of user's subscriptions for your application in the
        format requested.
      operationId: getUserCollectionPathApisubscriptions.json
      x-api-path-slug: usercollectionpathapisubscriptionsjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - -collection-pathapiSubscriptions.json
  /user/-{collection-path}apiSubscriptions/{subscription-id}.json:
    delete:
      summary: Delete User Collection Path Apisubscriptions Subscription .json
      description: Delete a subscription for the user and get a response in the format
        requested.
      operationId: deleteUserCollectionPathApisubscriptionsSubscription.json
      x-api-path-slug: usercollectionpathapisubscriptionssubscriptionidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - -collection-pathapiSubscriptions
      - Subscription-id.json
    post:
      summary: Post User Collection Path Apisubscriptions Subscription .json
      description: Add a subscription for the user to get notifications and get a
        response in the format requested.
      operationId: postUserCollectionPathApisubscriptionsSubscription.json
      x-api-path-slug: usercollectionpathapisubscriptionssubscriptionidjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - -collection-pathapiSubscriptions
      - Subscription-id.json
  /user/-/friends/invitations.json:
    get:
      summary: Get User Friends Invitations.json
      description: Retrieve the list of invites to become freinds for a user in the
        format requested.
      operationId: getUserFriendsInvitations.json
      x-api-path-slug: userfriendsinvitationsjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Friends
      - Invitations.json
  /foods/units.json:
    get:
      summary: Get Foods Units.json
      description: Get list of all valid Fitbit food units in the format requested.
      operationId: getFoodsUnits.json
      x-api-path-slug: foodsunitsjson-get
      responses:
        200:
          description: OK
      tags:
      - Foods
      - Units.json
  /foods/{food-id}.json:
    get:
      summary: Get Foods Food .json
      description: Get the details of a specific food in Fitbit Food database (or
        private food for the user) in the format requested. Note, that nutritional
        values currently included in response only for the private foods.
      operationId: getFoodsFood.json
      x-api-path-slug: foodsfoodidjson-get
      responses:
        200:
          description: OK
      tags:
      - Foods
      - Food-id.json
  /activities/{id}.json:
    get:
      summary: Get Activities .json
      description: Get the details of a specific activity in Fitbit activities database
        in the format requested. If activity has levels, also get list of activity
        level details.
      operationId: getActivities.json
      x-api-path-slug: activitiesidjson-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Id.json
  /activities.json:
    get:
      summary: Get Activities.json
      description: Get a tree of all valid Fitbit public activities from the activities
        catalog as well as private custom activities the user created in the format
        requested. If activity has levels, also get a list of activity level details.
      operationId: getActivities.json
      x-api-path-slug: activitiesjson-get
      responses:
        200:
          description: OK
      tags:
      - Activities.json
  /user/-/devices.json:
    get:
      summary: Get User Devices.json
      description: Retrieve the list of Fitbit devices for a user in the format requested.
      operationId: getUserDevices.json
      x-api-path-slug: userdevicesjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Devices.json
  /user/-/foods/log/goal.json:
    post:
      summary: Post User Foods Log Goal.json
      description: Update (create) a user's daily calorie consumption goal or Food
        Plan and get a response in the format requested. Food Plan could not be created
        unless user already has active goal (Update-Weight-Goal). Depending on the
        weight goal setup only either MAINTENANCE (in case start weight is close to
        target weight or smaller) or one of the four other "lose" food plans could
        be created via intensity POST parameter.
      operationId: postUserFoodsLogGoal.json
      x-api-path-slug: userfoodsloggoaljson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Goal.json
    get:
      summary: Get User Foods Log Goal.json
      description: Get a user's current daily calorie consumption goal and/or Food
        Plan in the format requested.
      operationId: getUserFoodsLogGoal.json
      x-api-path-slug: userfoodsloggoaljson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Goal.json
  /user/-/meals.json:
    get:
      summary: Get User Meals.json
      description: Get a list of meals user created in his food log in the format
        requested.
      operationId: getUserMeals.json
      x-api-path-slug: usermealsjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Meals.json
  /foods.json:
    post:
      summary: Post Foods.json
      description: Create new private food for a user and get a response in a format
        requested. Created private food could be found in results of Search Foods
        call.
      operationId: postFoods.json
      x-api-path-slug: foodsjson-post
      responses:
        200:
          description: OK
      tags:
      - Foods.json
  /user/-/foods/log/water/{water-log-id}.json:
    delete:
      summary: Delete User Foods Log Water Water Log .json
      description: Delete user's water log entry with the given id.
      operationId: deleteUserFoodsLogWaterWaterLog.json
      x-api-path-slug: userfoodslogwaterwaterlogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Water
      - Water-log-id.json
  /user/-/foods/log/water.json:
    post:
      summary: Post User Foods Log Water.json
      description: Create log entry for a water using units in the unit system that
        corresponds to the Accept-Language header provided (or waterUnit) and get
        a response in the format requested.
      operationId: postUserFoodsLogWater.json
      x-api-path-slug: userfoodslogwaterjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Water.json
  /user/-/foods/log/water/date/{date}.json:
    get:
      summary: Get User Foods Log Water Date Date .json
      description: Get a summary and list of a user's water log entries for a given
        day in the format requested using units in the unit system which corresponds
        to the Accept-Language header provided.
      operationId: getUserFoodsLogWaterDateDate.json
      x-api-path-slug: userfoodslogwaterdatedatejson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Water
      - Date
      - Date.json
  /user/-/foods/log/favorite/{id}.json:
    delete:
      summary: Delete User Foods Log Favorite .json
      description: Delete the food with the given id from user's list of favorite
        foods.
      operationId: deleteUserFoodsLogFavorite.json
      x-api-path-slug: userfoodslogfavoriteidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Favorite
      - Id.json
    post:
      summary: Post User Foods Log Favorite .json
      description: Add the food with the given id to user's list of favorite foods.
      operationId: postUserFoodsLogFavorite.json
      x-api-path-slug: userfoodslogfavoriteidjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Favorite
      - Id.json
  /user/-/activities/goals/weekly.json:
    get:
      summary: Get User Activities Goals Weekly.json
      description: Get a user's current weekly activity goals in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided.
      operationId: getUserActivitiesGoalsWeekly.json
      x-api-path-slug: useractivitiesgoalsweeklyjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Goals
      - Weekly.json
  /user/-/activities/goals/daily.json:
    get:
      summary: Get User Activities Goals Daily.json
      description: Get a user's current daily activity goals in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided.
      operationId: getUserActivitiesGoalsDaily.json
      x-api-path-slug: useractivitiesgoalsdailyjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Goals
      - Daily.json
  /user/-/activities/log/favorite/{id}.json:
    delete:
      summary: Delete User Activities Log Favorite .json
      description: Delete the activity with the given id from user's list of favorite
        activities.
      operationId: deleteUserActivitiesLogFavorite.json
      x-api-path-slug: useractivitieslogfavoriteidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Log
      - Favorite
      - Id.json
    post:
      summary: Post User Activities Log Favorite .json
      description: Adds the activity with the given id to user's list of favorite
        activities.
      operationId: postUserActivitiesLogFavorite.json
      x-api-path-slug: useractivitieslogfavoriteidjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Log
      - Favorite
      - Id.json
  /user/-/foods/log/favorite.json:
    get:
      summary: Get User Foods Log Favorite.json
      description: Get a list of a user's favorite foods in the format requested.
        A user marks a food as favorite on the user's Food Tab tab. A favorite food
        in the list provides a quick way to log the food via the Log Food endpoint.
      operationId: getUserFoodsLogFavorite.json
      x-api-path-slug: userfoodslogfavoritejson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Favorite.json
  /user/-/foods/log/frequent.json:
    get:
      summary: Get User Foods Log Frequent.json
      description: Get a list of a user's frequent foods in the format requested.
        A frequent food in the list provides a quick way to log the food via the Log
        Food endpoint.
      operationId: getUserFoodsLogFrequent.json
      x-api-path-slug: userfoodslogfrequentjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Frequent.json
  /user/-/foods/log/recent.json:
    get:
      summary: Get User Foods Log Recent.json
      description: Get a list of a user's recent foods in the format requested. A
        recent food provides a quick way to log the food via the Log Food endpoint.
      operationId: getUserFoodsLogRecent.json
      x-api-path-slug: userfoodslogrecentjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Recent.json
  /user/-/activities/favorite.json:
    get:
      summary: Get User Activities Favorite.json
      description: Get a list of a user's favorite activities in the format requested.
        A user marks an activity as favorite on the user's Activities Tab. The activity
        ids in the list can be used to create a new activity log entry via the Log
        Activity.
      operationId: getUserActivitiesFavorite.json
      x-api-path-slug: useractivitiesfavoritejson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Favorite.json
  /user/-/activities/frequent.json:
    get:
      summary: Get User Activities Frequent.json
      description: Get a list of a user's frequent activities in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided. A frequent activity record contains the distance and duration values
        recorded the last time the activity was logged. The record retrieved can therefore
        be used to log the activity via the Log Activity with the same or adjusted
        values for distance and duration.
      operationId: getUserActivitiesFrequent.json
      x-api-path-slug: useractivitiesfrequentjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Frequent.json
  /user/-/activities/recent.json:
    get:
      summary: Get User Activities Recent.json
      description: Get a list of a user's recent activities in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided. A recent activity record contains the distance and duration values
        recorded the last time the activity was logged. The record retrieved can therefore
        be used to log the activity via the Log Activity with the same or adjusted
        values for distance and duration.
      operationId: getUserActivitiesRecent.json
      x-api-path-slug: useractivitiesrecentjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Recent.json
  /user/{user-id}/sleep/minutesAsleep/date/{start-date-or-end-date}/{end-date-or-period}.json:
    get:
      summary: Get User User Sleep Minutesasleep Date Start Date Or End Date End Date
        Or Period .json
      description: Get time series in the specified range for a given resource in
        the format requested using units in the unit system which corresponds to the
        Accept-Language header provided.
      operationId: getUserUserSleepMinutesasleepDateStartDateOrEndDateEndDateOrPeriod.json
      x-api-path-slug: useruseridsleepminutesasleepdatestartdateorenddateenddateorperiodjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Sleep
      - MinutesAsleep
      - Date
      - Start-date-or-end-date
      - End-date-or-period.json
  /user/{user-id}/foods/log/caloriesIn/date/{start-date-or-end-date}/{end-date-or-period}.json:
    get:
      summary: Get User User Foods Log Caloriesin Date Start Date Or End Date End
        Date Or Period .json
      description: Get time series in the specified range for a given resource in
        the format requested using units in the unit system which corresponds to the
        Accept-Language header provided.
      operationId: getUserUserFoodsLogCaloriesinDateStartDateOrEndDateEndDateOrPeriod.json
      x-api-path-slug: useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiodjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Foods
      - Log
      - CaloriesIn
      - Date
      - Start-date-or-end-date
      - End-date-or-period.json
  /user/-/body/log/fat/goal.json:
    post:
      summary: Post User Body Log Fat Goal.json
      description: Create or updates user's fat goal and get a response in the format
        requested.
      operationId: postUserBodyLogFatGoal.json
      x-api-path-slug: userbodylogfatgoaljson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Fat
      - Goal.json
    get:
      summary: Get User Body Log Fat Goal.json
      description: Get a user's current fat goal in the format requested.
      operationId: getUserBodyLogFatGoal.json
      x-api-path-slug: userbodylogfatgoaljson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Fat
      - Goal.json
  /user/-/body/log/weight/goal.json:
    post:
      summary: Post User Body Log Weight Goal.json
      description: Create or update user's weight goal using units in the unit system
        that corresponds to the Accept-Language header provided and get a response
        in the format requested.
      operationId: postUserBodyLogWeightGoal.json
      x-api-path-slug: userbodylogweightgoaljson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Weight
      - Goal.json
    get:
      summary: Get User Body Log Weight Goal.json
      description: Get a user's current weight goal using units in the unit system
        that corresponds to the Accept-Language header provided in the format requested.
      operationId: getUserBodyLogWeightGoal.json
      x-api-path-slug: userbodylogweightgoaljson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Weight
      - Goal.json
  /user/-/body/log/fat/{body-fat-log-id}.json:
    delete:
      summary: Delete User Body Log Fat Body Fat Log .json
      description: Delete user's body fat log entry with the given id.
      operationId: deleteUserBodyLogFatBodyFatLog.json
      x-api-path-slug: userbodylogfatbodyfatlogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Fat
      - Body-fat-log-id.json
  /user/-/body/log/fat/{body-weight-log-id}.json:
    delete:
      summary: Delete User Body Log Fat Body Weight Log .json
      description: Delete user's body weight log entry with the given id.
      operationId: deleteUserBodyLogFatBodyWeightLog.json
      x-api-path-slug: userbodylogfatbodyweightlogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Fat
      - Body-weight-log-id.json
  /user/-/body/log/fat.json:
    post:
      summary: Post User Body Log Fat.json
      description: Create log entry for a body fat and get a response in the format
        requested.
      operationId: postUserBodyLogFat.json
      x-api-path-slug: userbodylogfatjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Fat.json
  /user/-/body/log/weight.json:
    post:
      summary: Post User Body Log Weight.json
      description: Create log entry for a body weight using units in the unit system
        that corresponds to the Accept-Language header provided and get a response
        in the format requested.
      operationId: postUserBodyLogWeight.json
      x-api-path-slug: userbodylogweightjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body
      - Log
      - Weight.json
  /user/-/body.json:
    post:
      summary: Post User Body.json
      description: Log body measurements using units in the unit system that corresponds
        to the Accept-Language header provided.
      operationId: postUserBody.json
      x-api-path-slug: userbodyjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Body.json
  /user/{user-id}/body/weight/date/{start-date-or-end-date}/{end-date-or-period}.json:
    get:
      summary: Get User User Body Weight Date Start Date Or End Date End Date Or Period
        .json
      description: Get time series in the specified range for a given resource in
        the format requested using units in the unit system which corresponds to the
        Accept-Language header provided.
      operationId: getUserUserBodyWeightDateStartDateOrEndDateEndDateOrPeriod.json
      x-api-path-slug: useruseridbodyweightdatestartdateorenddateenddateorperiodjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Body
      - Weight
      - Date
      - Start-date-or-end-date
      - End-date-or-period.json
  /user/{user-id}/activities/calories/date/{start-date-or-end-date}/{end-date-or-period}.json:
    get:
      summary: Get User User Activities Calories Date Start Date Or End Date End Date
        Or Period .json
      description: Get time series in the specified range for a given resource in
        the format requested using units in the unit system which corresponds to the
        Accept-Language header provided.
      operationId: getUserUserActivitiesCaloriesDateStartDateOrEndDateEndDateOrPeriod.json
      x-api-path-slug: useruseridactivitiescaloriesdatestartdateorenddateenddateorperiodjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Activities
      - Calories
      - Date
      - Start-date-or-end-date
      - End-date-or-period.json
  /user/-/bp/{bp-log-id}.json:
    delete:
      summary: Delete User Bp Bp Log .json
      description: Delete user's blood pressure log entry with the given id.
      operationId: deleteUserBpBpLog.json
      x-api-path-slug: userbpbplogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Bp
      - Bp-log-id.json
  /user/-/heart/{heart-log-id}.json:
    delete:
      summary: Delete User Heart Heart Log .json
      description: Delete user's heart rate log entry with the given id.
      operationId: deleteUserHeartHeartLog.json
      x-api-path-slug: userheartheartlogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Heart
      - Heart-log-id.json
  /user/-/sleep/{sleep-log-id}.json:
    delete:
      summary: Delete User Sleep Sleep Log .json
      description: Delete user's sleep log entry with the given id.
      operationId: deleteUserSleepSleepLog.json
      x-api-path-slug: usersleepsleeplogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Sleep
      - Sleep-log-id.json
  /user/{user-id}/badges.json:
    get:
      summary: Get User User Badges.json
      description: Get user's badges in the format requested. Response includes all
        badges for the user as seen on the Fitbit website badge locker (both activity
        and weight related). We return weight and distance badges based on the user's
        unit profile preference as on the website.
      operationId: getUserUserBadges.json
      x-api-path-slug: useruseridbadgesjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Badges.json
  /user/-/activities/{activity-log-id}.json:
    delete:
      summary: Delete User Activities Activity Log .json
      description: Delete user's activity log entry with the given id.
      operationId: deleteUserActivitiesActivityLog.json
      x-api-path-slug: useractivitiesactivitylogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Activity-log-id.json
  /user/-/foods/log/{food-log-id}.json:
    delete:
      summary: Delete User Foods Log Food Log .json
      description: Delete the user's food log entry with the given id.
      operationId: deleteUserFoodsLogFoodLog.json
      x-api-path-slug: userfoodslogfoodlogidjson-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log
      - Food-log-id.json
  /user/-/glucose.json:
    post:
      summary: Post User Glucose.json
      description: Create log entry for a blood glucose measurement and/or HbA1c using
        units in the unit system which corresponds to the Accept-Language header provided
        and get a response in the format requested.
      operationId: postUserGlucose.json
      x-api-path-slug: userglucosejson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Glucose.json
  /user/-/bp.json:
    post:
      summary: Post User Bp.json
      description: Create log entry for a blood pressure measurement and get a response
        in the format requested.
      operationId: postUserBp.json
      x-api-path-slug: userbpjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Bp.json
  /user/-/heart.json:
    post:
      summary: Post User Heart.json
      description: Create log entry for a heart rate measurement and get a response
        in the format requested.
      operationId: postUserHeart.json
      x-api-path-slug: userheartjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Heart.json
  /user/-/sleep.json:
    post:
      summary: Post User Sleep.json
      description: Create log entry for a sleep and get a response in the format requested.
      operationId: postUserSleep.json
      x-api-path-slug: usersleepjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Sleep.json
  /user/-/foods/log.json:
    post:
      summary: Post User Foods Log.json
      description: Create log entry for a food. You need to select one of the unit
        ids to create a food log entry. It is possible to fetch unit ids allowed for
        specific food via previous calls to endpoints that retrieve food lists of
        the user. Each unit id maps to a unit in the list returned via the Get Food
        Units API call.
      operationId: postUserFoodsLog.json
      x-api-path-slug: userfoodslogjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Foods
      - Log.json
  /user/-/activities.json:
    get:
      summary: Get User Activities.json
      description: Get user's activity statistics in the format requested using units
        in the unit system which corresponds to the Accept-Language header provided.
        Response contains both lifetime statistics from the tracker device and total
        numbers including the manual activity log entries as seen on the Fitbit website
        dashboard.
      operationId: getUserActivities.json
      x-api-path-slug: useractivitiesjson-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities.json
    post:
      summary: Post User Activities.json
      description: Create log entry for an activity using units in the unit system
        which corresponds to the Accept-Language header provided (or using optional
        custom distanceUnit).
      operationId: postUserActivities.json
      x-api-path-slug: useractivitiesjson-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities.json
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---