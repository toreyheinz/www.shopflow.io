<template lang="pug">
div.main.navbar(role="navigation" aria-label="main navigation")
  div.container.pb-2
    div.navbar-brand
      a.navbar-item(href="/")
        img(src="~/assets/images/shopflow-logo.png" width="290" height="35")

nav.sub.navbar(role="navigation" aria-label="main navigation")
  div.container.pb-2.mb-4
    div.navbar-start
      a.navbar-item(href="/") Home
      a.navbar-item(href="/getting-started") Getting Started
      a.navbar-item(href="/features") Features
      a.navbar-item(href="/pricing") Pricing
      a.navbar-item(href="/") Updates
      a.navbar-item(href="/") About
      a.navbar-item(href="/") Contact
      a.navbar-item(href="/") ~Shopflow Login~

    div.navbar-end
      div.navbar-item contact@shopflow.io
      div.navbar-item 1.616.931.5828
</template>
