# Phase 1
1. Deploy application via serverless.com framework
2. Add additional endpoint
3. Add separate endpoint / lambda for something that needs to scale separately from the rest?
4. Spin up DynamoDB
5. Use DynamoDB for listing records from DB in API
6. Add entry to DynamoDB via API
7. Optimize Lambda functions, e.g. by using Express.js instead of Nest.js and optimizing build.

## Phase 2
1. Optimize Lambda function build, use Express.js instead of Nest.js
2. NTH: DNS resolving so it resolves to an actual domain

## Phase 3?
1. Add authentication on API Gateway

## Phase 4?
1. Replace serverless.com framework with setup via Terraform