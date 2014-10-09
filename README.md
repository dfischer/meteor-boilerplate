meteor-boilerplate
==================

A meteor project structure + obvious packages for bootstrapping new meteor projects.

```
client/
  compatibility/
  views/
    admin/
    landing_pages/
      home.html
      home.js
      home.scss
    layouts
      main.html
      main.js
lib/
  router.js
  routes/
    landing_pages.js
models/
public/
server/
  publications.js
  fixtures.js
```

Packages
* iron-router
* spiderable
* meteorhacks:npm
* iron-router-active
* ms-seo
* spinner
* email
* accounts-password
* accounts-ui
* LESS

There is no CSS framework because most people use bootstrap and I heavily dislike bootstrap so you can add that yourself if you like it. I recommend you check out http://semantic-ui.com though :).
