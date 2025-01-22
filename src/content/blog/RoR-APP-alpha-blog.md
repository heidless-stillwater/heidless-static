---
author: Rob Craig
pubDatetime: 2024-06-01T15:57:52.737Z
title: RoR-APP-alpha-blog
postSlug: RoR-APP-alpha-blog
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - alpha-blog
  - ruby-on-rails
  - cloud-run
  - docker
description: Ruby on Rails App - multi-user Blog env
---

## <a href="https://alpha-blog-svc-58856964484.europe-west1.run.app/"  target="_blank">App: alpha blog</a>

#

## Multi-user blog environment.

- ### link

  - USERNAME: demo@heidless-app-0.com
  - PASSWORD: password

- ### Bloggers

  - List all Bloggers registerd with the site (including 'Admin')
  - All Users visible including their Articles

- ### Articles

  - create New Articles for current user
  - 'View Articles'
    - List ALL articles for ALL users
  - category
    - choose from list of categories
    - new categories create under 'Catogories' menu

- ### Categories

  - 'Create New Category'
    - ONLY Available to Admin user
    - does what it says on the tin
  - 'View Categories': lists all available categories for selection with Articles
  - All Categories available to All Users

- ### Profile(s)
  - List ALL Users

## tech info

- Rails 6
- Google Cloud
  - Postgres
  - Credentials via Secret Mgr
