---
name: Refuge Restrooms
x-slug: refuge-restrooms
description: Refuge Restrooms is a web application that seeks to provide safe restroom
  access for transgender, intersex, and gender nonconforming individuals. Users can
  search for restrooms by proximity to a search location, add new restroom listings,
  as well as comment and rate existing listings. We&rsquo;re trans led and seek to
  create a community focused not only on finding existing safe restroom access, but
  also advocating for transgender, intersex, and gender nonconforming people&rsquo;s
  safety.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Refuge Restrooms
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/apis.md
specificationVersion: "0.14"
apis:
- name: Refuge Restrooms - Get all restroom records ordered by date descending.
  x-api-slug: v1restrooms-json-get
  description: ""
  image: ""
  humanURL: http://refugerestrooms.org
  baseURL: https://www.refugerestrooms.org//api
  tags: Gender, Restrooms, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restrooms-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restrooms-json-get-openapi.md
- name: Refuge Restrooms - Search for restroom records updated or created on or after
    a given date
  x-api-slug: v1restroomsby-date-json-get
  description: ""
  image: ""
  humanURL: http://refugerestrooms.org
  baseURL: https://www.refugerestrooms.org//api
  tags: Gender, Restrooms, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomsby-date-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomsby-date-json-get-openapi.md
- name: Refuge Restrooms - Search by location.
  x-api-slug: v1restroomsby-location-json-get
  description: ""
  image: ""
  humanURL: http://refugerestrooms.org
  baseURL: https://www.refugerestrooms.org//api
  tags: Gender, Restrooms, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomsby-location-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomsby-location-json-get-openapi.md
- name: Refuge Restrooms - Perform full-text search of restroom records.
  x-api-slug: v1restroomssearch-json-get
  description: ""
  image: ""
  humanURL: http://refugerestrooms.org
  baseURL: https://www.refugerestrooms.org//api
  tags: Gender, Restrooms, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomssearch-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/refuge-restrooms/master/_listings/refuge-restrooms/v1restroomssearch-json-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://reddit.api.gallery.streamdata.io
- type: x-api-stack
  url: http://refuge.restrooms.stack.network
- type: x-documentation
  url: https://refugerestrooms.org/api/docs/
- type: x-website
  url: http://refugerestrooms.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---