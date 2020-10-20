---
title: Directory Structure
description: Basic project with pages, components, assets and static directory as well as the nuxt.config and package.json files.
position: 3
category: examples
csb_link: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/01_get_started/03_directory_structure?
---

<example-intro></example-intro>

- The `assets` folder contains an svg and a css file.
- The `components` folder contains a navigation component.
- The `pages` folder contains pages at root level as well as inside a folder.
- The `static` folder contains a favicon.
- The `nuxt.config.js` file shows:
  - `components` property set to true so that you can use components without having to write import statements.
  - `css` property to globally add css to your application

<base-alert type="next">

Learn more in the Get Started book in the [Directory Structure](/guides/get-started/directory-structure) chapter.

</base-alert>

<code-sandbox :src="csb_link"></code-sandbox>
