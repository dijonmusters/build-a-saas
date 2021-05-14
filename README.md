# Build a SaaS product with Next.js, Auth0, Prisma and Stripe

This is the project repo to accompany the Build a SaaS product with Next.js, Auth0, Prisma and Stripe course on egghead. In this course we step through building an egghead clone, where customers pay a recurring subscription to have access to premium courses. Additionally users will be able to purchase individual courses and own them for life.

## What does the course cover?

- when to use static site generation (SGG) vs serverside rendering (SSR)
- designing and querying relational databases
- authentication and authorization of both client pages and serverless functions
- using webhooks to communicate between distributed services
- managing dev and production environments across multiple services
- implementing individual payments and subscription-based billing

## What do you need to know?

Some experience building React or Node applications and using NPM would be beneficial but not required. We will be using tools that are built on these technologies but will explain the important bits as we go.

## Instructor

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/13792200?s=400&u=a4fe6e9e2a155e1f8e88cc261583c116d953d491&v=4" />
</div>

Hey! I'm Jon, a software engineer and egghead instructor from Melbourne Australia. The Jamstack is my jam! Outside of computers, I play basketball and love hanging out with my awesome daughter!

## Course outline

### Next.js

- create pages using file-based routing
- static site generation (SSG) for specific pages
- serverside rendering (SSR) for specific pages
- create serverless functions with API routes
- hosting on Vercel and environment variables

### Prisma

- design database schema
- use migrations to modify the structure of the database
- model many-to-many relationships between tables
- query data joining multiple tables

### Auth0

- implement social login with GitHub
- use webhooks to notify other services of new users

### Stripe

- charge a card using serverless functions
- create recurring monthly and yearly subscriptions
- implement a customer portal so users can manage their own subscription and payment info
- subscribe to webhook events to notify other services when changes occur

## More reading

Want to learn more about this stack? Check out my [egghead case study](https://egghead.io/blog/saas-app-with-nextjs-prisma-auth0-and-stripe) which explores these technology choices more deeply.

## What now?

(Let's get setup!)[./lessons/00_getting_setup.md]
