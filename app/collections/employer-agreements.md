---
title: Employer agreements
tags: manage-apprenticeships
description: Improvements to the employer agreements section of the Manage apprenticeships service
breadcrumbs:
  text: Employer agreements
  href: /employer-agreements
related:
  items:
  - text: Prototype
    description: |
      Username: `esfa`
      Password: `educ4tion`
    href: https://esfa-ma-employer-agreements.herokuapp.com/
pagination:
  data: collections.employer-agreements
  reverse: true
  size: 50
permalink: "employer-agreements/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% else %}index{% endif %}.html"
order: 3
---
