---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Post Users User Favorites Users Target User
  description: Creates a new favorite listing for a user
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/favorites/users/{target_user_id}:
    get:
      summary: Get Users User Favorites Users Target User
      description: Finds a favorite user for a user
      operationId: getUsersUserFavoritesUsersTargetUser
      x-api-path-slug: usersuser-idfavoritesuserstarget-user-id-get
      parameters:
      - in: path
        name: target_user_id
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Users
      - Target
      - User
    post:
      summary: Post Users User Favorites Users Target User
      description: Creates a new favorite listing for a user
      operationId: postUsersUserFavoritesUsersTargetUser
      x-api-path-slug: usersuser-idfavoritesuserstarget-user-id-post
      parameters:
      - in: path
        name: target_user_id
      - in: query
        name: target_user_id
      - in: path
        name: user_id
      - in: query
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Users
      - Target
      - User
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