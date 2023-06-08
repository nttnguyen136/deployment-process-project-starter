# Udagram Application

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/nttnguyen136/deployment-process-project-starter/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/nttnguyen136/deployment-process-project-starter/tree/master)


# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

Project infrastructure can be found [here](Docs/Infrastructure.md)

Project dependencies can be found [here](Docs/Dependencies.md)

Project using Circle CI to trigger deployment [Pipeline](Docs/Pipeline.md)

All screenshot can be found [HERE](Docs/Screenshot)

## AWS Cloud Setup

- RDS - Database Host: udagramdb.crbwrjjhbvjo.us-east-1.rds.amazonaws.com
- RDS - Database Port: 5432
- S3 - Frontend: http://udagram-fe.s3-website-us-east-1.amazonaws.com
- Elastic Beanstalk - API: http://udagram-api-dev.us-east-1.elasticbeanstalk.com/ 


### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
