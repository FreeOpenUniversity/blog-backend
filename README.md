# Intro
The blog backend is based on this strapi blog template: https://github.com/strapi/strapi-template-blog

It has been deployed to Heroku: https://strapiblog-backend.herokuapp.com/admin

# Getting Started

```
# Using NPM
npm install
npm run develop
npm start
```
You also need to add a ```.env``` file in the root folder to store values of **AWS_ACCESS_KEY_ID** and **AWS_ACCESS_SECRET**, this is for the AWS S3 upload provider which stores the images