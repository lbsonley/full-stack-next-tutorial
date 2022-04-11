---
id: getting-started
title: Getting Started
tags: 
  - setup
---

# Getting Started

## Prerequisites

This tutorial is targeted at medium to advanced level frontend developers. Basic skills needed to participate:

* Executing terminal commands (git, npm scripts)
* Developing React Apps with Next.js

Skills which will benefit you, but are not required:

* Querying a GraphQL Server
* Running Docker Containers
* Deploying Frontend Web Apps with Vercel

Skills you will learn:
* Implementing OAuth2 Authentication
* Deploying Backend Apps with Heroku

With that being said, it is also ok if you are not familiar with all of these skills. This is, afterall, a tutorial and you will learn these skills along the way.

## Docker

If you have not already, please install Docker on your machine.

## Vercel

If you have not already, please setup an account with Vercel. We will use this to deploy the frontend of our App.

## Heroku

If you have not already, please setup an account with Heroku. We will use this to deploy the backend of our App.

## Auth0

If you have not already, please setup an account with Auth0. We will use this as the identity provider for our App.

## Stripe Developer Account

[Signup](https://dashboard.stripe.com/register)
[Integrate with Auth0](https://marketplace.auth0.com/integrations/stripe-connect-social-connection)

## Clone the Repository and Install Dependencies

Clone the [App Repository](https://google.com) to your local machine. After you have cloned the project, you will need to install the dependencies.

To facilitate smooth deployment of frontend and backend separately. Each directory has it's own dependencies. Additionally, testing, linting and commit-hook dependencies are defined at the repository root.

That means you have to install dependencies three times. It also means you have to pay attention when you are adding dependencies to ensure they are being added to the correct `package.json`.

To get started, you will need to run `yarn install` three times. Once from the repository root, then from the `frontend` directory, and finally from `backend` directory.

## Checkpoints

Throughout this tutorial, we will be adding features to the project. Each feature will have a corresponding `checkpoint` branch. In the event that you do not finish the feature in the alotted time, you can commit your incomplete code to a new branch, and checkout the next `checkpoint` branch, so that you can continue working on the next feature.

To start, please run `git checkout checkpoint/genesis`. This is the starting point for this tutorial.
