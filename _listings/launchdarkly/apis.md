---
name: LaunchDarkly
x-slug: launchdarkly
description: Our vision is to eliminate risk for developers and operations teams from
  the software development cycle. As companies transition to a world built on software,
  there is an increasing requirement to move quickly&mdash;but that often comes with
  the desire to maintain control. LaunchDarkly is the feature management platform
  that enables dev and ops teams to control the whole feature lifecycle, from concept
  to launch to value. Feature flagging is an industry best practice of wrapping a
  new or risky section of code or infrastructure change with a flag. Each flag can
  easily be turned on/off independent of code deployment (aka &rdquo;dark launching&rdquo;).
  Equipping businesses with the ability to move at the speed of every deploy allows
  an entire company to learn rapidly, deliver value to their customers faster, and
  produce more value. Developers can build, marketing can launch, product can iterate,
  and sales can sell.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
x-kinRank: "7"
x-alexaRank: "187776"
tags: Hooks
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/apis.md
specificationVersion: "0.14"
apis:
- name: Launch Darkly Fetch a list of all webhooks
  x-api-slug: launch-darkly
  description: Fetch a list of all webhooks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooks-get-openapi.md
- name: Launch Darkly Create a webhook
  x-api-slug: launch-darkly
  description: Create a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooks-post-openapi.md
- name: Launch Darkly Delete a webhook by ID
  x-api-slug: launch-darkly
  description: Delete a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-delete-openapi.md
- name: Launch Darkly Get a webhook by ID
  x-api-slug: launch-darkly
  description: Get a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-get-openapi.md
- name: Launch Darkly Modify a webhook by ID
  x-api-slug: launch-darkly
  description: Modify a webhook by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2//webhooks/{resourceId}
  tags: Webhooks,ResourceId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/webhooksresourceid-patch-openapi.md
- name: Launch Darkly
  x-api-slug: launch-darkly
  description: Our vision is to eliminate risk for developers and operations teams
    from the software development cycle. As companies transition to a world built
    on software, there is an increasing requirement to move quickly&mdash;but that
    often comes with the desire to maintain control. LaunchDarkly is the feature management
    platform that enables dev and ops teams to control the whole feature lifecycle,
    from concept to launch to value. Feature flagging is an industry best practice
    of wrapping a new or risky section of code or infrastructure change with a flag.
    Each flag can easily be turned on/off independent of code deployment (aka &rdquo;dark
    launching&rdquo;). Equipping businesses with the ability to move at the speed
    of every deploy allows an entire company to learn rapidly, deliver value to their
    customers faster, and produce more value. Developers can build, marketing can
    launch, product can iterate, and sales can sell.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: Hooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hooks/master/_listings/launchdarkly/openapi.md
x-common:
- type: x-website
  url: http://www.launchdarkly.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/launchdarkly
- type: x-email
  url: sales@launchdarkly.com
- type: x-email
  url: privacy@launchdarkly.com
- type: x-email
  url: security@launchdarkly.com
- type: x-github
  url: https://github.com/launchdarkly
- type: x-curated-source
  url: http://launchdarkly.com/blog/stripe-webhook-event-processing-best-practices/
- type: x-website
  url: http://launchdarkly.com
- type: x-twitter
  url: https://twitter.com/LaunchDarkly
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---