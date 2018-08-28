swagger: "2.0"
x-collection-name: Etsy
x-complete: 1
info:
  title: Etsy
  description: bring-etsys-handmade-marketplace-and-community-into-your-apps-
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
    delete:
      summary: Delete Users User Favorites Users Target User
      description: Delete a favorite listing for a user
      operationId: deleteUsersUserFavoritesUsersTargetUser
      x-api-path-slug: usersuser-idfavoritesuserstarget-user-id-delete
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