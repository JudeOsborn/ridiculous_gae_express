# Ridiculously Simple App Engine + Express

A ridiculously simple App Engine + Express boilerplate for when you just want to start making stuff.

Static files go in the /static folder. Nothing but a basic html, css and js file.

## Setup

Install:
 * [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
 * [pip](https://pip.pypa.io/en/stable/installing)

## Local server server

	node server.js

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn
