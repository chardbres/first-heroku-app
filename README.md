[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Rails Deployment with Heroku

You've learned a lot about how to build a Rails application over the last few
weeks. Now let's "go public" and share our apps with the world!

## Prerequisites

- [rails-api](https://git.generalassemb.ly/ga-wdi-boston/rails-api)
- This guide assumes you have followed [these installation instructions](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#installation)
  up to where the steps mention Heroku.

## Objectives

After this lesson, developers will be able to:

- Explain what Heroku is
- Create a Heroku app from the command line
- Deploy our app to Heroku
- Configure our production application environment
- Setup our production database
- View our running application

### What is Heroku?



### Getting Started

We are going to use Heroku to host our Rails API, the backend for our first full-stack project. 

Make sure you have a new repository on Github for your project. You should continue to push your code to your Github repo. In addition, you will now be able to push code to a repository hosted on Heroku which will update your hosted app on their servers.

To deploy a new application to Heroku:

- [ ] [Create a New Heroku App](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#create-a-new-heroku-app)
- [ ] [Push `master` to Heroku](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#push-master-to-heroku)
- [ ] [Update Heroku's Database](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#update-herokus-database)
- [ ] [Setup Your Environment](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#setup-your-production-environment)
- [ ] [Check Your Work](https://git.generalassemb.ly/ga-wdi-boston/rails-api-template#run-your-server)

Head over to the [rails-heroku-deployment-guide](git.generalassemb.ly/ga-wdi-boston/rails-api-template/rails-heroku-deployment-guide.md) to get started.

### Connecting a client to your Heroku API

We can send cURL requests to our new application by simply changing our URL from your running client (usually we are on `localhost:7165`), to our production application's url, something like

In our JavaScript frontend based on the [browser-template](git.generalassemb.ly/ga-wdi-boston/browser-template), we can edit the `app/config.js` file and fill in our shiny new Heroku application url in the `production` field. Make sure to _not_ use the `git` url ending in `.git`. Check `heroku info` to see the various Heroku URLs.

### Share Your App **(REQUIRED)**

Once you've completed the above steps, share your new application: 

1. [Open a Pull Request on this repository](https://git.generalassemb.ly/ga-wdi-boston/rails-heroku-setup-guide/compare).

1. Make sure to include the deployed URL of your Heroku app in the Pull Request.


## Additional Resources

- [Heroku Command Line](https://devcenter.heroku.com/categories/command-line)
- [Heroku Rails Deployment](https://devcenter.heroku.com/articles/getting-started-with-rails5)

## [License](LICENSE)

1. All content is licensed under a CC­BY­NC­SA 4.0 license.
1. All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
