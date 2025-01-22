---
author: Rob Craig
pubDatetime: 2024-06-01T15:57:52.737Z
title: RoR-APP-photo-app
postSlug: RoR-APP-photo-app
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - photo-app
  - cloud-run
  - AWS
  - AWS S3
  - S3
  - docker
  - ruby-on-rails
  - devise
  - sendgrid
  - gcloud-domain-mapping
description: Ruby on Rails App - photo mgmnt app
---

## <a href="https://photo-app-svc-590618864324.europe-west1.run.app" target="_blank">photo app</a>

#

### login

- USERNAME: demo@heidless-app-0.com
- PASSWORD: password

### integrations

- ### devise

  - registration confirmation by email
  - activation via email

- ### sendgrid

  - proxy enable email comms via app

- ### Google Cloud Domain Mapping

  - allows use of a Curstom Domain
  - used to enable sendgrid email comms

- ### active_record
  - used to enable image persistence
    - uses AWS S3 for image storage
  - live deploy uses Google Cloud
