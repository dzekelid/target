swagger: "2.0"
x-collection-name: Server Density
x-complete: 1
info:
  title: Widgets API
  description: the-widgets-api-
  version: 1.0.0
host: api.serverdensity.io.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/alerts/targets ':
    ' get ':
      summary: Alerts Targets
      description: Gets a list of all alert targets that are visible to you as a customer.
      operationId: -alerts-targets-
      x-api-path-slug: alertstargets-get
      responses:
        200:
          description: OK
      tags:
      - Alerts