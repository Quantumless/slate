---
title: Get categories

language_tabs:
  - shell
  - python

toc_footers:
 - <a href='http://www.ecwid.com'>Register your application in Ecwid</a>
---

# Get categories

Returns an array of immediate subcategories of a given parent category. If the parent parameter is absent, returns all categories. If parent=0, returns a list of root categories. Disabled categories are not returned, but enabled subcategories of disabled categories are.

## URL

GET http(s)://app.ecwid.com/api/v2/**[STORE-ID/categories?parent=number​&hidden_categories=boolean​&productIds=boolean​&secure_auth_key=string
