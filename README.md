# mahdi-sakib-portfolio-content

Public mirror of the published content for [mahdisakib.com](https://mahdisakib.com).

This repo intentionally holds **only** `content.json` — the same data
already served publicly (no auth) by the site's API. It exists so the
public site can read its content from a CDN (jsDelivr) that's always warm,
instead of depending on a free-tier API host that can go to sleep.

No secrets live here or ever will — those stay in the private
`mahdi-sakib-portfolio` repo. This repo is updated automatically by the
server every time content is published from the site's editor.
