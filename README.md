# Bael Netlify CMS Template

![Bael](https://i.imgur.com/e1zmiB2.jpg "Bael CMS Blog Template")

> Bael is a free template that gives you an easy way to start a blog that uses modern technologies like static-site JAMstack architecture, CSS grid layout, responsive design, and fuzzy search — all wrapped up in a brutalist aesthetic.

## Info

Bael runs using [Nuxt.js](https://nuxtjs.org), [Vue.js](https://vuejs.org), [Netlify CMS](https://netlifycms.org), and is hosted by [Netlify](https://netlify.com). Bael requires an account with Netlify and Github/Bitbucket to deploy. Made by [Jake 101](https://jake101.com)

## Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alexwelcing/flowers)


## Build Setup

``` bash
# install dependencies
$ yarn install # Or npm install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

## Edit content

Access `yourwebsite.com/admin`, e.g. `localhost:3000/admin`.

## Manage dynamic routes

When you use Netlify CMS' `folder` type, you actually create dynamic routes. For example, when creating a blog,
you render different content files with the same template. And for the blog to know which content to render,
it looks at the url and gets the specific content file. That's a dynamic route.

So If you create a `folder` type with Netlify CMS, add the folder as glob to the `dynamicRoutes` variable
in the `nuxt.config.js`.

MIT License
