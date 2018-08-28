swagger: "2.0"
x-collection-name: Pingometer
x-complete: 1
info:
  title: Checks API
  description: the-checks-api-
  version: 1.0.0
host: api.pingdom.com
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
basePath: /