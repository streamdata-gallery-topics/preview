---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get a preview list for parcel service presets.
  description: Get a preview list for parcel service presets..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/listings/option_templates/preview:
    get:
      summary: Get a preview list of option templates
      description: Gets a preview list of all available listing option templates.
      operationId: getRestListingsOptionTemplatesPreview
      x-api-path-slug: restlistingsoption-templatespreview-get
      responses:
        200:
          description: OK
      tags:
      - Preview
      - List
      - Of
      - Option
      - Templates
  /rest/orders/shipping/parcels/preview/{language?}:
    get:
      summary: Get a preview list for parcel services.
      description: Get a preview list for parcel services..
      operationId: getRestOrdersShippingParcelsPreviewLanguage
      x-api-path-slug: restordersshippingparcelspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Services
  /rest/orders/shipping/presets/preview/{language?}:
    get:
      summary: Get a preview list for parcel service presets.
      description: Get a preview list for parcel service presets..
      operationId: getRestOrdersShippingPresetsPreviewLanguage
      x-api-path-slug: restordersshippingpresetspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Service
      - Presets
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