---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Get Host Reservation Purchase Preview
  version: 1.0.0
  description: |-
    Preview a reservation purchase with configurations that match those of your
                Dedicated Host.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetHostReservationPurchasePreview:
    get:
      summary: Get Host Reservation Purchase Preview
      description: |-
        Preview a reservation purchase with configurations that match those of your
                    Dedicated Host.
      operationId: gethostreservationpurchasepreview
      x-api-path-slug: actiongethostreservationpurchasepreview-get
      parameters:
      - in: query
        name: AutoPlacement
        description: Specify whether to enable or disable auto-placement
        type: string
      - in: query
        name: HostId.N
        description: The host IDs of the Dedicated Hosts you want to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
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