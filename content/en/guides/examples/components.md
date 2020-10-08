---
title: Components
description: Use fetch in your components to fetch data from an API as well as auto importing and lazy loading components
position: 53
category: examples
csb_link: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/04_directory_structure/03_components
---

`components/MountainsList.vue` uses fetch to fetch data from an API and uses: - `$fetchState.pending` to show a loading message when waiting for the data to load. - `$fetchState.error` to show an error message if the component does not load.

`pages/index.vue` shows how to lazy load a component by prefixing it with the world lazy.

`nuxt.config.js` shows `components: true` for auto importing components.

<base-alert type="next">

Learn more in the Directory Structure book in the [Components](/guides/directory-structure/components) chapter.

</base-alert>

<code-sandbox :src="csb_link"></code-sandbox>
