---
title: "Ruby (Sinatra)"
---

Getting started with Django on Convox is easy. Your app will need a `Dockerfile` and `docker-compose.yml`.

See [Preparing an Application](/docs/preparing-an-application) for more details.

## What's Included

The Convox-generated `Dockerfile` and `docker-compose.yml` will set up the following:

#### bin/web

This wrapper script will be created to assist in booting your application. You can find the source [here](https://github.com/convox/sinatra/blob/master/bin/web).

#### nginx

Nginx is included in your application to buffer incoming connections and inject proper headers to incoming HTTPS requests. You can find the configuration [here](https://github.com/convox/sinatra/blob/master/conf/nginx.conf).

## Running the Application

See [Running Locally](/docs/running-locally) and [Deploying to Convox](/docs/deploying-to-convox).

