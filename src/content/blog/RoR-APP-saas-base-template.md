---
author: Rob Craig
pubDatetime: 2024-06-01T15:57:52.737Z
title: RoR-APP-saas-base-template
postSlug: RoR-APP-saas-base-template
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - saas-base-template
  - devise
  - stripe
  - ruby-on-rails
  - cloud-run
  - docker
description: Ruby on Rails App - RoR-APP-saas-base-template
---

## <a href="https://rails-v6-1-7-base-0-svc-1089619978780.europe-west1.run.app/" target="_blank">App Name: SaaS Base Template</a>
#

Goal is to be able to quickly spin up a fully provisioned new SaaS project.

The 'standard' SaaS functionality is available out-of-the-box.

Allows focus on what makes the app unique.

Current 'standard' functionality:

- Devise Credentials Mgmt
  - Standard sign-up & sign-in functionality
  - Email Confirmation ()& activation) of Sign-Up

- SendGrid (twilio interface)
  - SignUp Confirmation
  - Verified by email

- Stripe
  - Credit Card Processing
  - SignUp dependent on successful payment


### login
- USERNAME: demo@heidless-app-0.com
- PASSWORD: password


### Tech Info
- Rails 6
- Google Cloud 
  - Domain Mapping
  - Postgres
  - Credentials via Rails Credentials & Goole Secret Mgr
- Devise User Mgmt
- Stripe Payment Integration
