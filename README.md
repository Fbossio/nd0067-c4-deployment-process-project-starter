# Udagram

## Project overview
Udagram is a full-stack application built using Angular for the frontend, Express for the backend API, and PostgreSQL for the database. It is deployed on AWS Cloud, providing users the ability to create an account, log in, and post photos.

## Link to Frontend Application
Access the live application through this [link](http://udagram-432253917402.s3-website-us-east-1.amazonaws.com)

## Frontend views
Upon accessing the link provided, you will encounter the main view of the frontend application.

![frontend main view](./assets/working-application-view-1.png)

To create an account, click on the 'Register' button.

![frontend register](./assets/working-application-register.png)

Once registered, you will be automatically logged into the application, and your provided email will be displayed in the navbar.

![frontend log in](./assets/working-application-logged-user.png)

## Infrastructure Screenshots

1. AWS RDS for PostgreSQL Database

![RDS Posrgres](./assets/rds-overview.png)

2. AWS Elastic Beanstalk for Deploying API

![AWS EB](./assets/elastic-beanstalk-overview.png)

3. AWS S3 for Hosting the Angular App

![AWS S3 - 1](./assets/s3-properties.png)

![AWS S3 - 2](./assets/s3-website-hosting-enabled.png)


## CI/CD Screenshots

1. CircleCi Last successful build

![CircleCi build](./assets/circleci-build-success.png)

2. CircleCi Last successful deploy

![CircleCi deploy](./assets/circleci-deploy-success.png)

3. CircleCi env variables

![CircleCi env-variables](./assets/circleci-env-variables.png)


## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)

