# Node.js

 Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform.

# Heroku

Heroku is a cloud platform as a service (cool long-bearded programmer guys call such type of things "PaaS"). It allows you to deploy your web server, so everyone could see how awesome you are as a web developer.

# Architecture

Applications that are run on Heroku typically have a unique domain (typically "applicationname.herokuapp.com") used to route HTTP requests to the correct dyno. Each of the application containers, or dynos, are spread across a "dyno grid" which consists of several servers. Heroku's Git server handles application repository pushes from permitted users.

# Products

### The Heroku Platform

The Heroku network runs the customer's apps in virtual containers which execute on a reliable runtime environment. Heroku calls these containers "Dynos." These Dynos can run code written in Node, Ruby, PHP, Go, Scala, Python, Java, or Clojure. Heroku also provides custom buildpacks with which the developer can deploy apps in any other language. Heroku lets the developer scale the app instantly just by either increasing the number of dynos or by changing the type of dyno the app runs in.

### Heroku Postgres
Heroku Postgres is the Cloud database (DBaaS) service for Heroku based on PostgreSQL. Heroku Postgres provides features like continuous protection, rollback, and high availability; also forks, followers, and dataclips.
[Home Page](https://osamamousa204.github.io/reading-notes-301/)