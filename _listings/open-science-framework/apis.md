---
name: Open Science Framework
x-slug: open-science-framework
description: OSF provides free and open source project management support for researchers
  across the entire research lifecycle. As a collaboration tool, OSF helps researchers
  work on projects privately with a limited number of collaborators and make parts
  of their projects public, or make all the project publicly accessible for broader
  dissemination. As a workflow system, OSF enables connections to the many services
  researchers already use to streamline their process and increase efficiency. As
  a flexible repository, it can store and archive research data, protocols, and materials.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Institutions
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/apis.md
specificationVersion: "0.14"
apis:
- name: Open Science Framework - List all affiliated nodes
  x-api-slug: institutionsinstitution-idnodes-get
  description: |-
    A paginated list of all nodes affiliated with an institution.
    #### Versioning
    As of version `2.2`, affiliated components (in addition to affiliated top-level projects) are returned from this endpoint.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 nodes. Each resource in the array is a separate nodes object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include nodes that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/nodes?filter[title]=science.

    Nodes may be filtered by their `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-openapi.md
- name: Open Science Framework - List all affiliated registrations
  x-api-slug: institutionsinstitution-idregistrations-get
  description: |-
    A paginated list of all registrations affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 registrations. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include registrations that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/registrations?filter[title]=science.

    Registrations may be filtered by their  `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-openapi.md
- name: Open Science Framework - List all affiliated users
  x-api-slug: institutionsinstitution-idusers-get
  description: |-
    A paginated list of all users affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 users. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include users that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/users?filter[family_name]=Nosek.

    Users may be filtered by their `id`, `full_name`, `given_name`, `middle_names`, and `family_name`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-openapi.md
- name: Open Science Framework - List all affiliated nodes
  x-api-slug: institutionsinstitution-idnodes-get
  description: |-
    A paginated list of all nodes affiliated with an institution.
    #### Versioning
    As of version `2.2`, affiliated components (in addition to affiliated top-level projects) are returned from this endpoint.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 nodes. Each resource in the array is a separate nodes object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include nodes that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/nodes?filter[title]=science.

    Nodes may be filtered by their `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-openapi.md
- name: Open Science Framework - List all affiliated registrations
  x-api-slug: institutionsinstitution-idregistrations-get
  description: |-
    A paginated list of all registrations affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 registrations. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include registrations that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/registrations?filter[title]=science.

    Registrations may be filtered by their  `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-openapi.md
- name: Open Science Framework - List all affiliated users
  x-api-slug: institutionsinstitution-idusers-get
  description: |-
    A paginated list of all users affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 users. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include users that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/users?filter[family_name]=Nosek.

    Users may be filtered by their `id`, `full_name`, `given_name`, `middle_names`, and `family_name`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-openapi.md
- name: Open Science Framework - Root
  x-api-slug: get
  description: |-
    Welcome to the Open Science Framework API. With this API you can access users, projects, components, logs, and files from the [Open Science Framework](https://osf.io/). The Open Science Framework (OSF) is a free, open-source service maintained by the [Center for Open Science](http://cos.io/).

    #### Returns
    A JSON object with `meta` and `links` keys.

    The `meta` key contains information such as a welcome message from the API, the specified version of the request, and the full representation of the current user, if authentication credentials were provided in the request.

    The `links` key contains links to the following entity collections: [addons](), [collections](), [institutions](#Institutions_institutions_list), [licenses](#Licenses_license_list), [metaschemas](), [nodes](#Nodes_nodes_list), [registrations](), [users](#Users_users_list)
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/get-openapi.md
- name: Open Science Framework - List all affiliated nodes
  x-api-slug: institutionsinstitution-idnodes-get
  description: |-
    A paginated list of all nodes affiliated with an institution.
    #### Versioning
    As of version `2.2`, affiliated components (in addition to affiliated top-level projects) are returned from this endpoint.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 nodes. Each resource in the array is a separate nodes object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include nodes that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/nodes?filter[title]=science.

    Nodes may be filtered by their `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idnodes-get-openapi.md
- name: Open Science Framework - List all affiliated registrations
  x-api-slug: institutionsinstitution-idregistrations-get
  description: |-
    A paginated list of all registrations affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 registrations. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include registrations that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/registrations?filter[title]=science.

    Registrations may be filtered by their  `id`, `title`, `description`, `public`, `tags`, `category`, `date_created`, `date_modified`, `root`, `parent`, `contributors`, and `preprint`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idregistrations-get-openapi.md
- name: Open Science Framework - List all affiliated users
  x-api-slug: institutionsinstitution-idusers-get
  description: |-
    A paginated list of all users affiliated with an institution.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of 10 users. Each resource in the array is a separate users object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    #### Filtering
    You can optionally request that the response only include users that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/institutions/cos/users?filter[family_name]=Nosek.

    Users may be filtered by their `id`, `full_name`, `given_name`, `middle_names`, and `family_name`
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/institutionsinstitution-idusers-get-openapi.md
- name: Open Science Framework - Root
  x-api-slug: get
  description: |-
    Welcome to the Open Science Framework API. With this API you can access users, projects, components, logs, and files from the [Open Science Framework](https://osf.io/). The Open Science Framework (OSF) is a free, open-source service maintained by the [Center for Open Science](http://cos.io/).

    #### Returns
    A JSON object with `meta` and `links` keys.

    The `meta` key contains information such as a welcome message from the API, the specified version of the request, and the full representation of the current user, if authentication credentials were provided in the request.

    The `links` key contains links to the following entity collections: [addons](), [collections](), [institutions](#Institutions_institutions_list), [licenses](#Licenses_license_list), [metaschemas](), [nodes](#Nodes_nodes_list), [registrations](), [users](#Users_users_list)
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/institutions/master/_listings/open-science-framework/get-openapi.md
x-common:
- type: x-website
  url: https://cos.io
- type: x-api-gallery
  url: http://open.fintech.api.gallery.streamdata.io
- type: x-api-stack
  url: http://open.science.framework.stack.network
- type: x-github
  url: https://github.com/OSFramework
- type: x-twitter
  url: https://twitter.com/OSFramework
- type: x-website
  url: http://osf.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---