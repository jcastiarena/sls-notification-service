# Serverless Notification Service

This service is part of a system to place bids on auctions for selling online books. It uses the serverless framework and various AWS services including DynamoDB, SQS, SES and S3. Its responsibility is to notify bidders and sellers via AWS SES.

## Install

```
git clone git@github.com:jcastiarena/sls-notification-service.git
cd sls-notification-service
npm i
sls deploy --verbose
```
