# Pipeline Information

This project uses CircleCI for automation and continous integration/deployment.

## Workflow

1. Commit is pushed to Github.
2. CircleCI gets notified.
3. CircleCI setups an environment with NodeJS and AWS CLIs.
4. CircleCI downloads a copy of the repository.
5. CircleCI runs install scripts on the backend and frontend.
6. CircleCI runs build scripts on the backend and frontend.
7. CircleCI deploys frontend files to Amazon S3.
8. CircleCI deploys backend files to Amazon Elasticbeanstalk
