---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Update Repositories Username Repo Slug Default Reviewers Target
    Username
  description: |-
    Adds the specified user to the repository's list of default
    reviewers.

    This method is idempotent. Adding a user a second time has no effect.
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/default-reviewers/{target_username}:
    delete:
      summary: Delete Repositories Username Repo Slug Default Reviewers Target Username
      description: Delete repositories username repo slug default reviewers target
        username
      operationId: deleteRepositoriesUsernameRepoSlugDefaultReviewersTargetUsername
      x-api-path-slug: repositoriesusernamerepo-slugdefaultreviewerstarget-username-delete
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Default
      - Reviewers
      - Target
      - Username
    get:
      summary: Get Repositories Username Repo Slug Default Reviewers Target Username
      description: |-
        Returns the specified reviewer.

        This can be used to test whether a user is among the repository's
        default reviewers list. A 404 indicates that that specified user is not
        a default reviewer.
      operationId: getRepositoriesUsernameRepoSlugDefaultReviewersTargetUsername
      x-api-path-slug: repositoriesusernamerepo-slugdefaultreviewerstarget-username-get
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Default
      - Reviewers
      - Target
      - Username
    parameters:
      summary: Parameters Repositories Username Repo Slug Default Reviewers Target
        Username
      description: Parameters repositories username repo slug default reviewers target
        username
      operationId: parametersRepositoriesUsernameRepoSlugDefaultReviewersTargetUsername
      x-api-path-slug: repositoriesusernamerepo-slugdefaultreviewerstarget-username-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Default
      - Reviewers
      - Target
      - Username
    put:
      summary: Update Repositories Username Repo Slug Default Reviewers Target Username
      description: |-
        Adds the specified user to the repository's list of default
        reviewers.

        This method is idempotent. Adding a user a second time has no effect.
      operationId: putRepositoriesUsernameRepoSlugDefaultReviewersTargetUsername
      x-api-path-slug: repositoriesusernamerepo-slugdefaultreviewerstarget-username-put
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Default
      - Reviewers
      - Target
      - Username
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