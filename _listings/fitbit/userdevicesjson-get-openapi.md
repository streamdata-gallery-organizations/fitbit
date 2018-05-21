---
swagger: "2.0"
x-collection-name: Fitbit
x-complete: 0
info:
  title: Fitbit Get User Devices.json
  description: Retrieve the list of Fitbit devices for a user in the format requested.
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