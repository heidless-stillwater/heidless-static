---
author: Rob Craig
pubDatetime: 2024-06-01T15:57:52.737Z
title: RoR-APP-airbnb-clone
postSlug: RoR-APP-airbnb-clone-0
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - airbnb-clone
  - ruby-on-rails
  - cloud-run
  - docker
  - devise
  - stimulus
  - geocode
description: RoR App - airbnb clone
---

## <a href="https://airbnb-clone-v1-svc-58856964484.europe-west1.run.app/"  target="_blank">App: airbnb clone</a>

#

### login

- USERNAME: demo@heidless-app-0.com
- PASSWORD: password

### description

- WIP: Implementation to date:
  - SignUp/SignIn functionality
    - Modal Pop Up
    - Seed test users by DB Migration

### key functionality

- ### custom domain mapping:
- ### geocoding
  - distance from USERS location to Destination
    - if NOT logged in use location of IP
    - if LOGGED in use PROFILE home address
- ### devise: user mgmt
- ### stimulus: javascript functionality
  - modal login/signup popup
  - dynamic form validation
  - 'favorite' property
