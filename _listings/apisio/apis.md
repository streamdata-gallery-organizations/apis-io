---
name: APIs.io
x-slug: apisio
description: APIs.io os an experimental API Search service to help discover APIs on
  the web. The service uses the APIs.json proposed discovery format. To find APIs
  type your request in the search box. To get listed follow the instructions in the
  FAQ. The Search engine is also open source so you can run your own copy.
image: http://apis.io/logo_square.png
x-kinRank: "10"
x-alexaRank: ""
tags: APIs.io
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/apis.md
specificationVersion: "0.14"
apis:
- name: APIs.io Get APIS
  x-api-slug: apisio
  description: List all the APIs available
  image: http://apis.io/logo_square.png
  humanURL: http://apis.io/
  baseURL: http://apis.io/api///apis
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/apis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/apis-get-openapi.md
- name: APIs.io Search APIs
  x-api-slug: apisio
  description: Search for apis
  image: http://apis.io/logo_square.png
  humanURL: http://apis.io/
  baseURL: http://apis.io/api///search
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/search-get-openapi.md
- name: APIs.io Add APIs
  x-api-slug: apisio
  description: Adds an API to APIs.io
  image: http://apis.io/logo_square.png
  humanURL: http://apis.io/
  baseURL: http://apis.io/api///apis
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/apis-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/apis-post-openapi.md
- name: APIs.io Get Maintainers
  x-api-slug: apisio
  description: Returns a list of maintainers
  image: http://apis.io/logo_square.png
  humanURL: http://apis.io/
  baseURL: http://apis.io/api///maintainers
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/maintainers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/maintainers-get-openapi.md
- name: APIs.io
  x-api-slug: apisio
  description: APIs.io os an experimental API Search service to help discover APIs
    on the web. The service uses the APIs.json proposed discovery format. To find
    APIs type your request in the search box. To get listed follow the instructions
    in the FAQ. The Search engine is also open source so you can run your own copy.
  image: http://apis.io/logo_square.png
  humanURL: http://apis.io/
  baseURL: http://apis.io/api/
  tags: APIs.io
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apis.io/master/_listings/apisio/openapi.md
x-common:
- type: x-apijson--authoritative
  url: http://apis.io/apis.json
- type: x-github
  url: https://github.com/apisio
- type: x-twitter
  url: https://twitter.com/apisio
- type: x-website
  url: http://apis.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---