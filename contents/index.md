---
no_page_title: true
no_metadata: true
---
# Index

## Search
:jinja:`{% from 'macros/google_custom_search.html' import google_custom_search %}`
:jinja:`{{ google_custom_search(page) }}`


## Recent Update
:jinja:`{% from 'macros/recent_contents.html' import recent_contents %}`
:jinja:`{{ recent_contents(contents, num=10, subdirs=['entry/']) }}`

---

## [Category Index](category/)

:jinja:`{% from 'macros/grouped_contents.html' import grouped_contents %}`
:jinja:`{{ grouped_contents(contents, group='category', subdirs=['entry/']) }}`

---

- [Tag Index](tags/)
