---
name: The Guardian
x-slug: the-guardian
description: The Guardian is a British national daily newspaper which has grown into
  a national paper associated with a complex organisational structure and an international
  multimedia and web presence. The Guardian provides API access to articles accessible
  by tag and section, and a suite of open source data and tools. The Guardian makes
  content accessible to increase traffic, brand awareness, and as a marketing vehicle,
  including partnership opportunities via platform program.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: The Guardian
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/apis.md
specificationVersion: "0.14"
apis:
- name: The Guardian Search
  x-api-slug: the-guardian
  description: Searches news content across the Guardian news platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
  humanURL: http://www.guardian.co.uk/open-platform
  baseURL: https://content.guardianapis.com///search
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/search-get-openapi.md
- name: The Guardian Tags
  x-api-slug: the-guardian
  description: Retrieves the tags used across the Guardian news platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
  humanURL: http://www.guardian.co.uk/open-platform
  baseURL: https://content.guardianapis.com///tags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/tags-get-openapi.md
- name: The Guardian Sections
  x-api-slug: the-guardian
  description: Retrieves the sections used across the Guardian news platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
  humanURL: http://www.guardian.co.uk/open-platform
  baseURL: https://content.guardianapis.com///sections
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/sections-get-openapi.md
- name: The Guardian Editions
  x-api-slug: the-guardian
  description: Retrieves the editions of the Guardian news platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
  humanURL: http://www.guardian.co.uk/open-platform
  baseURL: https://content.guardianapis.com///editions
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/editions-get-openapi.md
- name: The Guardian
  x-api-slug: the-guardian
  description: The Content API is a public service for accessing all the content the
    Guardian creates and the collections we have of that content (tags and sections).
    There are over one and a half million items available published as far back as
    1999. This overview will give you some idea of what data is available, how to
    find what you need, and what you will see when you make a request to us.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/the-guardian-logo.png
  humanURL: http://www.guardian.co.uk/open-platform
  baseURL: https://content.guardianapis.com/
  tags: The Guardian
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-guardian/master/_listings/the-guardian/openapi.md
x-common:
- type: x-access-tiers
  url: http://open-platform.theguardian.com/access/
- type: x-base
  url: http://content.guardianapis.com/
- type: x-blog
  url: http://www.theguardian.com/open-platform/blog
- type: x-blog-rss
  url: http://www.theguardian.com/open-platform/blog/rss
- type: x-chrome-extension
  url: http://www.theguardian.com/open-platform/blog/idio-guardian-chrome-extension
- type: x-crunchbase
  url: http://www.crunchbase.com/organization/the-guardian
- type: x-documentation
  url: http://open-platform.theguardian.com/documentation/
- type: x-email
  url: openplatform@guardian.co.uk
- type: x-events
  url: http://developers.theguardian.com/events-&-talks.html
- type: x-explorer
  url: http://open-platform.theguardian.com/explore/
- type: x-faq
  url: http://www.theguardian.com/open-platform/faq
- type: x-forum
  url: http://groups.google.com/group/guardian-api-talk/
- type: x-getting-started
  url: http://www.theguardian.com/open-platform/getting-started
- type: x-github
  url: https://github.com/guardian
- type: x-java-library
  url: http://code.google.com/p/openplatform-java/w/list
- type: x-partners
  url: http://www.theguardian.com/open-platform/partner-programs
- type: x-php-library
  url: http://code.google.com/p/openplatform-php/
- type: x-python-library
  url: http://code.google.com/p/openplatform-python/
- type: x-selfservice-registration
  url: http://guardian.mashery.com/member/register
- type: x-slideshare
  url: http://www.slideshare.net/openplatform
- type: x-terms-of-service
  url: http://www.theguardian.com/open-platform/terms-and-conditions
- type: x-twitter
  url: https://twitter.com/gdndevelopers
- type: x-twitter
  url: https://twitter.com/GuardianData
- type: x-website
  url: http://www.guardian.co.uk/open-platform
- type: x-wikipedia-
  url: http://en.wikipedia.org/wiki/The_Guardian
- type: x-wordpress-plugin
  url: http://www.theguardian.com/open-platform/news-feed-wordpress-plugin
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---