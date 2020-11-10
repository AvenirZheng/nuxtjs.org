---
title: Custom Plugins
description: In this example we show how you how you can create your own plugin
position: 404
category: plugins
csb_link: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/04_directory_structure/12_plugins_custom_plugin
---

<example-intro></example-intro>

`plugins/hello.js` - logs a message to the console with a dynamic message.

`store/index.js` - stores our dynamic message from our input.

`pages/hello-plugin.vue` uses the hello plugin to:

- log a message to the console on mounted.
- log a message to the console containing the value from our input.

`plugins/nuxt-api.js` - fetches data from our API.

`pages/api-plugin.vue` - uses our plugin to fetch and show the data from our API.

`nuxt.config.js` - registers our plugins using the `plugins` property.

<base-alert type="next">

Learn more in the Directory Structure book in the [plugins](/guides/directory-structure/plugins#inject-in-root--context) chapter.

</base-alert>

<code-sandbox :src="csb_link"></code-sandbox>
