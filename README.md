meteor-boilerplate
==================

A meteor best practices project structure + obvious packages for bootstrapping new meteor projects.

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

Explanation
-----------
This project structure gives you a nice amount of modularity. It's a change from the traditional MVC pattern (if you come from Rails especially). At first glance it may be weird to have `.js .html .scss` files together but in reality it makes a lot of sense. You don't have to do much context switching and each namespace is basically a self-contained module, which allows for easy abstraction into a package as needed.

Otherwise everything else should be pretty obvious. You have your publications, fixtures, and routing best practices.

Enjoy!

Packages
========

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
